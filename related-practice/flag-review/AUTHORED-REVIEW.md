# Separate authored review key

Try the [participant worksheet](README.md) before reading this key. All counts are fictional, prepared with AI assistance. This is an arithmetic reference, not a model evaluation or customer result.

| Reference review | Flagged | Not flagged | Total |
| --- | ---: | ---: | ---: |
| Actual error | 9 | 1 | 10 |
| Already correct | 20 | 970 | 990 |
| Total | 29 | 971 | 1,000 |

- **Error detection:** 9 / 10 = 90%. One of the ten known errors was missed.
- **Useful flags (precision):** 9 / 29 = about 31%. There are 29 flags to inspect, of which nine correspond to actual errors in the reference review.
- **Unnecessary flags:** 20 already-correct rows were flagged. Their review cost and consequences are unknown.
- **Missed errors:** one actual error was not flagged. Its severity is unknown.

Keep the reference review separate from the checker's proposals. Review unflagged rows against the independent reference too; inspecting only flagged rows cannot find misses. If only a sample is reviewed, retain its sampling method and do not report sample counts as the complete file's counts.

For another batch, error detection is undefined if there are no actual errors; precision is undefined if there are no flags. Count preparation, review and correction time separately before making any cost comparison. No savings, performance, accounting decision or payment is established here.
