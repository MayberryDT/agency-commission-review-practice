# One batch: arithmetic practice

Use these eight fictional cases to practice calculating cost per **checked result**, then deciding when a calculation must stop. The figures are invented teaching inputs, not agency costs, measured savings, customer results or a model benchmark. This reference and its key were prepared with AI assistance.

## Try the inputs first

1. Open [the fictional inputs](inputs-fictional.csv). Use one currency throughout each case. A blank input is unknown; it is not zero.
2. For each case, decide whether all four inputs are usable. The checked-result count must be a positive whole number. Staff minutes, hourly staff cost and additional tool cost must be finite and non-negative. Leave unusable cases unresolved instead of inventing an answer.
3. For usable cases, calculate staff cost as `staff_minutes / 60 * hourly_staff_cost`. Add the additional tool cost to get batch cost. Divide the **unrounded** batch cost by the checked-result count. Display final amounts to two decimal places.
4. Compare your decisions with the [separate authored key](AUTHORED-KEY.md). You can also enter the same fictional figures in the [existing browser calculator](https://insuranceagencyvirtualassistant.com/cost#batch-cost-title).

Count preparation, attended running, review, corrections and filing in staff minutes. Count only results actually checked against your required standard. Keep setup and monthly upkeep separate: the calculator excludes them. The broader [whole-task worksheet](https://insuranceagencyvirtualassistant.com/cost#task-cost-worksheet) provides context for comparing methods.

## Use the calculator offline

Download [calculator.html](calculator.html), save it as an HTML file, and open it in a browser. GitHub's normal file view shows the source; it does not run the calculator. The downloaded file is self-contained and needs no server, installation, signup or model API. Start with the fictional inputs above; no client records are needed.

This is an AI-assisted adaptation of the existing browser calculator, not a separate measured model experiment. All four figures start blank; changing a figure clears the old result. It rejects missing values, negative or non-finite figures, and zero or fractional checked-result counts. Explicit zero cost is allowed. Without JavaScript, its inputs stay disabled and the visible formula remains available.

The file contains no network, storage or tracking calls. Following its optional source-guide link opens the commercial guide, where existing site analytics runs. Inputs are not sent by the calculator. Seventeen automated Chrome checks passed for the local-file version, including arithmetic, reset, keyboard, narrow layouts and no-JavaScript behavior; no physical-device or screen-reader test is claimed.

## Limits and affiliation

The arithmetic does not judge output quality, establish what work was completed, quote a service, prove savings or decide whether automation is worthwhile. Compare like-for-like checked results and keep estimates separate from observations. No currency conversion, tax treatment, accounting recommendation or licensed insurance advice is provided.

Tyler Mayberry builds software through Cirlet, which offers paid AI and automation help to independent insurance agencies. The linked guide is on a commercial service site. These are optional practice materials, not client records or a software integration. No open-source or data-reuse license is supplied. Keep private records out of public repositories and issues.
