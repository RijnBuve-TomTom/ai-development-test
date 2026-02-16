# OSM Routing Animation

An interactive web application that visualizes A* pathfinding on OpenStreetMap data.

## Features

- Load and parse gzipped OSM XML files
- Three routing modes: Car, Bicycle, Pedestrian
- Animated A* route calculation visualization
- Interactive map with Mapbox GL JS
- Draggable settings panel with light/dark themes
- Configurable animation speed (1-10)

## Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Configure Mapbox token:**
   - Copy `.env.example` to `.env`
   - Get your free Mapbox token from https://account.mapbox.com/access-tokens/
   - Replace `YOUR_MAPBOX_TOKEN_HERE` in `.env` with your token

3. **Run development server:**
   ```bash
   npm run dev
   ```

4. **Open browser:**
   Navigate to `http://localhost:3000`

## Usage

1. Select a map from the dropdown (leiden.osm.gz or amsterdam.osm.gz)
2. Choose routing mode (Car/Bicycle/Pedestrian)
3. Click on the map to set origin point (green marker)
4. Click again to set destination point (red marker)
5. Watch the A* algorithm explore routes (blue lines)
6. Final route shown in red
7. Adjust animation speed with slider
8. Toggle OSM tile background
9. Switch between light/dark themes
10. Drag the settings panel to reposition

## Project Structure

```
src/
├── core/           # StateManager and types
├── data/           # OSM parsing and graph
├── routing/        # A* algorithm and map matching
├── map/            # Mapbox rendering and animation
└── ui/             # User interface components
```

## Building

```bash
npm run build
```

## Configuration

- JetBrains Junie
- Skill superpowers
- Sonnet 4.5
