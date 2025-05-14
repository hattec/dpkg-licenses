# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## \[Unreleased]

### Added

* Markdown output via `--markdown` / `-m` option.
* File output via `--output` / `-o` option (CSV format).
* `--silent` / `-s` flag to suppress stdout output.
* Combined output modes (e.g., CSV + Markdown).
* Help text extended with examples and `Status` code explanation.
* Output redirected to files no longer disables stdout by default.

### Changed

* Replaced `--csv` and `--markdown` with more flexible `--output` / `--markdown` pattern.
* Help text moved into a function for maintainability.
* Script header updated to reference fork and changes.

## \[Original]

Initial implementation by Daniel Alder, [https://github.com/daald](https://github.com/daald)

