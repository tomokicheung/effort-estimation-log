# Effort Estimation Log

Effort estimation log for ICS 314 (Software Engineering I), UH Manoa, Fall 2026.

Each entry is a GitHub issue. The estimate is recorded when the issue is opened,
before the work starts. The actual time and reflection are added when it closes.

## Why issues instead of a text file

A text file has less friction per entry, which is normally the point. Here one
specific piece of friction is the whole value: an issue opened before the work
begins cannot have its estimate quietly revised afterward. The format enforces
the discipline the exercise is meant to build. An estimate written once you know
the answer is not an estimate.

Issues also timestamp themselves, support labels for filtering, and keep the
record searchable as it grows.

## Workflow

1. Read the assignment. Open a new issue from the template.
2. Fill in **Estimate** and **What is new here?** only. Nothing else yet.
3. Start the timer. Do the work.
4. Stop the timer. Complete the remaining fields and close the issue.

Track AI assistance as its own line item. Prompting and verification are
separate from implementation time, and mixing them hides where the effort
actually went.

Browse entries in the [Issues tab](../../issues?q=is%3Aissue). Closed issues are
completed entries; open ones are work in progress.

## Labels

Create these once under Issues > Labels.

| Label | Colour | Meaning |
|---|---|---|
| `estimation-log` | `#0e8a16` | Applied automatically by the template |
| `underestimated` | `#d93f0b` | Actual exceeded estimate by more than 15% |
| `accurate` | `#0e8a16` | Within 15% either way |
| `overestimated` | `#1d76db` | Finished more than 15% early |
| `new-concepts:0` | `#ededed` | Repetition of a shape already written |
| `new-concepts:1` | `#fbca04` | One genuinely unfamiliar idea |
| `new-concepts:2+` | `#b60205` | Two or more |

The `new-concepts` labels do the real work. Filtering by them shows whether the
count predicts overrun, which is the question this log exists to answer.

## Working hypothesis

Four entries in, estimates appear to hold when a task contains one unfamiliar
idea and to run roughly 60 to 90 percent over when it contains two. Four data
points is not enough to call that a pattern. Each new entry is a test of it.
