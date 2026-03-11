# Spin the Wheel to decide

## About 
This project generates a website that is offline available.
The website shows multiple wheels in each other which you can spin to get a decision done.

Options for the wheel can be inserted in a seperate page.

## Files
- `index.html`: main nested wheels page (press Space to spin)
- `options.html`: edit ring names/options (saved in `localStorage`)
- `sw.js`: offline cache (service worker)
- `manifest.webmanifest`: PWA metadata

## Run locally
- Open `index.html` directly, or serve the folder with any static server.
- Example (Node): `npx serve .`