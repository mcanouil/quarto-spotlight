# Changelog

## Unreleased

### Documentation

- docs: Serve the extension's social card as the Open Graph image, so a shared link shows the card rather than the first image on the page. (#27)

## 1.2.2 (2026-08-02)

### Refactoring

- refactor: Target the Quarto Wizard v2 extension schema in `_schema.yml`.

## 1.2.1 (2026-08-01)

### Documentation

- docs: Add a documentation website under `docs/`, built on the `atelier` project type and published to <https://m.canouil.dev/quarto-revealjs-spotlight/>, including a deck to try the spotlight on.
- docs: Trim `README.md` to a landing page pointing at the website.
- docs: Add the Pages workflow, which renders `docs/` on pull requests and deploys it from the release tag.
- docs: Add the Quarto Extensions Updates workflow, scanning `docs` for the website's own dependencies.

No user-facing changes.

## 1.2.0 (2026-02-21)

### New Features

- feat: Add extension-provided code snippets (#15).
- feat: Add _schema.yml for configuration validation and IDE support (#12).

## 1.1.1 (2026-02-11)

### Bug Fixes

- fix: Update copyright year.

## 1.1.0 (2025-10-25)

### New Features

- feat: Enhance example.qmd with author details and subtitle.

### Documentation

- docs: Update installation section and add example output.

## 1.0.2 (2025-04-05)

### New Features

- feat: Add CITATION file for project citation.

### Bug Fixes

- fix: Switch to deploy from GitHub Actions (#6).

### Documentation

- docs: Update quarto command.

## 1.0.1 (2023-02-10)

### Bug Fixes

- fix: Add missing license.
- fix: Add URI to handle which does not autolink.

## 1.0.0 (2023-02-10)

### Bug Fixes

- fix(readme): License notice.

### Documentation

- docs(readme): Add github handle.

### Style

- style: Title case.
