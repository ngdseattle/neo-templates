# Neo Smart Contract Templates Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

This project uses [NerdBank.GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning)
to manage version numbers. This tool automatically sets the Semantic Versioning Patch
value based on the [Git height](https://github.com/AArnott/Nerdbank.GitVersioning#what-is-git-height)
of the commit that generated the build. As such, released versions of this extension
will not have contiguous patch numbers. Initial major and minor releases will be documented
in this file without a patch number. Patch version will be included for bug fix releases, but
may not exactly match a publicly released version.

## [1.1] - Unreleased

### Added

- Added contract metadata attributes

### Changed

- Templates updated to depend on Neo.SmartContract.Framework v2.10.0
- Run NEON as part of build target instead of publish target.
  - Note, neon output is copied to publish directory for backwards compatibility.

### Removed

- `--enable-debug-enhancements` option. Templates only work with official NEON tool now.

## [1.0.7] - 2019-11-08

### Changed

- updated Neo branding as per https://neo.org/presskit

## [1.0] - 2019-09-13

Initial Release
