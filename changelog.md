# Changelog

All notable changes to this project  be documented in this file.

## [Unreleased]

### Added

- nothing so far

### Fixed

- nothing so far

### Changed

- nothing so far

## [1.0.8] - 2022-08-24

### Fixed

- Support check failures not blowing up if called outside of a test.
  - should also fix [85](https://github.com/okken/pytest-check/issues/85)

### Changed

- changelog.md format. :)
- tox.ini cleanup
- refactoring tests to use examples directory instead of embedding example tests in test code.
  - this is easier to understand and debug issues.
  - also provides extra documentation through examples directory

## [1.0.7] - 2022-08-21

### Fixed

- Handle cases when context is None

## [1.0.6] - 2022-08-19

### Changed

- Update pyproject.toml to use newer flit
- Changed plugin name from pytest_check to pytest-check.


## [1.0.5] - 2022-03-29

### Added

- Add `raises`

## [1.0.4] - 2021-09-12

### Changed

- Require Python >= 3.6
- Remove old Manifest.in file.

## [1.0.3] - 2021-09-12

### Fixed

- Fix #64, modifications to maxfail behavior.

## [1.0.2] - 2021-08-12

### Added

- Add `excinfo` to call object in `pytest_runtest_makereport()`.
  - Intended to help with some report systems.

## [1.0.1] - 2020-12-27

### Changed

- Remove Beta Classifier
- Status is now "Development Status :: 5 - Production/Stable"

## [1.0.0] - 2020-12-27

### Changed

- Jump to 1.0 version, API is fairly stable.

## [0.4.1] - 2020-12-27

### Fixed

- Fix #43/#44 tests with failing checks and failing asserts now report all issues.

## [0.4.0] - 2020-12-14

### Added

- added `is_()` and `is_not()`

### Changed

- Requires pytest 6.0 or above. (Removed some cruft to support pytest 5.x)