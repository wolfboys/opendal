# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)
and this project adheres to [Semantic Versioning](https://semver.org/).

## [v0.0.3] - 2022-02-16

### Added

- benches: Implement benches for ops (#26)

### Changed

- services/s3: Don't load_from_env if users already inputs (#23)
- readers: Improve seekable performance (#25)

## [v0.0.2] - 2022-02-15

### Added

- tests: Implement behavior tests (#13)
- services/s3: Add support for endpoints without scheme (#15)
- tests: Implement integration tests for s3 (#18)
- 
### Fixed

- services/s3: Allow set endpoint and region while input value is valid (#17)

## v0.0.1 - 2022-02-14

### Added

Hello, OpenDAL!

[v0.0.3]: https://github.com/datafuselabs/opendal/compare/v0.0.2...v0.0.3
[v0.0.2]: https://github.com/datafuselabs/opendal/compare/v0.0.1...v0.0.2