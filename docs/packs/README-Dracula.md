# Dracula for Adventure Game Studio Editor

Modern full port of the classic AGS Dracula theme for the [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) Editor.

| | |
|---|---|
| **Modern port by** | [selloa](https://github.com/selloa) |
| **Original AGS `[C]` theme by** | [vga256](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/editor-theme-dracula-dark/) (2021) |
| **Palette** | [Dracula](https://draculatheme.com/) |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |
| **Accent** | Pink `#ff79c6` (syntax keywords); cyan line numbers |

This expands the legacy `[C] AGS-Dracula-0.2.json` with modern `caret`/`selected`, log panel, brace matching, and other keys added in AGS 3.6.1+.

## File

| File | Theme |
|---|---|
| `[M] Dracula.json` | Dracula |

## Install

1. Place the JSON file in `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Choose **Dracula**
4. Restart the editor

## Origins and licensing

- **Palette:** [Dracula Theme](https://github.com/dracula/dracula-theme) - [MIT License](https://github.com/dracula/dracula-theme/blob/main/LICENSE)
- **Original AGS `[C]` theme:** by [vga256](https://www.adventuregamestudio.co.uk/forums/modules-plugins-tools/editor-theme-dracula-dark/) (forum post, 2021); later included in the official [ags-themes](https://github.com/adventuregamestudio/ags-themes) repo
- **Modern `[M]` JSON:** port by selloa (2026), generated from the official `[C]` file with palette preserved

When redistributing, include the Dracula MIT notice and credit vga256 for the original AGS mapping and selloa for the modern expansion.

## Notes

- Legacy users on older AGS can keep using `[C] AGS-Dracula-0.2.json` from the official themes repo.
- AGS theme JSON only stores display `name` / `version` for humans; the editor ignores them as metadata.
