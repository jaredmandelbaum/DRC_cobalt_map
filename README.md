# DRC Cobalt Map

Standalone map scrollytell extracted from `drc_cobalt_scrollytell`, focused only on the zooming satellite map sequence and text overlays.

## Stack
- Leaflet 1.9.4
- Esri World Imagery + World Boundaries and Places reference labels
- Self-hosted Lato font (`assets/fonts`)

## Attribution and Licensing
- Map imagery and labels are provided by Esri services used in this project.
- Data context references OpenStreetMap contributors.
- Lato font is licensed under the SIL Open Font License 1.1 (`assets/fonts/OFL.txt`).

## Run locally
Open `index.html` directly, or serve with a static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
