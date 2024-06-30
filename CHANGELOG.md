# Changelog

All notable changes to the Inkpot GC VSC extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.2] - 2024-07-??

### Fixed

- Find Match Highlight Background and Border colors that made some found code invisible.

## [1.4.1] - 2024-06-26

### Fixed

- Regular Expressions color.

## [1.4.0] - 2024-06-20

### Added

- Custom Gallery Banner color for Visual Studio Marketplace.

## [1.3.0] - 2024-06-20

### Added

- Diff colors for Edtitor Gutter (line numbers) when comparing changes.

### Changed

- Input placeholder color to the same as the input's text. Like in the original Dark Modern theme.
- Status Bar Debugging Background to green-blue instead of a warning-like orange.

### Fixed

- Lack of contrast of markup text in "diff added" sections of a code due to the almost same colors used. It is done via implementing half-transparent color for a changed text.

## [1.2.0] - 2024-06-05

### Added

- A Marketplace icon.

### Fixed

- Non-contrasting focus border to much brighter one.

## [1.1.3] - 2024-06-05

### Added

- A license type in `package.json`.

### Fixed

- Keywords limitation to 5 in `package.json` as mentioned in the Extension Manifest's docs.

## [1.1.2] - 2024-06-05

### Changed

- `launch.json` version restored to `0.2.0` as it was accidentally matched with the theme version before.

## [1.1.1] - 2024-06-05

### Fixed

- Old screenshot to a new one.

## [1.1.0] - 2024-06-05

### Added

- A screenshot.
- Meta for Marketplace: homepage, issues page, keywords.

### Changed

- Error and warning colors for Side Bar list.
- Selection background color as the previous one was the same as regular background.
- Status Bar color for no opened folder.

### Removed

- Status Bar border when a folder is opened.

## [1.0.0] - 2024-06-04

- Created an initial release.
