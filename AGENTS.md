# Repository instructions

## Purpose and structure

This is the GitHub profile repository for `felipe-NR`. Its public content lives
in `README.md`, which contains a short biography, an open-source contribution
table, and project links.

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
the linked evidence. The table legend uses bold numbers for merged contributions
and plain numbers for contributions that are open or under review; preserve that
meaning or update the legend together with any change in presentation.

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
