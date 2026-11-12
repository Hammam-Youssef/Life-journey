# Life Journey Map

Enter your birth year, birthplace and every place you have lived, in order, and watch your journey drawn on a real world map. Export it as an image (color / black & white, with or without map, names, numbers) with the total distance in km. Arabic and English UI.

Single static file: `index.html` (no build step). Open it in a browser or host it on GitHub Pages.

## Run locally
Open `index.html` in a browser (needs internet for d3 and topojson from cdnjs).

## Data sources and attributions (review before selling)
- Country borders: Natural Earth via `world-atlas` (ISC license; Natural Earth is public domain).
- Countries and regions list: `country-state-city` npm package. Its license is **GPL-3.0**; check with a lawyer or replace the data before any commercial use.
- Cities: `all-the-cities` (MIT), derived from GeoNames data (CC BY 4.0, attribution required: https://www.geonames.org).

## Notes
- Image saving uses the claude.ai downloads capability when available; elsewhere it opens the image so it can be saved by long-press / right-click.
- No license file is included on purpose (all rights reserved) until you decide how to license the project.
