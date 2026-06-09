# Take-Down-IMO AGENTS

## Read Order

1. `README.md`
2. `docs/agent/current-state.md`
3. `Math-training/docs/structure-guide.md`
4. `Changing Description.txt` only when historical context is needed
5. The target Typst entry file under `Math-training/entries/` or a
   `Math-training/utils/` module

## Scope

- Stay inside `Project/Take-Down-IMO/` unless explicitly asked to pull source
  material from `Project-source/Math/`.
- Treat `Math-training/` as the main work area.
- Treat `typst-skills/` as support material, not the default editing surface.

## Default Ignore Paths

- `Math-training/output/`
- generated PDFs and build artifacts
- `Math-training/assets/fonts/` unless the task is explicitly about typography
  or setup

## Preferred Plugins

- `Everything MCP` for file discovery
- `QMD` for local documentation and handoff docs
- `GitHub MCP` for repo history or remote review
- `Context7` when framework or tooling docs are needed

## Validation

Use the narrowest compile command that proves the change:

- `typst compile Math-training/entries/Note-to-EGMO.typ Math-training/output/Note-to-EGMO.pdf`
- `typst compile Math-training/entries/Note-to-MONT.typ Math-training/output/Note-to-MONT.pdf`
- task-specific compile commands for new entry files

## Structure Direction

- Keep `Math-training/` as the active authoring workspace.
- Keep document entrypoints in `Math-training/entries/`.
- Keep structure notes in `Math-training/docs/`.
- Keep local font assets in `Math-training/assets/fonts/`.
- Keep shared helpers in `Math-training/utils/`.
- Do not let `typst-skills/` drift into a parallel work area.
