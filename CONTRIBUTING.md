# Contributing to OOTP27 NPB 2026

[한국어](./CONTRIBUTING.ko.md)

Thanks for helping improve the NPB 2026 quickstart for OOTP Baseball 27. This repository is the public release and feedback hub for the mod, so the most useful contributions are precise corrections, source links, and reproducible issue reports.

## What Helps Most

- Roster fixes: team assignment, active/retired status, uniform number, handedness, position, name spelling, date of birth, height/weight, nationality, and player IDs.
- Rating feedback: batting, pitching, fielding, pitch mix, velocity, no-record player fallback ratings, and obvious outliers.
- Contract data: salary, multi-year contract terms, options, and missing minimum-salary cases.
- Data sources: official NPB profile pages, club roster pages, Chadwick Register IDs, Baseball-Reference links, and other stable public references.
- Quickstart bugs: load failures, duplicate players, missing players, broken logos/uniforms/ballparks, or anything that makes a new save behave incorrectly.

## Before Opening an Issue

Please check the latest GitHub Release and report the release tag you tested. If the issue is about a player, include as many stable identifiers as possible:

- OOTP player ID, if visible in your export.
- NPB official player page or player register link.
- Team and roster status.
- Expected value and current in-game value.
- Screenshot or CSV row when it helps identify the exact player.

Name-only reports are still welcome, but IDs and source links make fixes much faster.

## Issue Titles

Use a short prefix when possible:

- `[Roster]`
- `[Ratings]`
- `[Contracts]`
- `[Uniforms]`
- `[FaceGen]`
- `[Ballparks]`
- `[Crash]`
- `[Credits]`

## Pull Requests

Small, focused pull requests are easiest to review. Good PRs usually do one of these:

- Fix documentation or credits.
- Add source links for known issues.
- Provide a small, source-backed data correction.
- Improve release notes or installation instructions.

Please do not upload copyrighted commercial game files, unrelated assets, or large generated files unless a maintainer asks for them. Quickstart release zips are published by the maintainer.

## Data Standards

Prefer stable IDs over name-only matching. When two sources conflict, official NPB pages and club pages should be treated as the first reference point, then Chadwick/Baseball-Reference style identifiers can be used to connect records across datasets.

For player names, use the spelling that best matches the OOTP roster unless a source-backed correction is needed.

## Beta Policy

This mod is currently distributed as a beta quickstart. Data fixes may be batched into the next beta release instead of being released one by one. Larger database or regeneration changes may need extra testing before they appear in a public release.

## Credits

Keep `CREDITS.md` accurate. If you submit or identify an asset that requires attribution, include the creator, source URL, and permission/license note.
