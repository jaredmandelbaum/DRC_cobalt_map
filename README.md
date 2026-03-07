# DRC Cobalt Map

Standalone map scrollytell for Shorthand, focused on a zooming satellite map sequence and text overlays.

## Active Files
- `shorthand-embed-maplibre.html`: current production embed snippet for Shorthand.
- `drc-cobalt-overlays.pmtiles`: hosted PMTiles overlays used by the embed.
- `drc_overlays.geojson`: source GeoJSON used to build the PMTiles overlays.
- `assets/fonts`: self-hosted Lato font files.

## Stack
- MapLibre GL JS
- PMTiles (vector overlays)
- Esri World Imagery + World Boundaries and Places reference labels

## Attribution and Licensing
- Basemap imagery and labels are provided by Esri services (including Maxar, Earthstar Geographics, and the GIS User Community credits shown in-map).
- Lato font is licensed under the SIL Open Font License 1.1 (`assets/fonts/OFL.txt`).

## Local Check
Serve this folder locally:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/shorthand-embed-maplibre.html`.
