# Official Legacy Themes (Modern `[M]` Ports)

Modern full ports of the four classic `[C]` themes from the [official AGS themes repository](https://github.com/adventuregamestudio/ags-themes), expanded for AGS **3.6.0.36+** with log panel, modern caret/selection, brace matching, and other keys added in 3.6.1+.

Community pack published on [selloa/ags-themes](https://github.com/selloa/ags-themes) (not submitted to the upstream repo). Same goal as the discussion in [adventuregamestudio/ags-themes#8](https://github.com/adventuregamestudio/ags-themes/issues/8): modern `[M]` themes that cover newer editor panes.

| | |
|---|---|
| **Modern ports by** | [selloa](https://github.com/selloa) |
| **Original AGS `[C]` themes by** | [AlanDrake](https://github.com/AlanDrake) (2022) |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |

`[C] Template Compat.json` is a reference skeleton only and is not part of this pack.

## Files

| File | Theme | Replaces legacy |
|---|---|---|
| `[M] Dracula.json` | Dracula | `[C] AGS-Dracula-0.2.json` |
| `[M] Visual Studio Dark.json` | Visual Studio Dark (full port) | `[C] VisualStudioDark.json` |
| `[M] Gray Tones Dark.json` | Gray Tones (dark script) | `[C] GrayTones(DarkScript).json` |
| `[M] Gray Tones Light.json` | Gray Tones (light script) | `[C] GrayTones(LightScript).json` |

### Visual Studio Dark: which file?

| File | What it is |
|---|---|
| `[C] VisualStudioDark.json` | Legacy exhaustive theme (rgba, old caret) - official repo |
| `[M] Dark.json` | Upstream minimal modern VS Dark - official repo |
| `[M] Visual Studio Dark.json` | **This pack** - full modern port from `[C]` |

## Install

1. Copy the JSON file(s) you want into `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Pick a theme from the list above
4. Restart the editor

Only the JSON files are loaded by AGS. `README.md` and screenshots are reference.

## Origins and licensing

### Dracula

- **Palette:** [Dracula Theme](https://draculatheme.com/) - [MIT License](https://github.com/dracula/dracula-theme/blob/main/LICENSE)
- Unofficial community expansion of AlanDrake's AGS Dracula `[C]` theme

### Visual Studio Dark

- Inspired by Microsoft Visual Studio Dark workbench colors (not a Microsoft product)
- Full modern expansion of AlanDrake's `[C] VisualStudioDark.json`

### Gray Tones

- Original AGS gray-chrome designs by AlanDrake (not a third-party VS Code port)
- Dark and light script variants preserved from the official `[C]` pair

### All themes

- **Original `[C]` JSON:** [ags-themes](https://github.com/adventuregamestudio/ags-themes) by AlanDrake
- **Modern `[M]` JSON:** port by selloa (2026), generated from the official `[C]` files via `tools/legacy_c_to_modern.py`

When redistributing Dracula, include the Dracula MIT notice. Credit AlanDrake for the original AGS themes and selloa for the modern expansion.

## Notes

- Users on older AGS (pre-3.6.0.36) can keep using the `[C]` files from the official repo.
- Theme JSON `name` / `version` fields are metadata only; the editor ignores them.
