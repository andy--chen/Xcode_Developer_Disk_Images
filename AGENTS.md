# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **static asset repository** containing Apple iOS Developer Disk Images (`.dmg` and `.dmg.signature` files). It has **no source code, no build system, no tests, no dependencies, and no runnable application**.

### Repository structure

- `Developer Disk Image/` — 47 subdirectories (iOS versions 4.2 through 15.0), each containing `DeveloperDiskImage.dmg` and `DeveloperDiskImage.dmg.signature`
- `README.md` — Documents purpose and download links
- `LICENSE` — MIT License

### Development notes

- There is nothing to build, lint, test, or run. No package manager, no CI/CD pipeline, no scripts.
- Changes to this repository are limited to adding/removing disk image files or updating documentation.
- To validate repository integrity, check that every version directory under `Developer Disk Image/` contains both a `DeveloperDiskImage.dmg` and a `DeveloperDiskImage.dmg.signature` file.
