# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.0] - 2021-05-09
### Added
- Support dot notation in `bindEventListeners()`
- Add `upgrade()` all-in-one function


## [0.4.0] - 2021-04-16
### Added
- Module entry-point
- Terser for minification
- Dependency related single-imports
- Mark this package as side-effects free

### Changed
- It’s at least es9 support required
- Allow single imports


## [0.3.0] - 2020-06-23
### Added
- Adjust behaviour of `isElementInViewport()` with `amount` and `viewport` settings

### Changed
- Return created shadow root when calling `createShadowRoot()`
- Now `template` and `settings` arguments for `createShadowRoot()` are optional


## [0.2.0] - 2020-06-14
### Added
- Exporting all functions as object via default export
- New `bindEventListeners` function
- New `findReferences` function

### Fixed
- Providing settings for `createShadowRoot` would toss away defaults even if they would not be overwritten


## [0.1.0] - 2020-06-13
First silent release.

[Unreleased]: https://github.com/browserkids/dom/compare/0.5.0...HEAD
[0.5.0]: https://github.com/browserkids/dom/compare/0.4.0...0.5.0
[0.4.0]: https://github.com/browserkids/dom/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/browserkids/dom/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/browserkids/dom/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/browserkids/dom/releases/tag/0.1.0
