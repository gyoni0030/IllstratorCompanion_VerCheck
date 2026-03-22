# Changelog - Illustrator Companion

## [0.9.1] - 2026-03-23
### Added
- Added automatic character encoding detection for script files (.jsx), enabling correct loading in UTF-8 or Shift_JIS
- Added an optional script execution cache
- When re‑registering (overwriting) a script, user‑defined argument values are now preserved
- Scripts that include the #include directive can now run as long as their dependent files exist in the correct relative paths
- Added links to the official website, privacy policy, and changelog on the About screen
### Fixed
- Fixed an issue where scripts saved in Shift_JIS could appear garbled when loaded

## [0.9.0] - 2026-03-21
### Added
- Added support for dragging and dropping folders when registering scripts
- Added support for the “.jsxbin” extension when registering scripts
- The auto-restore maximization feature now also works when the Illustrator window is unintentionally restored from maximized state by slightly dragging its title bar
- Added a confirmation message when removing scripts from the launcher
### Changed
- Improved performance and state detection accuracy of the auto-restore maximization option
- Reorganized the options UI
- Improved wording of some messages
### Fixed
- Fixed an issue where the window would be automatically maximized when resizing it while not maximized with the auto-restore maximization option enabled
- Fixed an issue where, when the XYWH caret target was set to the Control panel, caret movement shortcuts could become unresponsive or move to an incorrect field
- Fixed an issue where argument UI for scripts not included in the selected category would remain visible after changing categories
- Fixed an issue where the current category would reset to default after editing categories
- Fixed an issue where execution results and other information could disappear at inappropriate timing
- Fixed an issue where the launcher size would become smaller on the next launch if the app was closed in window shade state
- Fixed an issue where unregistered scripts in the managed script folder could not be added to the launcher

## [0.8.0] - 2026-03-15 Preview Release
