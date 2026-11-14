# DaringTact-tl

Official English translation data and localized assets for **DaringTact** (Princess Connect! Re:Dive JP translation layer).

The in-game DaringTact runtime pulls and updates active translation packs directly from this repository.

## Repository Contents
- `version.json`: Release manifest, build timestamp, and asset statistics.
- `translations/`:
  - `master.json`: Localized Master DB tables (character names, skill descriptions, quest titles, etc.).
  - `const_text.json`: System constants and UI string mappings.
  - `ui_paths.json`: Exact UI hierarchy transforms and text overrides.
  - `text_settings.json`: Typography, text wrapping, and font scaling configurations.
  - `stories/`: Pre-compiled story timeline asset JSONs.
  - `movies/`: Pre-compiled anime cutscene and movie subtitle cues.
  - `textures/`:
    - `Atlas/`: Localized UIAtlases (clean PNGs and JSON UV manifests).
    - `Texture2D/`: Localized standalone game graphics, banners, and icons.

## Upstream Sources
- Generated with [DaringTact-Tools](https://github.com/HachiFridge/DaringTact-Tools)
