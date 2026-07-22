# Official Legacy Themes (Modern `[M]` Ports)

Modern full ports of the four classic `[C]` themes from the [official AGS themes repository](https://github.com/adventuregamestudio/ags-themes), expanded for AGS **3.6.0.36+** with log panel, modern caret/selection, brace matching, and other keys added in 3.6.1+.

Community pack published on [selloa/ags-themes](https://github.com/selloa/ags-themes) (not submitted to the upstream repo). Same goal as the discussion in [adventuregamestudio/ags-themes#8](https://github.com/adventuregamestudio/ags-themes/issues/8): modern `[M]` themes that cover newer editor panes.

| | |
|---|---|
| **Modern ports by** | [selloa](https://github.com/selloa) |
| **Original `[C]` Visual Studio Dark by** | [persn](https://github.com/persn) (2018) |
| **Original `[C]` Gray Tones by** | [imagazzell](https://github.com/imagazzell) |
| **Original `[C]` Dracula by** | [vga256](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/editor-theme-dracula-dark/) (2021) |
| **Official collection / updates** | [AlanDrake](https://github.com/AlanDrake) ([ags-themes](https://github.com/adventuregamestudio/ags-themes)) |
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

### Visual Studio Dark

- Inspired by Microsoft Visual Studio Dark workbench colors (not a Microsoft product)
- **Original AGS theme JSON:** by [persn](https://github.com/persn) (Per Olav Flaten), introduced with the editor color-theme system ([adventuregamestudio/ags#427](https://github.com/adventuregamestudio/ags/pull/427), 2018). File title: "Visual Studio Dark Theme Replica"
- Later collected into the official [ags-themes](https://github.com/adventuregamestudio/ags-themes) repo
- This pack: full modern `[M]` expansion of that `[C]` file

### Gray Tones

- **Original AGS themes:** by [imagazzell](https://github.com/imagazzell) - [Gray Color Theme](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/gray-color-theme/) forum post and [AGS-Color-Themes](https://github.com/imagazzell/AGS-Color-Themes)
- Classic gray editor chrome with dark or light script pane (not a third-party VS Code port)
- Later included in the official [ags-themes](https://github.com/adventuregamestudio/ags-themes) repo

### Dracula

- **Palette:** [Dracula Theme](https://draculatheme.com/) - [MIT License](https://github.com/dracula/dracula-theme/blob/main/LICENSE)
- **Original AGS `[C]` theme:** by [vga256](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/editor-theme-dracula-dark/) (forum post, 2021); later included in the official [ags-themes](https://github.com/adventuregamestudio/ags-themes) repo
- Unofficial community expansion to modern `[M]` format

### All themes

- **Collected / maintained in:** [ags-themes](https://github.com/adventuregamestudio/ags-themes) by [AlanDrake](https://github.com/AlanDrake) (compatibility updates, modern format docs; not the original author of these four `[C]` themes)
- **Modern `[M]` JSON:** port by selloa (2026), generated from the official `[C]` files via `tools/legacy_c_to_modern.py`

When redistributing Dracula, include the Dracula MIT notice. Credit persn (VS Dark), imagazzell (Gray Tones), vga256 (Dracula), and selloa for the modern expansion.

## Notes

- Users on older AGS (pre-3.6.0.36) can keep using the `[C]` files from the official repo.
- Theme JSON `name` / `version` fields are metadata only; the editor ignores them.
