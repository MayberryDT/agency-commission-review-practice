# Collection provenance

Collected October23,2026UTC. Private raw receipts retain per-query UTC times, stdout/stderr and exit status. Source directory commit `877ae321e53a44af231f4560b6d373ecfc9fb029`; source data SHA256 `4ac7e7f26500724419d01318af6026e570e76e90f47319074717daee31a1cdb3`. Source rows 1060; eligible unique two-label.com website domains 855; fixed selected sample20.

Selection: normalize website host to lowercase, remove one leading www., accept regex `[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.com`, deduplicate, sort by SHA256 of `cirlet-dns-pilot-20261023|` plus domain, select first20. Protocol written before collection. Source was existing published office data; no outreach export or private business records.

Initial command per domain: `dig @1.1.1.1 NAME TYPE +time=2 +tries=1 +noall +comments +answer`. Queries: MX at website domain; TXT at website domain; TXT at _dmarc.website-domain. At most3domains processed concurrently; each domain's queries sequential. Second resolver validation: same exact DMARC TXT query through9.9.9.9;20queries. Total80DNSqueries. No email or website/port/account tests.

TXT interpretation: concatenate quoted chunks within each TXT response row; count case-insensitive prefix v=spf1 or v=dmarc1 as a matching-looking record. This is not a full parser/validation/SPF evaluator/DMARC tree walk. For the six single matching DMARC records, retain the literal p value without asserting effective message handling. Errors stay unknown. Second-resolver comparison ignores TTL and sorts record lines but preserves status and record data.

The private observations and sample are not included in this public folder. Public claims are limited to aggregated pilot observations; exact independent sample reproduction is unavailable here. No global license change for the repository.

Primary protocol source read October23: https://www.rfc-editor.org/rfc/rfc9989.html (selected sections, not a full standards audit). https://www.rfc-editor.org/info/rfc7489/ identifies its supersession. No protocol text copied into this note.
