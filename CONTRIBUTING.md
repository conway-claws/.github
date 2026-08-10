# Contributing

Contributions are welcome across the org. Start with an issue on the relevant repository; small, well-sourced corrections are the most useful contribution these projects get.

## calendar-sync

- A wrong, missing, or stale event: open an issue with the event title, date, and the public source that shows the correct information. The calendar rebuilds daily from its sources, so a fix at the source usually propagates on its own.
- Label taxonomy and merge logic changes: open an issue first so the change can be discussed before a pull request.

## district-library

- Corrections to a record: open an issue citing the public source. Records state machine observations with dates, not characterizations; contributions are held to the same rule.
- No binaries, ever. Records hold pointers, provenance, and text extractions. Originals stay with the district.
- No credentials, ever. The automation runs with zero secrets by design; anonymous reachability is the public-records test. Pull requests that add a secret, a proxy, or an authenticated fetch path will be declined.
- Removal requests: use the repository's removal-request issue form, or email privacy@conwaypto.org.

## Pull requests

Keep them small and single-purpose, with the reasoning in the description. Anything that changes published output (the calendar feeds, the catalog) should say what the output looks like after the change.
