# Repository instructions

## Purpose and structure

This is the GitHub profile repository for `felipe-NR`. Its public content lives
in `README.md`, which contains a short biography, an open-source contribution
table, and project links.

The layout reference is
[`abhisheksharma2411/abhisheksharma2411`](https://github.com/abhisheksharma2411/abhisheksharma2411).
Adapt its structure using Felipe's verified work and preserve improvements in
link precision and presentation.

- `README.md`: public profile, written in English using Markdown and inline HTML.
- `AGENTS.md`: contains all project guidance, including instructions specific
  to Claude Code or other agents.
- `CLAUDE.md`: contains the bare `@AGENTS.md` import for Claude Code and an
  explanatory comment about the import and where project guidance belongs.

The repository contains no application source, package manifest, build tooling,
automated tests, or CI workflows. There are no install, build, lint, or test
commands to run for the current contents.

## Editing the profile

Keep public copy concise and in English, following the existing README style.
The contribution table uses HTML for grouped headers and cell alignment.
Preserve its header spans, column relationships, and total row when editing it.

Verify contribution counts, project stars, and pull request links against GitHub
before changing those values. Keep category counts and totals consistent with
the linked evidence. In Bug fixes and Features & docs, bold numbers represent
merged contributions and plain numbers represent open contributions. Keep these
states separate in category cells and totals. Reviews count unique PRs by other
authors across all states; exclude the user's own PRs.

Order upstream projects by descending star count. Keep exact counts linked to
their stargazer pages, sum the displayed stars in Total, and date the snapshot
when refreshing statistics.

A PR closed without merging may count as landed only when an upstream commit
confirms that its work was incorporated with attribution. Link to that commit,
explain the exception, and avoid counting the same work twice.

Support maintainer attribution and contribution examples with PR metadata or
upstream commits. Include working product links in My projects when available,
and distinguish contribution forks from original projects.

There is no statistics-generation script in this repository. Counts and links
are edited directly in `README.md`.

## Memory language

Write all ai-memory content for this project in English, including page titles,
bodies, and paths.

## Validation

Run `git diff --check` after edits and review the diff for the affected files.
For README changes, check Markdown and HTML structure, link destinations, table
column alignment, totals, and consistency with the legend. Use a rendered preview
when available to inspect layout; a local preview may differ from GitHub's
rendering.

For instruction changes, confirm that the bare `@AGENTS.md` import remains in
`CLAUDE.md` and resolves to this file.
