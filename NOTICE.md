# NOTICE

This repository is a **personal fork** of [Everything Claude Code (ECC)](https://github.com/affaan-m/ECC), maintained by [@maheshsv](https://github.com/maheshsv) for personal use across Python / data, web / TypeScript, journalism, and general coding workflows.

## Upstream

- **Project:** Everything Claude Code (ECC)
- **Author:** [Affaan Mustafa](https://github.com/affaan-m) — original creator and maintainer
- **Upstream repo:** https://github.com/affaan-m/ECC
- **Forked from version:** 2.0.0-rc.1
- **Fork date:** 2026-05-27
- **License:** MIT (unchanged in this fork — see [`LICENSE`](LICENSE))

All credit for the design, agents, skills, hooks, rules, and overall system goes to the upstream project and its contributors.

## What's different in this fork

This is currently a **rebrand-only** copy. No functional changes have been made yet.

Top-level identity files updated:

- `README.md` — fork-notice banner prepended (upstream content preserved below)
- `AGENTS.md`, `CLAUDE.md` — fork-notice block prepended
- `package.json` — `name`, `repository`, `homepage`, `bugs` re-pointed to this fork; `contributors` adds maheshsv; original `author` (Affaan Mustafa) preserved
- `NOTICE.md` *(this file)* — added

**Unchanged from upstream:**

- `LICENSE` — original MIT text preserved verbatim
- All agents, skills, commands, rules, hooks, scripts, tests
- Plugin manifest and slash-command namespace (`ecc:`)
- Internal identifiers used by the install machinery

## Pulling upstream updates

```bash
git fetch upstream
git merge upstream/main          # or rebase, depending on your workflow
```

The `upstream` remote points at https://github.com/affaan-m/ECC.

## Reporting issues

- **Upstream bugs / general ECC issues:** file at https://github.com/affaan-m/ECC/issues
- **Fork-specific issues:** file at https://github.com/maheshsv/everything-claude-code/issues
