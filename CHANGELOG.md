# Changelog

All notable changes to this standalone edition of the Airbnb JavaScript style guide are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus npm updates for the root package and `packages/eslint-config-airbnb` and `packages/eslint-config-airbnb-base`.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the style-guide docs; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's Node test workflows and the repo's own `linters/.markdownlint.json` were kept as-is.
- No `.editorconfig` added — upstream already ships one (root, with per-package symlinks); kept unchanged.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [airbnb/javascript](https://github.com/airbnb/javascript) at upstream commit `8ed19247bef145e3cc41b24a02dd1fe6d9b5e681` (upstream HEAD dated 2026-02-21).
- Fork history severed; all files and the MIT licence (`LICENSE.md`) preserved as-is, including the 4 upstream symlinks in `packages/`.
