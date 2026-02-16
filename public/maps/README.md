# OSM Map Files

Place your gzipped OSM XML files here (e.g., `leiden.osm.gz`, `amsterdam.osm.gz`)

## Getting OSM Data

1. Visit https://www.openstreetmap.org/
2. Navigate to your area of interest
3. Click "Export" and select a small area
4. Or use https://download.geofabrik.de/ for pre-extracted regions
5. Compress the .osm file with gzip: `gzip filename.osm`
6. Place the .osm.gz file in this directory

## Update index.json

After adding files, update `index.json` with the list of available files:

```json
[
  "leiden.osm.gz",
  "amsterdam.osm.gz"
]
```
