# Changelog

## [1.1.0] - 2026-10-09
The app is now called **WinTess OCR** (formerly Screenshot OCR). Settings and autostart are migrated automatically.

### Added
- Side toolbar next to the selection: recognize text, fix keyboard layout, copy image, save as…, record GIF, close.
- GIF recording of the selected area: 1–60 s, 15 / 30 / 60 fps, quality and picture-size options, optional mouse cursor, `Esc` to stop.
- Keyboard layout fixer: converts text typed in the wrong layout (`ghbdtn` → `привет`), Russian or Ukrainian, also for clipboard text.
- "Functions and hotkeys" window: custom key bindings for every function and all settings in one place.
- "Save as…" with a choice of format: PNG, JPEG, BMP, GIF, TIFF.
- Optional reading of QR codes and barcodes.
- Automatic update check (once a day, can be turned off).

### Changed
- Better recognition: speed / accuracy profiles, optional double processing, improved reading of colored text, recognition runs in the background.
- Faster language downloads: several files at once, with speed shown.

## [1.0.1] - 2026-10-03
### Changed
- Language models are now downloaded from tessdata_best (more accurate, slower, larger files).
- The "Languages and data folder" window detects older (fast) models and offers to replace them.

## [1.0.0] - 2026-10-03
- Initial release.
