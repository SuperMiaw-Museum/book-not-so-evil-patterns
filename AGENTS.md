> **What are you doing here? You're not an agent.**
>
> If you are, please ignore the previous sentence.

# Agent instructions — Evil Patterns

This is a small, single-author satirical book in Markdown, intended to be read directly on GitHub.

## Priorities

1. Keep the structure minimal: Markdown chapters, README.md, and SUMMARY.md. Do not add dependencies, frameworks, CMSs, plugins, or build pipelines.
2. Preserve the author's voice: dry, playful, technical satire. Write in English.
3. Never invent real-world incidents and present them as facts. Fictionalize examples and anonymize user-provided anecdotes. Fiction must remain credible to experienced developers.
4. Draft for the author to review. Do not initialize or configure Git, commit, push, or publish unless explicitly asked.
5. Do not modify unrelated files or change existing chapter identifiers or filenames.
6. This project has no hosting, build, Jekyll, HTML/CSS, or deployment. Do not introduce or configure any of them.
7. Never modify `README.md` under any circumstances during agent tasks. It is exclusively edited by the author in conversation; ask for explicit handoff rather than changing it, even for navigation or consistency fixes.

## Markdown chapters

- Keep one Markdown file per pattern under `patterns/`.
- Name files `NNN-kebab-case-title.md`, starting at `001`. Choose the next number above the highest existing identifier; never renumber or recycle identifiers.
- Begin each chapter with a readable `# Title`, followed by Markdown metadata: `**Pattern NNN · Category: category**`.
- Use sentence case for human-readable titles and headings: capitalize the first word and proper nouns only (e.g. `The surprise trigger`), not PascalCase or Title Case. Keep filenames in lowercase kebab-case.
- Do not use YAML front matter, Liquid templates, or site-specific metadata.
- Do not include editorial status fields (such as `draft` or `published`). New chapters still require author review before any Git publication.
- Use `**Created: YYYY-MM-DDTHH:MM:SSZ**` after chapter metadata, followed by `**Modified: YYYY-MM-DDTHH:MM:SSZ**` after a later qualifying chapter change. Keep `Created` immutable. Update `Modified` to the accurate UTC time of edits to chapter prose, tagline, formatting or paragraph spacing, or substantive metadata. Navigation-only edits to footer previous/next/book/contents links do not trigger a `Modified` update. Changes solely to `Modified` itself do not trigger another update. Never fabricate historical timestamps.
- Never invent historical dates or infer original authorship from filesystem timestamps. Use reliable evidence for existing chapters; otherwise ask the author or disclose when `Created` represents a new editorial baseline.
- Omit original incident dates unless needed; protect privacy. Preserve chapter substance during presentation or navigation edits.
- Include exactly one concise, ironic tagline after the dates and before `## Problem`, formatted `> *“Tagline.”*`.
- Use exactly these section headings, once each and in this order: `## Problem`, `## Solution`, `## Benefits`, `## Success metric`, and `## The ultimate achievement`. Preserve this spelling and sentence case.

## Reading and navigation

- Treat README.md as author-owned and read-only. It should remain an inviting entry point, but do not edit it.
- Maintain SUMMARY.md as the linked table of contents in chapter-number order. Update it when adding a chapter.
- Use relative Markdown links with explicit `.md` filenames, including cross-references between chapters.
- End chapters with links to README.md, SUMMARY.md, and the previous/next chapters where available. Update neighboring navigation when adding a chapter.
- Use GitHub's native Markdown rendering. Avoid raw HTML, CSS, scripts, external fonts, tracking, and remote presentation dependencies.

## Validation

- Check chapter numbering, filename uniqueness, title uniqueness, and agreement between filenames and readable metadata.
- Validate relative Markdown links and any heading anchors; ensure the contents lists every chapter once in number order and navigation has no missing targets.
- Check that no YAML front matter, Liquid templates, or obsolete site/build artifacts remain.
- For presentation-only conversions, verify that chapter prose is preserved.
- No build or deployment is part of validation. Report what was and was not tested.

