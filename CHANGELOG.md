# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.3.3] - 2015-06-30
### Fixed
- `grunt run --record` now works correctly when entering an empty value for a custom input field which has a dependency on another input.

## [1.3.2] - 2015-05-20
### Fixed
- `grunt run --single` now works correctly, and for dynamic inputs.

## [1.3.1] - 2015-05-19
### Fixed
- Ensure that method config always defines a run script.

## [1.3.0] - 2015-05-18
### Added
- Support dependant input fields - field config which depends upon the values of parent fields.
- Validation helper methods.

## [1.2.3] - 2015-05-14
### Added
- Input fields used when recording are now displayed when running in replay mode.

## [1.2.2] - 2015-05-13
### Fixed
- User profile should be `user_profile` instead of `profile`.

## [1.2.1] - 2015-05-12
### Fixed
- Fix issue with recording a test method run with empty inputs.

## [1.2.0] - 2015-05-12
### Added
- Support for webhook triggers.

## [1.1.2] - 2015-05-07
### Fixed
- Fixed a bug in displaying nested outputs.

## [1.1.1] - 2015-05-06
### Fixed
- Fixed a bug which occurred when `grunt run` is called on a method with a custom input script, but no regular input fields.

## [1.1.0] - 2015-05-06
### Changed
- Input field collection from `grunt run` now consolidates regular and custom input fields into a single list.
- The order of the outputs in the `LABELLED` section after `grunt run`ing a task now match the order that the outputs are defined in the service config.
- All keys defined in the service's output config are now displayed in the `LABELLED` section.
- `grunt run` no longer aborts when an error occurs when running a script. This allows errors to be tested using `grunt run --replay`.

### Fixed
- If no OAuth details are provided in the `.env` file, running `grunt auth` displays the correct env var keys, instead of `TRELLO_ID` and `TRELLO_SECRET`.

## 1.0.0 - 2015-04-23
### Added
- Initial release of the SDK.

[1.3.3]: https://github.com/flowxo/flowxo-sdk/compare/v1.3.2...v1.3.3
[1.3.2]: https://github.com/flowxo/flowxo-sdk/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/flowxo/flowxo-sdk/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/flowxo/flowxo-sdk/compare/v1.2.3...v1.3.0
[1.2.3]: https://github.com/flowxo/flowxo-sdk/compare/v1.2.2...v1.2.3
[1.2.2]: https://github.com/flowxo/flowxo-sdk/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/flowxo/flowxo-sdk/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/flowxo/flowxo-sdk/compare/v1.1.2...v1.2.0
[1.1.2]: https://github.com/flowxo/flowxo-sdk/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/flowxo/flowxo-sdk/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/flowxo/flowxo-sdk/compare/v1.0.0...v1.1.0
