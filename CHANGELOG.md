# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).
## [2.5.4] - 2024-08-21
### Added
 - Update README.md

## [2.5.3] - 2024-08-14
### Changed
 - Replace sed by gsed for macos users

### Fixed
 - Add gsed requirement for macos users

## [2.5.2] - 2024-07-02
### Changed
 - Update README.md

## [2.5.1] - 2023-06-28
### Fixed
 - Fix merge of older hotfix branches

## [2.5.0] - 2022-09-19
### Added
 - Configuration file & diff links on self runned instances

## [2.4.0] - 2022-08-10
### Added
 - Option --major/-m

### Changed
 - Update .gitignore

## [2.3.0] - 2022-01-21
### Changed
 - Link in README.md

### Fixed
 - Fix new 'git tag' command behaviour
 - bash version recognition on MacOS

## [2.2.0] - 2017-06-05

### Changed
 - Increment minor version when release is created #31
 
### Fixed
 - Initialization checks only local branches #73
 - `omgf pull` updates only local branches with remote branch #59

## [2.1.2] - 2017-04-10
### Fixed
 - Repair --help option #64

## [2.1.1] - 2017-04-07
### Fixed
 - Show links URL in man page #57

## [2.1.0] - 2017-04-03
### Added
 - Support for macOS #41
 - Check for requirements upon start, document requirements in README #30

### Changed
 - Improve README: add Setup and Alternatives, add OMGF's output and simplify installation instructions.
 - Use `env` instead of hardcoded path to Bash in shebang

### Fixed
 - Fix Unreleased URL generated for CHANGELOG

## [2.0.2] - 2017-03-11
### Fixed
 - Fix load user options to be case-sensitive #27
 - `make clean` and `make distclean` force removes files #28

## [2.0.1] - 2017-03-06
### Fixed
 - Fix `make dist`
 - Fix README.md Install section

## [2.0.0] - 2017-03-05

### Added
 - Add [EditorConfig](http://editorconfig.org/) file to enforce standard formatting

### Changed
 - Rename gf to omgf
 - Makefile uses BINDIR instead of EXEC_PREFIX

## [1.1.1] - 2017-01-30

## [1.1.0] - 2017-01-30
### Added
 - Automatic deployment into GitHub releases
 - `make distsingle` target compiles gf into a single file

## [1.0.1] - 2017-01-02
### Fixed
 - Proper changelog keywords listing

## [1.0.0] - 2016-12-22

[2.5.4]: https://github.com/kukenc/omgf/compare/v2.5.3...v2.5.4
[2.5.3]: https://github.com/kukenc/omgf/compare/v2.5.2...v2.5.3
[2.5.2]: https://github.com/kukenc/omgf/compare/v2.5.1...v2.5.2
[2.5.1]: https://github.com/kukenc/omgf/compare/v2.5.0...v2.5.1
[2.5.0]: https://github.com/kukenc/omgf/compare/v2.4.0...v2.5.0
[2.4.0]: https://github.com/kukenc/omgf/compare/v2.3.0..v2.4.0
[2.3.0]: https://github.com/kukenc/omgf/compare/v2.2.0...v2.3.0
[2.2.0]: https://github.com/InternetGuru/omgf/compare/v2.1.2...v2.2.0
[2.1.2]: https://github.com/InternetGuru/omgf/compare/v2.1.1...v2.1.2
[2.1.1]: https://github.com/InternetGuru/omgf/compare/v2.1.0...v2.1.1
[2.1.0]: https://github.com/InternetGuru/omgf/compare/v2.0.2...v2.1.0
[2.0.2]: https://github.com/InternetGuru/omgf/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/InternetGuru/omgf/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/InternetGuru/omgf.git/compare/v1.1.1...v2.0.0
[1.1.1]: https://github.com/InternetGuru/omgf/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/InternetGuru/omgf/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/InternetGuru/omgf/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/InternetGuru/gf/compare/v0.0.0...v1.0.0
