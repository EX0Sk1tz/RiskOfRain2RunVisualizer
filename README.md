# RiskOfRain2RunVisualizer

A lightweight, single file web app to view Risk of Rain 2 RunReport XML files. It parses your run history locally in the browser and shows a clean dashboard. You can choose which stats you want to see and export a RoR2 style stats panel as PNG.

## Live Version

Use the hosted version directly in your browser:

https://ex0sk1tz.github.io/RiskOfRain2RunVisualizer/

No installation required. Just open the link and load your RunReport XML.

## Where to Find Your Run Files

Risk of Rain 2 stores run history XML files here:

`Steam\steamapps\common\Risk of Rain 2\Risk of Rain 2_Data\RunReports\History`

Each file inside the `History` folder is a `RunReport` XML that you can load into the viewer.

## Features

- Upload or drag and drop RunReport XML files
- Run overview and player info
- Modular stats selection with persistent preferences
- Search and filter stats
- Export a RoR2 style stats panel as PNG
- No backend and no data uploads

## Notes

- Everything runs locally in your browser
- No data is sent anywhere
- Some stats only appear if they exist in your XML file

## License

MIT
