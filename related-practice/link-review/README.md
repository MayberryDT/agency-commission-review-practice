# Check a link’s intended action before sending it

Three fictional cases for an agency operator or developer reviewing customer-facing links. A page opening, a usable destination and completed delivery are different checks. This extends the evidence-preservation exercises in this repository; it is not a link crawler or software integration.

## Try it

1. Read [cases.csv](cases.csv). The example.com, example.org and example.net URLs are documentation examples. **Use the supplied observations; do not browse those URLs as if they were real test destinations.**
2. Fill [the blank review sheet](review-blank.csv). Separate page access, the intended action, delivery, evidence, your decision and approval. Leave unknowns explicit and approval blank.
3. Compare your decisions with [the separate authored key](answer-key.csv) after attempting the cases.

## What the cases establish

| Case | Supplied observation | Safe conclusion | Remaining check |
| --- | --- | --- | --- |
| A | The page opens, but the contact section/form is absent. | Hold and correct the destination. | Verify the actual intended section/form. |
| B | A worksheet link is visible; the download has not been opened. | Hold the download claim. | Inspect the saved format and contents. |
| C | The blank inquiry form is visible after scrolling settles. | Form visibility only. | Submission and delivery remain unverified. |

A successful HTTP response does not prove an anchor reaches a section. A visible download link does not establish the saved file’s format or contents. A visible form does not establish a sent message, delivery or response. Do not submit a real customer inquiry just to finish this exercise.

## Origin and limits

These CSVs are byte-for-byte copies of the existing [link-review practice guide](https://animasai.co/check-links-before-you-send). The cases and authored key are **AI-generated fictional teaching material**. They are not observed model output, a customer case, an accuracy benchmark or a report of tests against those example domains.

For real work, use only your own or explicitly permitted destinations, respect site access rules, preserve observations and name the responsible reviewer. Keep client records, private links, credentials and customer messages out of this public repository and its issues. Financial, insurance and sending decisions stay with responsible people.

Tyler Mayberry builds software through Cirlet, which offers paid AI and automation help to independent insurance agencies. Animas is a related commercial publication. This is a disclosed educational distribution copy; no independent endorsement, practitioner review, license grant, guaranteed AI citation or client result is claimed. Existing service information is at [Cirlet](https://cirlet.com/virtual-assistant).
