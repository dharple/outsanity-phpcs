# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Namespace rules.

## [0.4.0] - 2020-02-02
### Added
- Comment formatting rules.
- A script for dumping rulesets.

## [0.3.0] - 2020-01-31
### Changed
- Project is now `outsanity/phpcs` instead of `dharple/outsanity-phpcs`

### Fixed
- Properties weren't being checked for indentation.  Enabled the sniff property
  "exact" on Generic.WhiteSpace.ScopeIndent, which seemed to fix it.

## [0.2.1] - 2020-01-15
### Fixed
- Switched from 0.0.0 to v0.0.0 tags.

## [0.2.0] - 2020-01-14
### Added
- Rules around double quotes and spacing.
- Rules for sorting method and property names.

### Changed
- Moved ruleset.xml into Outsanity/ per the [phpcs coding standard].

### Fixed
- License identifier in composer.json

## [0.1.0] - 2020-01-14
### Added
- PSR-12
  - Enforce short array syntax
  - Extend line length
- Sanity checks

[Unreleased]: https://github.com/dharple/outsanity-phpcs/compare/v0.4.0...main
[0.4.0]: https://github.com/dharple/outsanity-phpcs/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/dharple/outsanity-phpcs/compare/v0.2.1...v0.3.0
[0.2.1]: https://github.com/dharple/outsanity-phpcs/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/dharple/outsanity-phpcs/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/dharple/outsanity-phpcs/releases/tag/v0.1.0

[phpcs coding standard]: https://github.com/squizlabs/PHP_CodeSniffer/wiki/Coding-Standard-Tutorial
