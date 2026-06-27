# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository overview

This is a content-only repository — a curated list of Albanian-related open source projects. The primary artifact is `README.md`. There is no build system, CI, or test suite.

## Where to edit

- **`README.md`** — the canonical project list. Almost all contributions touch only this file.
- **`CONTRIBUTING.md`** — contributor workflow; do not change without maintainer approval.
- **`LICENSE.md`** — do not modify.

Avoid introducing build tooling, CI pipelines, or large restructuring without prior maintainer approval.

## Entry format

Each entry in `README.md` uses this exact structure (match the existing pattern under the appropriate `##` section heading):

```
#### Project Title
**Description:** 1–2 sentence description.
**Repository:** https://full-url-here
**Technology:** Language, Platform, Framework
**Status:** Active | Maintained | Published Dataset | etc.
**Maintainer:** Person or organization name
```

Fields are required. Use `####` (h4) for the project title. Place the entry under the most appropriate existing section rather than creating a new one.

## Branch and commit conventions

- Branch name: `add-project-name` (e.g., `add-albanian-nlp-library`)
- Commit message: `Add [Project Name] to [Section Name]`
- Stage only `README.md` unless another file genuinely needs updating.
- Keep PRs small and focused — one or a few related entries per PR.

## Validation before submitting

- Repository URL must use `https://` scheme.
- Do not alter other projects' existing entries unless correcting factual data (link rot, status change) — note the source in the PR description.
- Preserve the CC BY-SA 4.0 license header in `README.md` and do not change licensing text.
- If adding many projects at once, open an issue first to explain the scope.

## PR description checklist

1. Which section was updated
2. One-line summary of the project added
3. URL verification status (manually checked or automated)
4. Any license notes (if the project's license differs from repo norm)
