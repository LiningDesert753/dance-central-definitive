# Changelog

All notable changes to this project are documented here.

## [v0.0.7] - 2026-06-29

### Fixed

- Fixed a bug when the game crashed on entering character selection panel on debug version.
- Minor building fixes.

## [v0.0.6] - 2026-06-27

### Added

- Preferences options including:
  - changing menu music (Dance Central 1, 2 or 3)
  - ability to skip intro and auto-save warning ("flimflam" is still played)
- Added DC2 styled ribbon

## [v0.0.5 (Commit 5c75e53)] - 2026-05-18

### Changed

- The "Toggle Post-Processing" option was moved from Gameplay Modifiers to the main Definitive Options screen

### Fixed

- Gameplay Modifiers no longer crash the game when trying to select the option.
- Backing out of certain menus within Gameplay Modifiers no longer takes players to the incorrect location

### Issues

- All of the Spectator settings cycle in order instead of doing their intended tasks

## [v0.0.5 (Commit 06da7a)] - 2026-05-18

### Added

- Spectator Settings (untested, may not work)

### Changed

- Gameplay Modifiers like Autoplay & Spectator are now in their own submenu within Definitive Settings

## [v0.0.5] - 2026-05-16

### Fixed

- songs, and characters folder, including macros.dta has been slightly updated

## [v0.0.4] - 2026-05-12

### Fixed

- Minor fixes

## [v0.0.3] - 2026-05-12

### Added

- Disabled motion blur in all menus.
- Added instructions for non-technical users / players
- Added ability to enable/disable depth buffers

### Changed

- Xenia patch is now static and works for all versions
- Improved and simplified the build process
- Improved CI/CD and automatic code verification

### Fixed

- Autoplay now also fakes player being active.
- Minor DTA fixes

## [v0.0.2] - 2026-05-11

### Added

- Release packaging now includes `out/deluxe.xex` alongside the generated patch archive.
- Tag release builds stamp `src/config/ham_version.dta` with the tag name and short commit hash.
- Automatic docs publishing runs from the `docs/` subdirectory.
- DTA/build validation workflow runs on pushes that touch source or build-related files.

### Changed

- Release archives now pull `patch_xbox.hdr` and `patch_xbox_0.ark` from `out/gen/`.
- Docs publishing workflow now runs from the MkDocs project root in `docs/`.

## [v0.0.1] - 2026-05-11

### Added

- Initial public release packaging workflow.
- Basic project documentation, build instructions, and helper script guidance.
- MIT licensing notice for original project-authored content.

### Notes

- Stock/original game assets and binaries remain owned by their respective rights holders.
- This project is intended as a non-commercial fan preservation effort.
