# What a public-DNS pilot actually measured

By Cirlet · October 23, 2026 · Original observation, prepared with AI assistance

We queried public email-related DNS records for 20 website domains from an insurance-agency directory. The useful result is a small demonstration of what a checker can observe and what it must leave unanswered. **This is not a survey of agency security or a test of email delivery.**

## The observations

The first collection used Cloudflare's public resolver, 1.1.1.1. Each domain received three queries: MX, apex TXT and TXT at `_dmarc.<domain>`. All 60 query responses were retained with timestamps and status codes.

| Exact-name DMARC observation | Domains |
| --- | ---: |
| One returned TXT record beginning with `v=DMARC1` | 6 |
| No matching record returned, with NOERROR or NXDOMAIN status | 13 |
| SERVFAIL response, left unknown | 1 |
| Total selected domains | 20 |

Of the six matching records, five contained the literal `p=none` and one contained `p=reject`. We did not establish that those records were fully valid, discoverable policies for actual outbound messages. We did not observe whether reports were requested, delivered or reviewed.

At the website-domain apex, 16 domains returned one SPF-looking record, three returned none, and one returned two. Every domain returned MX records. None of these observations establishes that staff send email using that website domain, that SPF evaluates successfully, or that messages pass DMARC.

A separate verification queried the same 20 exact DMARC names through Quad9, 9.9.9.9. **Nineteen returned matching status and record data after ignoring TTL.** The remaining name returned SERVFAIL through the first resolver and NOERROR with no matching record through the second. The error remains an error in the original collection. We did not determine why the responses differed or which conditions changed between observations.

## Why an agency should care about the distinction

A useful checker report should preserve the domain, queried name, resolver, time, returned record and error state. A failed lookup should not silently become “no record.” A record's presence should not become “email protected.”

Before changing DNS, ask the person responsible for email which domains actually appear in outgoing From addresses, which systems send legitimate mail and what evidence supports the proposed change. Review authentication and delivery evidence with that provider; a website-domain lookup cannot supply it.

The current DMARC specification, [RFC 9989](https://www.rfc-editor.org/rfc/rfc9989.html), was published in May 2026 and supersedes RFC 7489. Its sections 5.1.4–5.1.7 describe starting with reporting, inspecting mail streams and considering delivery problems before choosing an enforcement policy. A literal `p=none` alone does not prove that monitoring is occurring. Section 11.4 also places display-name attacks outside DMARC's scope. Neither a DNS record nor a policy value establishes that a message's human sender is trustworthy.

## Sampling and limits

The source directory contained 1,060 published office records. We lowercased website hostnames, removed one leading `www.`, kept only two-label `.com` hostnames, and deduplicated them. That produced 855 eligible website domains. We sorted them by SHA256 of `cirlet-dns-pilot-20261023|<domain>` and selected the first 20 before querying DNS.

This is a narrow convenience frame, not a representative sample of US agencies, directory offices, email domains or other suffixes. Multiple office records can share a website. The directory's published classification was reused; this study did not independently reverify each business. No private systems, accounts, messages, ports, client records or provider configurations were accessed. No agency was contacted.

Only aggregates are published. Domain-level observations and selection records are retained privately for internal checking, so a reader cannot independently reproduce the exact sample from this public note alone. The collection recipe is documented; full public sample reproducibility is not claimed.

No breach, exposure rate, security ranking, AI-attack trend, MFA setting, DKIM result, sender alignment, policy coverage or customer outcome was measured. The pilot provides no national prevalence estimate. There is no named negative list and no recommendation to change a policy solely from these counts.

[Aggregate observation data](aggregate.json) · [Collection method and provenance](METHOD.md)

Cirlet maintains the free [agency security resource desk](https://aicybersecurityforinsuranceagencies.com/). This note is education, not a personalized security assessment or an endorsement from the listed protocol authors or resolver operators.
