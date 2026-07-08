# Contributing

Thanks for helping keep this dataset accurate!

## Reporting a wrong or missing deadline

[Open an issue](../../issues/new) with:

- the venue and year (e.g. `CSCW 2027`),
- what is wrong or missing,
- a link to the **official source** (call-for-papers page or organizer announcement).

## Pull requests

Edit `data/deadlines.json` (the CSV is derived from it). Requirements:

1. **Official source URL required** for every date — CfP page, organizer site, or organizer announcement. Third-party trackers are not sufficient sources on their own.
2. Dates are ISO 8601 with explicit offset; deadlines are Anywhere on Earth (`-12:00`, `"tz": "AoE"`) unless the CfP says otherwise.
3. If a date is not officially announced yet, set `"status": "estimated"`.

## Suggesting a new venue

Open an issue with the venue name and why it fits the scope (social computing / HCI / web science / computational social science). Venues with a substantial social computing track are in scope.

Accepted changes are folded into the canonical dataset that powers
[casp.jp/social-computing-deadlines](https://casp.jp/social-computing-deadlines/) and are mirrored back here by the daily sync.
