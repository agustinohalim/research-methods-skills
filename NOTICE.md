# Notice

Both skills in this repository are copied from K-Dense scientific-agent-skills:

- Source: https://github.com/K-Dense-AI/scientific-agent-skills
- Commit: 154988403bb5a18e9d3c0ce4e6d5e2e4b184a298 (1 October 2026)
- License: MIT, Copyright (c) 2025 K-Dense Inc. (see `LICENSE`)

| Skill | Upstream path | Upstream skill version | Library covered (its own license) |
|---|---|---|---|
| `neurokit2` | `skills/neurokit2/` | 1.4 | NeuroKit2 0.2.13 (MIT) |
| `aeon` | `skills/aeon/` | 1.3 | aeon 1.6.0 (BSD-3-Clause) |

## Local changes

- `neurokit2`: script commands rewritten from `python skills/neurokit2/scripts/...`
  (paths relative to the upstream repo root) to `python scripts/...`, with one line in
  `SKILL.md` stating that these paths are relative to the skill directory. Applies to
  `SKILL.md` and five files under `references/`.
- `aeon`: unchanged.

## Updating from upstream

Copy the two folders again from a newer upstream commit, reapply the path change above,
update the commit hash and versions in this file, and bump `version` in
`plugins/research-methods/.claude-plugin/plugin.json`.
