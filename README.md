# Agency commission-record review practice

A five-case fictional exercise for reviewing proposed matches between an agency policy register and commission-statement rows. Practice preserving source evidence and leaving ambiguous records unresolved before considering automation.

This is an educational reference, **not a reconciliation application, model benchmark, accounting recommendation or AMS integration**. All carriers, producers, references and amounts are invented. No customer records are included.

## Try it

1. Open [the fictional register](commission-register-fictional.csv) and [statement rows](commission-statements-fictional.csv). Import policy references as **text** so `00104` and `00105` retain their leading zeros. Preserve the signed amount, including `-5.00`.
2. For each statement row, record candidate register references, supporting source fields, uncertainty and the next reviewer action. Do not choose an arbitrary first match when more than one candidate exists.
3. Compare your decisions with the [separate authored review key](AUTHORED-REVIEW.md). Try the inputs before reading it.

The exercise compares carrier, policy and term references. Those fields are not a universal matching rule: a real agency must decide which identifiers and source evidence are sufficient. A matching candidate never establishes what someone is owed or whether payment was received.

## Scope and provenance

These are the same source rows published in the [canonical agency software guide](https://insuranceagencyvirtualassistant.com/software#commission-review). That page also offers a printable two-page worksheet/key. This repository distributes the existing exercise in a plain-text format; it adds no new cases, measured results or model run.

The material and this repository were prepared with AI assistance. Tyler Mayberry builds software through **Cirlet**, which offers paid AI and automation help to independent insurance agencies. The canonical guide is on a commercial service site. No insurance-practitioner credentials, vendor affiliation, integration or client success are claimed.

Before using real records, establish agency/vendor permission, approved tools, named reviewers and stop conditions. Keep private records out of public repositories and issues. Coverage decisions, sending and financial approval remain with responsible people.

For a permitted trial, compare preparation, review and correction effort using the [whole-task cost worksheet](https://insuranceagencyvirtualassistant.com/cost#task-cost-worksheet). For existing scoped help, see [Cirlet's service page](https://cirlet.com/virtual-assistant).

No expected commission, split, accounting entry, bank receipt, payroll, tax treatment, accuracy rate or savings is established by this exercise. It is not legal, insurance or accounting advice. No open-source or data-reuse license is supplied by this repository.
