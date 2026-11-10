# johannesburg-last-mile-map

Static GitHub Pages site for an interactive story map of last-mile connectivity in Gauteng's three metros (Johannesburg, Tshwane and Ekurhuleni). Live at https://gavacharles.github.io/johannesburg-last-mile-map/

The content is a provisional research prototype built from open data; modelled feeder routes are candidates, not proposed services.

## Contents

| Path | What it is |
|---|---|
| `index.html` | The map page |
| `charts/` | Chart images used on the page |
| `closeups/`, `bus_closeups/` | Close-up images for individual zones and routes, named by ID (e.g. `EKU-003.jpg`, `GT-001.jpg`) |
| `.nojekyll` | Serve files as they are on GitHub Pages |

There is no build step in this repository. To view locally, serve the folder (`python -m http.server`) and open http://localhost:8000.

## Data sources and attribution

OpenStreetMap contributors (ODbL); WorldPop 2020 constrained population (CC BY 4.0), scaled to Census 2022 metro totals; GHSL R2023A (European Commission JRC); geoBoundaries (CC BY 3.0 IGO); Meta Relative Wealth Index via HDX; Esri and partners for basemaps and imagery. Map library: Leaflet (BSD 2-Clause).
