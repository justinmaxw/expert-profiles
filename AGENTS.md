# AGENTS.md

Catalog of loadable expert method profiles. See `README.md` for what this
repo is and how a profile gets loaded/invoked.

## Layout contract

- `_template/` — the reusable contract (`SKILL.md`, `sources.md`,
  `examples.md`). Keep it person-agnostic; new profiles copy it and fill it
  in, they don't reinvent its structure.
- `<profile-slug>/SKILL.md` — the cloned-brain skill file itself (Grok-skill
  frontmatter: `name`, `description` with trigger phrases and slash-command
  form).
- `<profile-slug>/sources.md` — the evidence file. Primary sources first;
  every non-obvious claim in `SKILL.md` should trace to a row here.
- `<profile-slug>/examples.md` — 5+ worked Q&A, including at least one
  question the profile should refuse or abstain on.
- `<profile-slug>/references/` — optional extracted material (timelines,
  framework cheat-sheets, short attributed quote cards). Never full
  copyrighted book chapters or video/podcast transcripts.

## Non-negotiables for every profile

- Unofficial / not-affiliated / not-endorsed, stated visibly in both
  `README.md`'s catalog table and the profile's own `SKILL.md` header.
- No invented quotes. If a claim can't be sourced, it's omitted, not
  hedged.
- The profile must have an explicit abstention rule and demonstrate it in
  `examples.md` — a profile that never says "the method doesn't reach" is
  a failed profile.

## Maintaining this file

Keep this file short and load-bearing: project-wide conventions that apply
to (almost) every future session, not task-specific detail. If something is
already documented in `README.md` or a profile's own files, link to it
instead of duplicating it. Prune entries that stop being true; don't let
this file grow chronologically.
