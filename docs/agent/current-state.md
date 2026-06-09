# Current State

## Objective

Stabilize Take-Down-IMO as a clear Typst authoring repository with explicit
agent entrypoints and low confusion between authoring files and support
material.

## Current Structure

- `Math-training/entries/Note-to-EGMO.typ` is the current style baseline.
- `Math-training/entries/Note-to-MONT.typ` is the active working document.
- `Math-training/docs/structure-guide.md` is the deeper authoring layout guide.
- `Math-training/assets/fonts/` holds local font assets.
- `Math-training/utils/` holds shared Typst logic.
- `typst-skills/` remains a support bundle.

## Current Decisions

- Keep the current structure stable during this governance pass.
- Keep source entry files, docs, assets, output, and shared utils distinct.
- Keep generated output in `Math-training/output/`.

## Next Likely Improvements

- Revisit a `books/`-style structure only when there are more active entry
  documents than the current `entries/` layout can comfortably hold.
- Keep `Changing Description.txt` as historical record, not the main agent
  handoff.
