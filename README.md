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

## Compiled Documents Index

See [`INDEX.md`](INDEX.md) for an index of the current list of compiled documents
available.

## Note on the Company Agreement record set

The `company-agreement/` folder contains the clean compiled reading copy of the
Company Agreement together with the Republic of the Marshall Islands filed,
stamped, certified, and related return documents for that same record set.

The clean compiled reading copy should be retained alongside, and not replaced
by, the Marshall Islands return documents. Where multiple official variants or
related filing artefacts exist for the Company Agreement, the folder-level
per-record index should be treated as the primary entry point.

## TODO

This repo is a work in progress.

## License / terms

Each compiled artefact inherits the licensing/terms of its upstream source
record and any applicable governance framework. Treat this repo as a
distribution mirror, not a relicensing vehicle.
