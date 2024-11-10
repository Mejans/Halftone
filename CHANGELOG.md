# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- New loading overlay used in image preview
- Initial Bulgarian (bg) translation
- Initial Norwegian Bokmål (nb) translation
- Initial Hindi (hi) translation
- `pyproject.toml` file to hold project's metadata and pyright configuration
- `__builtins__.pyi` type stubs file to define gettext's `_` function to pyright
- Spell checking using `codespell` in CI

### Changed

- Replaced deprecated `Gtk.FileChooser` with `Gtk.FileDialog`
- Started using `top-bar-style` setting instead of deprecated `.flat` headerbar style class
- Updated Brazilian Portuguese (pt_BR) translation
- Updated Italian (it) translation

### Fixed

- Use `GLib.Error` instead of `GLib.GError`
- Globally set 294 as a height request for window (to be in par with GNOME HIG recommendations)
- Added German translation to `LINGUAS`

## [0.6.1] - 2024-04-04

### Added

- Primary brand colors information

### Changed

- Updated about window to use new `Adw.AboutDialog` view
- Switch to `appsteamcli` validation
- Updated metainfo in order to conform with AppStream 1.0 specification
- Changed project's summary to fit in 35 character requirement
- Prefer dark color scheme
- Updated translations (ru, tr, zh_CN)

## [0.6.0] - 2024-01-10

### Changed

- Implement UI suggestions from GNOME Circle application
- Add keyboard shortcuts for toggling sidebar and main menu
- Updated translations

### Fixed

- Release info formatting
- Desktop file categories

## [0.5.0] - 2023-12-10

### Added

- Bottom sheet, which shows at 640px threshold (mobile mode)
- New translations

### Fixed

- Main window not being able to resize width down to 360px
- Lack of image options retention

## [0.4.0] - 2023-11-11

### Added

- Success toast that shows after copying logs on error page
- New translations

### Changed

- Updated UI to take advantage of the new widgets included with libadwaita 1.4

### Fixed

- Issue with "Open in External Image Viewer" button not working on Flatpak builds

### Removed

- Preferences window

## [0.3.1] - 2023-06-30

### Added

- Option to change how image should be resized to fit inside preview box
- New translations

### Changed

- Now Halftone uses flat headerbar style

## [0.3.0] - 2023-06-09

### Added

- Brightness and contrast control
- Button for opening preview image in external image viewers
- Custom logging facility for easier issue reporting
- Logic code for `Copy Logs` button
- New translations

### Changed

- Moved image size option to Image Properties
- Preview images are now saved as a temporary file
- Use normal logo variant in drop page

## [0.2.0] - 2023-05-20

### Changed

- Rename project to Halftone

## [0.1.0] - 2023-05-16

### Changed

- Initial release of Pixely.
