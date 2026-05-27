# Navigation System

## Overview
A route planning and navigation system using map data, supporting shortest-path algorithms and real-time location tracking.

## Tools & Technologies
- **Python** – Core pathfinding algorithms (Dijkstra, A*)
- **OpenCV** – Map rendering and visualization
- **Machine Learning** – Traffic prediction model
- **IoT / Raspberry Pi** – GPS module integration for live tracking
- **MySQL** – Map data, POI, and route history storage
- **Pandas** – GPS log processing and analysis

## Project Structure
```
navigation_system/
├── algorithms/
│   ├── dijkstra.py
│   └── astar.py
├── map/
│   ├── renderer.py
│   └── map_data/
├── gps/
│   └── tracker.py
├── ml/
│   └── traffic_predictor.py
├── database/
│   └── schema.sql
└── README.md
```

## Features
- Shortest and fastest route calculation
- Turn-by-turn directions
- Real-time GPS tracking via Raspberry Pi + GPS module
- Traffic-aware routing with ML predictions
- Map visualization with OpenCV overlay
- Route history and favourites in MySQL

## Setup
```bash
pip install -r requirements.txt
python algorithms/astar.py
```
