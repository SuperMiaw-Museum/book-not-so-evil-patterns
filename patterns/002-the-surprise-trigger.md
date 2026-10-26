# The surprise trigger

**Pattern 002 · Category: database**

**Created: 2026-10-22T17:05:21Z**

**Modified: 2026-10-26T10:21:15Z**

> *“Data doesn't need an origin story.”*

## Problem

A team needs to understand where a table's data comes from. The application has no obvious writer, yet new rows keep appearing.

## Solution

Put business logic inside database triggers, ideally across several tables. Let every insert or update create more data behind the scenes. Never reveal this in the application code.

## Benefits

- Keeps application services pleasantly small.
- Turns data lineage into an archaeological expedition.
- Encourages exciting cross-team debugging sessions.

## Success metric

The team spends longer finding the source of a row than building the feature that consumes it.

## The ultimate achievement

The missing data producer turns out to be a trigger written years ago. It has been working flawlessly the whole time.

---

[Book](../README.md) · [Contents](../SUMMARY.md) · [← Previous](001-the-website-itself.md) · [Next →](003-the-infinite-systems-engineering-analysis.md)
