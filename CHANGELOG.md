# Changelog

All notable changes to the **Daily Tutor** skill will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2026-04-08
### Changed
- Removed redundant prompt constraints regarding the `/take` URL suffix, as the `quizbuild` MCP integration has been updated on the server side.

## [1.0.0] - 2026-04-08
### Added
- Created a robust folder structure (`scripts/`, `data/`, `references/`) optimized for OpenClaw Cloudhub.
- Added comprehensive documentation (`README.md`, `EXAMPLES.md`).
- Added support for the OpenClaw `quizbuild` MCP server to generate practice exams automatically.
- Enhanced configuration options via `config.json` (`subject_name`, `num_items`, `primary_key`).
- Added `.gitignore` to prevent syncing local study states to public registries.
