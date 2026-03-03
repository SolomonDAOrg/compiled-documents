# Compiled Documents

Human-facing compiled artefacts (PDF/DOCX) for members and counterparties.

This repo exists because most readers will not build packets locally.
It provides stable links to compiled outputs while preserving provenance
back to the canonical sources.

## What this repo (will) contains

- Compiled packets (usually PDF) for:
  - Company instruments (e.g., Company Agreement)
  - DAO proposals
  - SOPs
  - Other record sets as needed
- Per-record metadata (`*_META.yaml`) that anchors provenance and
  integrity.
- Optional per-record index (`*_IND-index.md`) when a record has multiple
  compiled variants.

## What this repo is not

- Not the canonical source of truth for adopted text.
- Not a place to edit instruments.
- Not a substitute for upstream pinning (tags/commits) in the source
  repositories.

## TODO

This repo is a work in progress.

## License / terms

Each compiled artefact inherits the licensing/terms of its upstream source
record and any applicable governance framework. Treat this repo as a
distribution mirror, not a relicensing vehicle.
