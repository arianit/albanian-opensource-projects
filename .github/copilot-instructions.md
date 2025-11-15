## Purpose

This repository is a curated collection of Albanian-related open source projects. These instructions are written to help AI coding agents make small, safe, and consistent edits—primarily to the top-level `README.md`—and to surface project-specific conventions.

## Where to edit

- Primary source-of-truth: `README.md` at the repository root. Most contributions are single-entry additions to categorized sections (e.g., "Language & Linguistics", "Web & Mobile Applications").
- Contributor guidance and exact git/PR steps live in `CONTRIBUTING.md`. Respect that flow.

## Entry format (follow exactly)

When adding a project, follow the pattern already used in `README.md`. Required fields shown below are taken from existing entries:

- Title (one line)
- Description (1–2 sentences)
- Repository: full HTTPS URL
- Technology: list of primary languages / platforms
- Status: e.g., Active, Maintained, Published Dataset
- Maintainer: person or organization

Example (use this structure when adding):

### Albanian NLP Library

**Description:** A comprehensive library designed to enable NLP tasks in Albanian, including tokenization and stemming.
**Repository:** https://github.com/arditdine/albanian-nlp
**Technology:** Python, NLP
**Status:** Active
**Maintainer:** Ardit Dine

## Commit & branch conventions

- Use the branch naming suggested in `README.md` and `CONTRIBUTING.md`, e.g. `add-project-name`.
- Commit message template (copy from `README.md`):

  Add [Project Name] to [Section Name]

- Make a small, focused PR that only updates `README.md` unless the change requires touching another file (rare).

## Validation checks the agent should perform

- Preserve the repository license header and do not change `LICENSE.md` or licensing text in `README.md`.
- Ensure the repository URL uses `https://` and is reachable (do a quick HEAD request if network access is available; otherwise preserve format and note link-check in PR description).
- Keep the section grouping consistent (add to the most appropriate existing section rather than creating new sections).

## Files to reference

- `README.md` — canonical project list and examples (see multiple entries under each section).
- `CONTRIBUTING.md` — contributor workflow and exact git commands.
- `LICENSE.md` — repository license (do not modify).

## What NOT to change

- Do not alter other projects' entries unless you are updating factual data (link, status) and can cite a source. In that case, include an explicit note in the PR description.
- Avoid introducing CI, build tooling, or large restructuring in this repository without prior maintainer approval—this repo is content/markdown centric.

## When to open an issue first

- If adding many projects in one PR, open an issue first to explain the scope.
- If you are unsure which section is best, open an issue and tag maintainers.

## Short checklist to include in the PR description

1. Which section was updated
2. One-line summary of the project added
3. Source/URL verification status (manually-checked or automated)
4. Any licenses to note (if different from repo)

---

If anything here is unclear or you want the instructions expanded (e.g., link-checking rules, ordering rules), say which part and I will iterate.
