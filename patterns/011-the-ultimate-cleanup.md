# The ultimate cleanup

**Pattern 011 · Category: maintenance**

**Created: 2026-10-25T20:43:57Z**

> *“The cleanest code is no code at all.”*

## Problem

Your project has accumulated years of unnecessary files, outdated scripts, unused dependencies, and forgotten configurations. Some of them might still be useful, but investigating takes time.

## Solution

Delete everything that looks unnecessary.

Start with temporary files and obsolete scripts. Then remove redundant configurations, unused functions, and dependencies nobody remembers adding. Your repository becomes smaller with every commit. Clearly, you are making progress.

Some tests start failing. Remove them too. They were probably testing obsolete behavior anyway.

Eventually, the application stops working. Restoring deleted files would undo all your hard work.

Keep cleaning.

## Benefits

- Your repository becomes easier to navigate.
- Maintenance costs decrease with every deleted file.
- Fewer tests mean fewer failures.
- Your application has fewer dependencies than ever before.

## Success metric

Your repository contains fewer files than when the project started.

## The ultimate achievement

You have successfully removed every unnecessary file.

Including the ones your application needed.

---

[Book](../README.md) · [Contents](../SUMMARY.md) · [← Previous](010-the-perfectly-tuned-system.md) · [Next →](012-the-perfectly-shareable-project.md)
