
# AVL Data Simulator

A browser-based tool for simulating realistic AVL (Automatic Vehicle Location) data along real road networks — built for WebGIS platform testing.

## Features

- Select route by clicking two points on the map
- Real road routing via OSRM engine
- Simulate multiple vehicle types simultaneously
- Logic-based descriptive attributes (speed, fuel, temperature, RPM, etc.)
- Vessel tracking limited to Persian Gulf / Gulf of Oman
- Export to **5 structured CSV tables** or **JSON**
- No server required — runs in browser

## Vehicle Types

| Vehicle | Land/Water | Special Attributes |
|---|---|---|
| 🚒 Fire Truck | Land | — |
| 🚑 Ambulance | Land | Mission status |
| 🚛 Truck | Land | Cargo weight |
| 🚚 Camion | Land | Cargo weight |
| 🚔 Police Car | Land | Patrol zone |
| 🚌 Bus | Land | Passenger count |
| 🚗 Light Vehicle | Land | — |
| 🚢 Vessel | Water | Depth |

## Output Structure (5 CSV Tables)

## Usage

Download and open `index.html` in any browser. No installation needed.

## Tech Stack

- Leaflet.js — map rendering
- OSRM — real road routing
- OpenStreetMap — base tiles
- Vanilla JavaScript
