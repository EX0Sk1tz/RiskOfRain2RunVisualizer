# RoR2 RunReport Viewer

A lightweight, single file web app to view Risk of Rain 2 RunReport XML files. It parses your run history locally in the browser and shows a clean dashboard. You can choose which stats you want to see and export a RoR2 style stats panel as PNG.

## Features

- Upload or drag and drop RunReport XML files
- Run overview and player info
- Modular stats selection (your choices persist in the browser)
- Search and filter stats
- Export a RoR2 style stats panel as PNG
- Works fully offline, no backend, no uploads

## Getting Started

1. Download or clone this repository
2. Open `index.html` in your browser

Optional: Host it via GitHub Pages (recommended for sharing)

## GitHub Pages

1. Push `index.html` to the repository root
2. Go to `Settings` -> `Pages`
3. Select:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
4. Open the shown Pages URL

## Supported XML

This viewer expects the Risk of Rain 2 `RunReport` format, for example:

- `RunReport/version`
- `RunReport/playerInfos/PlayerInfo/statSheet/fields/*`
- `RunReport/playerInfos/PlayerInfo/itemStacks/*` (optional)
- `RunReport/ruleBook` (optional)

## Notes

- Everything runs locally in your browser
- No data is sent anywhere
- Some values only show up if your XML contains them

## License

MIT
