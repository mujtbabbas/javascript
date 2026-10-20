# Enhancements — Standalone Edition Changelog

Upstream: https://github.com/airbnb/javascript
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)
- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, and credit.
- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus npm
  updates for the root package and packages/eslint-config-airbnb and
  packages/eslint-config-airbnb-base).
- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation for the style-guide docs; upstream Node test
  workflows and the repo's own linters/.markdownlint.json kept as-is).
- No .editorconfig added — upstream already ships one (root, with per-package
  symlinks); kept unchanged.

## v1.0.0 — Baseline (2026-10-20)
- Clean standalone baseline of airbnb/javascript at upstream commit
  8ed19247bef145e3cc41b24a02dd1fe6d9b5e681 (upstream HEAD dated 2026-02-21).
- Fork history severed; all files and the MIT licence (LICENSE.md) preserved
  as-is, including the 4 upstream symlinks in packages/ (per-package
  .editorconfig and .npmrc pointing at the root files).
