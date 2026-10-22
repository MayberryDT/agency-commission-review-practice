# AI connector offboarding: four fictional evidence checks

Practice separating **new access** from **information already retained** when an AI connector trial ends. This is an original, AI-assisted teaching fixture, not a captured tool test, security assessment or customer result. All accounts, messages, timestamps and observations are invented.

## Try the exercise

1. Read [the fictional test setup](setup-fictional.md). It uses synthetic markers, not client records.
2. Review [four fictional observations](observations-fictional.csv). Each case is independent; do not combine them into a single incident timeline.
3. Complete [the blank evidence sheet](review-blank.csv): what does the evidence establish, what remains unknown, and who should take the next action?
4. Compare with the [separate authored key](AUTHORED-REVIEW.md) after recording your own answers.

Do not run changes against a production account from these examples. For an actual trial, have the agency and its IT provider agree the accounts, tools, test data, permissions, retention requirements, stop conditions and rollback first. A synthetic exercise does not establish safe handling of real client information.

## What this teaches

An observed failure to retrieve a new message is evidence about that tested request, identity and time. It does not establish that every other identity has lost access or that previous copies have been deleted. Similarly, a deletion request is different from evidence that deletion completed within its stated scope.

Keep sending permission separate from permission to read or create a draft. A successful draft does not establish authority to send it.

## Related resources and provenance

[Return to the practice collection](../../README.md).

Tyler Mayberry builds software through Cirlet and offers paid AI and automation help to independent insurance agencies. [The Agency AI Security Sprint](https://cirlet.com/security) describes a separately agreed, bounded service; this exercise is not a guarantee, certification, penetration test or emergency response service. The [agency permissions guide](https://insuranceagencyvirtualassistant.com/inbox-and-follow-ups#permissions-check) supplies related questions for an agency and its provider.

These materials were deliberately written with AI assistance. No model was run against this exercise, and no performance score, breach finding, customer outcome or vendor capability is established. Keep private data out of public repository issues. Existing repository rights and licensing statements remain unchanged.
