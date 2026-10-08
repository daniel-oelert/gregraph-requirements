# Requirements repository

This directory is a GREGraph requirements repository (layout: spec §3).

## Layout

- `documents/` — requirements, designs, tests, and more (one folder per
  type; placement is organisational only)
- `changes/` — change requests (CRs) that record intent, decisions, and scope
- `glossary/` — knowledge-base terms with aliases
- `assets/` — attachments, one folder per owning document
- `.gregraph/` — `config.toml`, shared templates, and the rebuildable cache

Every document is a Markdown body plus a JSON sidecar (`<ID>.md` and
`<ID>.json`). Edit the Markdown; the tool maintains the sidecar.

## Commands

- `gregraph new <type> --title "…"` — create a document
- `gregraph list` / `gregraph show <ID>` — browse the repository
- `gregraph validate` — run every check
- `gregraph --help` — the full command set
