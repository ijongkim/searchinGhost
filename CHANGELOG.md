# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
(empty)

## [1.3.2] - 2020-05-26
### Fixed
- Enable library import using yarn/NPM.

## [1.3.1] - 2020-05-23
### Added
- Ability to set `inputId` to `false` when no input field is needed.

## [1.3.0] - 2020-05-23
### Added
- Search engine configuration exposed to user.
- Non-latin languages support.

### Changed
- Remove the Ghost API library dependency, use the native `fetch()` instead. The bundle size is reduced by 50%.


## [1.2.0] - 2020-05-14
### Added
- Self documented methods within the source code (JSdoc).

### Changed
- The inner `loadResources()` method has been renamed to `loadData()`.
- Refactor some method and variable names to give them more sens.

### Fixed
- When `searchOn` set to `none`, properly disable form submission.


## [1.1.0] - 2020-05-10
### Added
- Discard post item when returning falsy value from the `customProcessing()` callback function.

### Changed
- Default format date based on the HTML page `lang` attribute.


## [1.0.0] - 2020-05-08

The first official and production-ready release of SearchinGhost!
