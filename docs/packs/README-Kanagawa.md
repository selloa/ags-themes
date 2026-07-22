# Kanagawa for Adventure Game Studio Editor

Unofficial community port of [Kanagawa](https://github.com/rebelot/kanagawa.nvim) for the [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) Editor.

| | |
|---|---|
| **AGS port by** | [selloa](https://github.com/selloa) |
| **Original theme by** | [Tommaso Laurenzi](https://github.com/rebelot) (rebelot) |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |

This is **not** an official Kanagawa port. Colors follow the palette and semantic mappings from [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim).

## Files

| File | Flavor | Accent |
|---|---|---|
| `[M] Kanagawa Wave.json` | Wave (default) | Crystal blue `#7E9CD8` |
| `[M] Kanagawa Dragon.json` | Dragon (darker/muted) | Dragon blue `#8ba4b0` |
| `[M] Kanagawa Lotus.json` | Lotus (light) | Lotus blue `#4d699b` |

## Install

1. Place the JSON files in `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Choose a Kanagawa flavor
4. Restart the editor

## Origins & licensing

- **Original:** [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) by Tommaso Laurenzi - [MIT License](https://github.com/rebelot/kanagawa.nvim/blob/master/LICENSE) 
 Copyright (c) 2021 Tommaso Laurenzi
- **AGS theme JSON:** port by selloa (2026), based on Kanagawa palette colors and Wave / Dragon / Lotus theme mappings

When redistributing, include the original MIT copyright notice for Kanagawa / Tommaso Laurenzi, and credit selloa for the AGS Editor mapping.

## Notes

AGS theme JSON only stores a display `name` / `version` for humans; the editor ignores them as metadata. Credit and license details live in this README.
