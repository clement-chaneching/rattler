# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.21.0](https://github.com/baszalmstra/rattler/compare/rattler-v0.20.1...rattler-v0.21.0) - 2024-04-05

### Fixed
- replace long shebangs with `/usr/bin/env` ([#594](https://github.com/baszalmstra/rattler/pull/594))
- run post-link scripts ([#574](https://github.com/baszalmstra/rattler/pull/574))

## [0.20.1](https://github.com/mamba-org/rattler/compare/rattler-v0.20.0...rattler-v0.20.1) - 2024-04-02

### Fixed
- copy windows dll without replacements ([#590](https://github.com/mamba-org/rattler/pull/590))

## [0.20.0](https://github.com/mamba-org/rattler/compare/rattler-v0.19.6...rattler-v0.20.0) - 2024-04-02

### Fixed
- do not do cstring replacement on windows ([#589](https://github.com/mamba-org/rattler/pull/589))

## [0.19.6](https://github.com/mamba-org/rattler/compare/rattler-v0.19.5...rattler-v0.19.6) - 2024-03-30

### Other
- remove unused dependencies ([#585](https://github.com/mamba-org/rattler/pull/585))

## [0.19.5](https://github.com/mamba-org/rattler/compare/rattler-v0.19.4...rattler-v0.19.5) - 2024-03-21

### Fixed
- typo ([#576](https://github.com/mamba-org/rattler/pull/576))

## [0.19.4](https://github.com/mamba-org/rattler/compare/rattler-v0.19.3...rattler-v0.19.4) - 2024-03-19

### Fixed
- multi-prefix replacement in binary files ([#570](https://github.com/mamba-org/rattler/pull/570))

## [0.19.3](https://github.com/mamba-org/rattler/compare/rattler-v0.19.2...rattler-v0.19.3) - 2024-03-14

### Added
- add mirror handling and OCI mirror type ([#553](https://github.com/mamba-org/rattler/pull/553))

### Other
- add pixi badge ([#563](https://github.com/mamba-org/rattler/pull/563))

## [0.19.2](https://github.com/mamba-org/rattler/compare/rattler-v0.19.1...rattler-v0.19.2) - 2024-03-08

### Other
- update Cargo.toml dependencies

## [0.19.1](https://github.com/mamba-org/rattler/compare/rattler-v0.19.0...rattler-v0.19.1) - 2024-03-06

### Added
- generalised CLI authentication ([#537](https://github.com/mamba-org/rattler/pull/537))

### Fixed
- removal of multiple packages that clobber each other ([#556](https://github.com/mamba-org/rattler/pull/556))
- dont use workspace dependencies for local crates ([#546](https://github.com/mamba-org/rattler/pull/546))

### Other
- every crate should have its own version ([#557](https://github.com/mamba-org/rattler/pull/557))

## [0.19.0](https://github.com/baszalmstra/rattler/compare/rattler-v0.18.0...rattler-v0.19.0) - 2024-02-26

