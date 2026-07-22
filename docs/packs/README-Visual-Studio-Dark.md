# Visual Studio Dark for Adventure Game Studio Editor

Full modern port of the official AGS Visual Studio Dark theme for the [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) Editor.

| | |
|---|---|
| **Modern port by** | [selloa](https://github.com/selloa) |
| **Original AGS `[C]` theme by** | [AlanDrake](https://github.com/AlanDrake) |
| **Inspired by** | Visual Studio Dark (2012-2019) |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |

## Which file should I use?

| File | What it is |
|---|---|
| `[C] VisualStudioDark.json` | Legacy exhaustive theme (rgba, old caret format) - official repo |
| `[M] Dark.json` | Upstream minimal modern VS Dark (~global fallbacks only) - official repo |
| `[M] Visual Studio Dark.json` | **This release** - full modern port from `[C]` with log panel, brace tokens, expanded script editor |

## File

| File | Theme |
|---|---|
| `[M] Visual Studio Dark.json` | Visual Studio Dark |

## Install

1. Place the JSON file in `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Choose **Visual Studio Dark**
4. Restart the editor

## Origins and licensing

- **Inspired by:** Microsoft Visual Studio Dark workbench colors
- **Original AGS `[C]` theme:** [ags-themes](https://github.com/adventuregamestudio/ags-themes) by AlanDrake (2022)
- **Modern `[M]` JSON:** port by selloa (2026), generated from `[C] VisualStudioDark.json`

## Notes

- This is a community expansion of the official AlanDrake theme, not a Microsoft product.
- AGS theme JSON only stores display `name` / `version` for humans; the editor ignores them as metadata.
