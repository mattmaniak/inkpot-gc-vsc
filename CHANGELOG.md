# Changelog

All notable changes to the Inkpot GC VSC extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.Y.Z] - UNRELEASED

## Added

- Border for Activity Bar Active Border.
- Border for Side Bar Title.
- Borders for Sticky Scrolls.
- Custom color for Buttons separators.
- Custom color for Dropdown Border.
- Custom color for Minimap Slider.
- Custom color for Odd Rows in a Table.
- Custom color for last line number when it's set to `dimmed`.
- Custom colors for Dropdowns.
- Custom colors for Preformatted Text.
- Custom colors for horizontal Activity Bar.
- Custom colors for files Tree rendering.

## Changed

- Color for Drag And Drop Border to a darker one.

## Fixed

- Missing opacity of overlapping colors.

## [1.5.1] - 2025-01-30

### Changed

- Keyword pink color to a little bit more pale as inspired by [GynColorsForSublime](https://github.com/pawlos/GynColorsForSublime/blob/master/gyncolors.sublime-color-scheme).

### Fixed

- Outdated colors on the screenshot.

## [1.5.0] - 2025-01-29

### Changed

- Keyword, preprocessor and punctation common color code to a brighter greenish blue found originally in [inkpot_gc.vim](https://github.com/gynvael/stream/blob/master/inne/inkpot_gc.vim).

### Fixed

- 1.4.4 typo in changelog.

## [1.4.4] - 2024-10-21

### Fixed

- Selection Highlight Background color as orange was overlapping a markdown text.

## [1.4.3] - 2024-06-30

### Fixed

- 1.4.2 release date in changelog.

## [1.4.2] - 2024-06-30

### Fixed

- Find Match Highlight Background that made some found code invisible when matched.

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
