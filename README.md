# Agency review practice: fictional exercises and a team rehearsal

Practice commission-row matching, source-note lookup, task-cost arithmetic, link review, form mapping, flag-list review, source-instruction review, request-to-draft review and AI connector offboarding with fictional inputs and separate authored keys. Keep source evidence visible and uncertain fields unresolved before considering automation.

This is an educational reference, **not a reconciliation application, model benchmark, accounting recommendation or AMS integration**. All carriers, producers, references and amounts are invented. No customer records are included.

## Download all practice files

[Download the complete collection as a ZIP](https://github.com/MayberryDT/agency-commission-review-practice/archive/refs/heads/main.zip), then extract it and open the README for the exercise you want to try. No GitHub account or software installation is needed to download it. Keep the separate authored keys closed until you have tried the inputs; import CSV identifiers as text so leading zeros survive.

[Printable two-page review reference](resources/agency-review-reference.pdf): eight checks and links to the matching exercises. This summarises existing practice material; it adds no cases or measured results.

## Choose the task you want to practice

| Task | Start here | What to check |
| --- | --- | --- |
| Review proposed commission-row matches | [Five-case matching exercise](#commission-row-matching) | Preserve identifiers and leave ambiguous candidates unresolved. |
| Find the right earlier conversation | [Source-note lookup](related-practice/source-note-lookup/README.md) | Retain the exact source; do not invent an absent date or confirmation. |
| Calculate cost per checked result | [One-batch arithmetic](related-practice/batch-cost/README.md) | Separate unknown inputs from explicit zeros and stop on unusable counts. |
| Review a customer-facing resource link | [Link-review cases](related-practice/link-review/README.md) | Distinguish page access, the intended action and delivery evidence. |
| Map one request into different intake layouts | [Two-form mapping](related-practice/form-mapping/README.md) | Keep requester, assigned reviewer and completed review distinct; preserve source references. |
| Review the usefulness of a checker's flags | [Flag-list worksheet](related-practice/flag-review/README.md) | Calculate errors found and useful flags separately; look for missed errors outside the flagged list. |
| Distinguish a sender request from an instruction aimed at the assistant | [Fictional source-message practice](related-practice/source-instructions/README.md) | Preserve missing review evidence and ordinary quoted requests without treating source text as task authority. |
| Check whether a reply answers the whole request | [Request-to-draft review](related-practice/request-draft-review/README.md) | Find an omitted question alongside unsupported receipt, review and deadline claims. |
| Separate connector revocation from retained data | [AI connector offboarding](related-practice/connector-offboarding/README.md) | Distinguish one denied request, a retained copy and a queued deletion from broader conclusions. |
| Resume unfinished work after AI becomes unavailable | [Interruption handoff](related-practice/ai-interruption/README.md) | Separate confirmed work, unsent drafts and uncertain delivery before a person takes over. |

Each exercise supplies fictional inputs and a separate authored key. Try the inputs before opening its key. These are practice materials, not measured results from an AI tool; keep real customer information out of this repository and its issues.

## Rehearse a suspicious payment-change request

[Agency security tabletop](related-practice/security-tabletop/README.md): the existing Cirlet 15-minute fictional discussion, with editable exercise and after-action worksheets. For trainers and IT providers helping an agency identify its trusted verification route, approval owner and unanswered questions. This republishes existing kit material; it is not a live security test or a customer result. Its specific reuse terms are linked in the folder.

## Explain request verification to clients

[Editable client wording](related-practice/client-verification/README.md) includes an email paragraph, website copy and an owner review sheet. Replace the placeholders with your agency’s actual process before use. These are original sample messages, not evidence that a particular agency verifies requests or that a client has received them.

## One dated CLI observation

[A captured review of the request-to-draft fixture](observations/2026-10-22-grok-cli/README.md) includes the exact supplied prompt, first assistant response and runtime limits. It uses fictional inputs, supplies no performance score and does not establish fully isolated context or readiness for real agency records. The deliberately flawed teaching draft remains separate from the observed review.

## Commission-row matching

1. Open [the fictional register](commission-register-fictional.csv) and [statement rows](commission-statements-fictional.csv). Import policy references as **text** so `00104` and `00105` retain their leading zeros. Preserve the signed amount, including `-5.00`.
2. For each statement row, record candidate register references, supporting source fields, uncertainty and the next reviewer action. Do not choose an arbitrary first match when more than one candidate exists.
3. Compare your decisions with the [separate authored review key](AUTHORED-REVIEW.md). Try the inputs before reading it.

The exercise compares carrier, policy and term references. Those fields are not a universal matching rule: a real agency must decide which identifiers and source evidence are sufficient. A matching candidate never establishes what someone is owed or whether payment was received.

## Scope and provenance

These are the same source rows published in the [canonical agency software guide](https://insuranceagencyvirtualassistant.com/software#commission-review). That page also offers a printable two-page worksheet/key. The commission section distributes that existing exercise in plain text without adding commission cases, measured results or a model run. The separately linked form-mapping exercise is original fictional teaching material.

The material and this repository were prepared with AI assistance. Tyler Mayberry builds software through **Cirlet**, which offers scoped cybersecurity reviews, practical AI training and workflow automation help to independent insurance agencies. The canonical guide is on a commercial service site. No insurance-practitioner credentials, vendor affiliation, integration or client success are claimed.

Before using real records, establish agency/vendor permission, approved tools, named reviewers and stop conditions. Keep private records out of public repositories and issues. Coverage decisions, sending and financial approval remain with responsible people.

For a permitted trial, compare preparation, review and correction effort using the [whole-task cost worksheet](https://insuranceagencyvirtualassistant.com/cost#task-cost-worksheet). For optional hands-on help, see the Quickstart below.

## Want help putting this into everyday work?

The exercises are free to use on your own. If your team wants help setting up one real administrative workflow, Cirlet's [Agency AI & Security Quickstart](https://cirlet.com/quickstart) is $1,500 one time. It includes workflow setup, data and review rules for that task, a team working session for up to five people, written instructions and a verified handoff.

Start with a free, 30-minute conversation with Tyler. Scope, access and timing are agreed first. Training alone can be scoped separately. Keep client records, passwords and other secrets out of public repository discussions.

No expected commission, split, accounting entry, bank receipt, payroll, tax treatment, accuracy rate or savings is established by this exercise. It is not legal, insurance or accounting advice. No blanket open-source or data-reuse license is supplied by this repository. The separately labeled security-tabletop folder retains the original kit’s specific reuse terms.

## Related source-selection practice

The [separate source-note lookup exercise](related-practice/source-note-lookup/README.md) applies the evidence-preservation habit to fictional service notes: two same-name contacts, an absent date and no proof of a completed change. It is separate from the five commission cases.

## Related arithmetic practice

The [one-batch cost exercise](related-practice/batch-cost/README.md) supplies eight fictional input cases and a separate arithmetic key. It distinguishes blank inputs, explicit zeros and unusable counts, with a link to the existing local browser calculator. It does not calculate commissions or establish savings.

## Related link-review practice

The [three-case link-review exercise](related-practice/link-review/README.md) separates page access, the intended action and delivery. It includes the original fictional observations, a blank review sheet and separate authored key; it does not browse or test the example domains.
