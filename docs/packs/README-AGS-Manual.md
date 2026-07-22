# AGS Manual themes for Adventure Game Studio Editor

Unofficial community port of the **dark** and **light** colour schemes from the [AGS Manual](https://adventuregamestudio.github.io/ags-manual/) HTML documentation for the [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) Editor.

| | |
|---|---|
| **AGS port by** | [selloa](https://github.com/selloa) |
| **Colour inspiration** | [ags-manual](https://github.com/adventuregamestudio/ags-manual) build system / published manual |
| **Live manual** | https://adventuregamestudio.github.io/ags-manual/ |
| **Format** | Modern (`[M]`) - AGS **3.6.0.36+** |

The published manual site offers a dark/light toggle; these editor themes map those documentation palettes onto the AGS Editor UI and script editor. This is **not** an official Adventure Game Studio release.

## AGS Editor Help plugin

These two themes were created in conjunction with the **AGS Editor Help plugin**. The colours match the plugin's manual viewer, so the help UI fits the rest of the editor instead of looking like a separate skin.

Use **AGS Manual Dark** or **AGS Manual Light** with the Help plugin for the best result.

## Files

| File | Theme | Manual mode |
|---|---|---|
| `[M] AGS Manual Dark.json` | AGS Manual Dark | Dark (default on the site) |
| `[M] AGS Manual Light.json` | AGS Manual Light | Light |

## Install

1. Place the JSON file(s) in `%LocalAppData%\AGS\Themes`
2. In AGS: **File -> Preferences -> Color Theme**
3. Choose **AGS Manual Dark** or **AGS Manual Light**
4. Restart the editor

## Origins & licensing

- **Manual site & build:** [adventuregamestudio/ags-manual](https://github.com/adventuregamestudio/ags-manual) - [MIT License](https://github.com/adventuregamestudio/ags-manual/blob/master/LICENSE) (Copyright (c) 2020 various contributors). Colours taken from the HTML manual's dark/light presentation at [adventuregamestudio.github.io/ags-manual](https://adventuregamestudio.github.io/ags-manual/).
- **AGS Editor theme JSON:** port by selloa (2026), mapping those manual palettes to the modern AGS theme format.

When redistributing, credit the AGS Manual project and note that the Editor JSON mapping is by selloa.

## Notes

AGS theme JSON only stores a display `name` / `version` for humans; the editor ignores them as metadata. Credit and license details live in this README.
