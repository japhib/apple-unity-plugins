# CHANGELOG
All notable changes to this project will be documented in this file.

## [1.0.5] - 2023-11-28
### Fixed
- Cleans up an issue with Unity 2022.1 and later in which Unity's Asset Database was unable to find frameworks or bundles.

## [1.0.4] - 2023-07-25
### Added
- API Availability checking
- Sample to highlight use of new API availability check feature.
- API Availability attributes to communicate API availability information to users and attach availability metadata to Apple Unity plug-in C# API

## [1.0.3] - 2022-12-16
### Changed
- Updated logging in AppleFrameworkUtility
- Updated AppleFrameworkUtility to search `/Libraries` along with `/Frameworks` for copied libraries

## [1.0.2] - 2022-11-29
### Changed
- Disabled bitcode generation in all native library project build targets.

## [1.0.1] - 2022-10-10
### Changed
- Updated package name to `com.apple.unityplugin.core`

## [1.0.0] - 2022-06-02
### Added
- Initial release.
