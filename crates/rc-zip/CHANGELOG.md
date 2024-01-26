# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.0](https://github.com/fasterthanlime/rc-zip/compare/rc-zip-v2.0.1...rc-zip-v3.0.0) - 2024-01-26

### Fixed
- Read 64-bit extra fields compressed/uncompressed sizes properly

### Other
- Add link to Deflate64
- Add Deflate64 method + test file (doesn't support it yet)
- Use num-enum crate
- Use cargo-hack --feature-powerset
- Switch to flate2 (with oxide backend)
- Add tracing-subscriber to jean, add more tracing around eocdr parsing
- Upgrade appnote
- Check docs in CI, deny warnings
- Refactor StoredEntry a little bit
- [**breaking**] Bump major version because we broke the API
- Fix clippy lints
- Merge branch 'main' into main
- Upgrade minor version dependencies
- Upgrade dependencies
- Don't use deprecated chrono method
