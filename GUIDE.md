# Reader's Guide — javascript (Airbnb JavaScript Style Guide)

## What this project is

This is the **Airbnb JavaScript Style Guide**: "a mostly reasonable approach
to JavaScript" and one of the most widely adopted coding-style references in
the ecosystem. It states Airbnb's rules for writing JavaScript — each rule
with good/bad code examples and the reasoning behind it — and ships the
official ESLint configs that enforce them automatically.

## How the content is organised

- [`README.md`](README.md) — **the main style guide** (this guide was written
  from its section outline and the repository tree). After the Table of
  Contents it works through the language rule by rule: Types, References,
  Objects, Arrays, Destructuring, Strings, Functions, Arrow Functions,
  Classes & Constructors, Modules, Iterators and Generators, Properties,
  Variables, Hoisting, Comparison Operators & Equality, Blocks, Control
  Statements, Comments, Whitespace, Commas, Semicolons, Type Casting &
  Coercion, Naming Conventions, Accessors, Events, jQuery, ECMAScript 5
  Compatibility, ECMAScript 6+ (ES 2015+) Styles, Standard Library, Testing
  and Performance — closing with Resources, translations and Contributors.
- `react/` — the **React style guide** (its own README): Airbnb's rules for
  React/JSX code.
- `css-in-javascript/` — the **CSS-in-JavaScript style guide** (its own
  README).
- `packages/` — the enforceable form of the guide: the published ESLint
  configs `eslint-config-airbnb` and `eslint-config-airbnb-base`.
- `linters/` — ready-made linter settings (`.eslintrc`, `.jshintrc`,
  SublimeLinter files) for older setups.

## How to use it

1. **Reading:** open the main README and jump via the Table of Contents to
   the construct you are unsure about; each section gives the rule, examples
   of what to do and avoid, and links to discussion.
2. **Enforcing:** install the config from `packages/` (`eslint-config-airbnb`
   for full, `-base` without React) in your project so the rules run in your
   editor and CI instead of living only in review comments.
3. **React or CSS-in-JS work:** switch to the corresponding sub-guide.

## About this standalone edition

This repository is a standalone edition of
[airbnb/javascript](https://github.com/airbnb/javascript), converted from a
fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Airbnb and the
upstream contributors; licence MIT (see `LICENSE.md`).
