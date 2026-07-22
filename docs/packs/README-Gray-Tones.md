# Gray Tones for Adventure Game Studio Editor

Modern full ports of the classic AGS Gray Tones pair for the [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) Editor.

| | |
|---|---|
| **Modern port by** | [selloa](https://github.com/selloa) |
| **Original AGS `[C]` themes by** | [imagazzell](https://github.com/imagazzell) |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |

Original designs: classic **gray editor chrome** with either a **dark** or **light** script pane. Not a port of a third-party VS Code theme.

## Files

| File | Theme |
|---|---|
| `[M] Gray Tones Dark.json` | Gray chrome + dark script editor (`#1e1e1e`) |
| `[M] Gray Tones Light.json` | Gray chrome + light script editor (`#c8c8c8`) |

## Install

1. Place one or both JSON files in `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Choose **Gray Tones Dark** or **Gray Tones Light**
4. Restart the editor

## Origins and licensing

- **Original AGS themes:** by [imagazzell](https://github.com/imagazzell) - [Gray Color Theme](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/gray-color-theme/) forum post and [AGS-Color-Themes](https://github.com/imagazzell/AGS-Color-Themes)
- Later included in the official [ags-themes](https://github.com/adventuregamestudio/ags-themes) repo as `[C] GrayTones(DarkScript).json` and `[C] GrayTones(LightScript).json`
- **Modern `[M]` JSON:** port by selloa (2026), generated from the official `[C]` files with palettes preserved

## Notes

- Legacy users on older AGS can keep using the `[C]` files from the official themes repo.
- AGS theme JSON only stores display `name` / `version` for humans; the editor ignores them as metadata.
