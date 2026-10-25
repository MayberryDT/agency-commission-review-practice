# Agency briefing review practice

A portable version of Cirlet's [existing daily-briefing exercise](https://github.com/MayberryDT/agency-commission-review-practice/tree/main/related-practice/daily-briefing). It supplies instructions, the same seven sample source notes and flawed draft, and a separate authored key. The names and records are invented. This is AI-assisted teaching material, not an agency application, inbox connection, captured model run or accuracy benchmark.

## Install in a practice project

Review [SKILL.md](SKILL.md) and its references before installing. The Skills CLI can install just this skill for Codex in the current project:

```sh
npx skills@1.7.4 add MayberryDT/agency-commission-review-practice --skill agency-briefing-review-practice --agent codex --copy
```

This installs files; it does not start an agent, connect to an agency system or send messages. Use a practice project. Do not add `--global` unless you intend a user-wide installation. Other agents have their own skill-loading requirements; they are not all tested here.

The Skills CLI sends installation telemetry by default. Its publisher documents an opt-out:

```sh
DISABLE_TELEMETRY=1 npx skills@1.7.4 add MayberryDT/agency-commission-review-practice --skill agency-briefing-review-practice --agent codex --copy
```

See [the CLI's documentation](https://github.com/vercel-labs/skills/blob/main/docs/troubleshooting.md#telemetry) for current collection details. An installation count is not a count of agency users or evidence of customer demand.

## Try it

Ask your agent: "Use agency-briefing-review-practice. Show me the sample briefing exercise and keep the review key closed until I submit my attempt."

Or ask it to attempt the review from the notes, then compare its actual answer with the separate key. The exercise's fixed date is October 26, 2026, at 8:30 a.m. America/Chicago. It does not use your current calendar.

Keep real client information out of this exercise, repository and public issues. The agent's response still needs a person's review. Installing the skill does not enforce a security or permission boundary.

## Source and reuse

Published by Cirlet with AI assistance. The [source exercise](https://github.com/MayberryDT/agency-commission-review-practice/tree/main/related-practice/daily-briefing) explains the public agency question that prompted it. This package changes the format, not the cases or authored review findings. The original exercise remains available without installing anything.

The collection's existing reuse scope applies: these are free practice resources, with no blanket open-source or data-reuse license. This package does not grant a new general redistribution license or vendor endorsement. [The collection](https://github.com/MayberryDT/agency-commission-review-practice) explains the separate optional agency help; it is not required to use the sample.
