# Bubble Day

A pencil-sketched daily to-do list made of bubbles. It's a single-page web app that installs to your phone's home screen and works offline.

## Files
- `index.html`: the whole app
- `manifest.webmanifest`, `icons/`: name and icon for the home screen
- `sw.js`: keeps it working offline

## Publishing an update
After changing `index.html`, bump `VERSION` in `sw.js` (e.g. `bubble-day-v2`) and upload the folder again.
Installed copies pick up the new version the next time they're opened with a connection.
