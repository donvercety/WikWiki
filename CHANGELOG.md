# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed
- Prevent long code tags from overflowing its line box.

## [1.0.1] - 2022-02-06

### Added
- [Favicon](https://en.wikipedia.org/wiki/Favicon)
- Blockquote element style.

### Changed
- Default tab size set to 4.

### Fixed
- Textarea tag breaking the edit page ([issue](https://github.com/donvercety/WikWiki/issues/7))
- Prevent images & tables going out of the border.
- Wrong padding on first line in code blocks.

## [1.0.0] - 2022-01-17
### Added
- Support for modern PHP v7.x ([issue](https://github.com/donvercety/WikWiki/issues/1))
- Made responsive ([issue](https://github.com/donvercety/WikWiki/issues/4))
- Style improvements
- New settings for `DATE_FORMAT` & `READ_ONLY`

### Changed
- Update Texy! to [v.2.3](https://github.com/dg/texy/releases/tag/v2.3)

### Fixed
- PHP Magic Quotes situation
- Texy! deprecation warnings
