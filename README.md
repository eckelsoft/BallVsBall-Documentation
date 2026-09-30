# BallVsBall Documentation

Private working documentation for BallVsBall's ball catalog, artwork references, abilities, and balance snapshots.

## Source of truth

The current UEFN project is authoritative for implemented behavior and live balance. This repository records reviewed documentation snapshots for design, communication, and asset reference. Update a ball entry only after checking its current implementation; record the project revision or review date. Do not treat an outdated page as gameplay truth.

## Ball catalog

See [`docs/ball-catalog.md`](docs/ball-catalog.md). The catalog starts as a verified-documentation structure; entries should be populated from current project data rather than inferred from screenshots or names.

## Adding a ball entry

Use [`docs/ball-entry-template.md`](docs/ball-entry-template.md). Store approved images under `assets/balls/`, use descriptive filenames, and link each image from its entry. Record whether an image is a gameplay render, icon, or concept image. Avoid committing Fortnite project exports or source assets unless they are explicitly needed and cleared for this repository.

## Change discipline

- Keep each balance snapshot dated and linked to its verification source.
- Separate verified values from design proposals.
- Include units, timing, conditions, and stacking rules for values that need them.
- Summarize meaningful changes in the commit message.
