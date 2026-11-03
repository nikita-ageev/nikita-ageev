# Credit Radar: source-backed market monitoring

## The decision

Retail lending conditions change across many pages and publications. The project turns collected public sources into a reviewable record of changes and a publication candidate.

## The implementation

The public repository describes a fixed workflow: collection → comparison with prior observations → fact extraction → code checks → model review → publication gate. The code checks include source-linked numbers, comparable snapshots and duplicate filtering. The repository also exposes regression checks and GitHub Actions results.

## Evidence to inspect

- [Public repository and architecture](https://github.com/nikita-ageev/credit-radar)
- [Checks in GitHub Actions](https://github.com/nikita-ageev/credit-radar/actions)
- [Published archive](https://ageev.dev/credit-radar/)

## What the project demonstrates

A model-assisted workflow can keep explicit state, trace its claims to source material and refuse a publication when a check fails. A passing CI run establishes that its checked cases passed; it does not prove live data completeness or uninterrupted operation. Provider availability, source changes and human review remain operational concerns.

This is a personal public-data project. No employer data or internal implementation is presented here. The public code and dated archive are the evidence; this case study does not claim a measured revenue benefit, exhaustive coverage or a production SLA.
