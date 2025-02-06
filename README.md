# OSM Data Analysis: Building Access to Hospitals

## Overview

This Python script analyzes OpenStreetMap (OSM) data to assess the accessibility of hospitals for buildings within a defined study area. The script uses libraries such as `OSMnx`, `Folium`, `Geopandas`, `NetworkX`, and `UTM` to fetch, process, and visualize geospatial data. It also calculates the shortest walking distance from each building to the nearest hospital, helping to understand access to healthcare facilities.

## Key Features

- Fetches and visualizes building, hospital, and road network data within a defined radius from a central point.
- Computes the shortest path distance from each building to the nearest hospital using OSM road network data.
- Displays the data on an interactive Folium map with layers for buildings, hospitals, and road networks.
- Visualizes access to hospitals by mapping the distance from each building.

## Dependencies

To run this script, you will need the following Python libraries:

- **`OSMnx`**: For downloading and working with OpenStreetMap data.
- **`Folium`**: For interactive map visualization.
- **`NetworkX`**: For calculating shortest paths on the road network.
- **`Geopandas`**: For geospatial data manipulation.
- **`Shapely`**: For geometric operations on spatial data.
- **`UTM`**: For handling UTM zone calculations.
- **`Matplotlib`**: For plotting results.
- **`Warnings`**: To suppress certain warnings for clean execution.
- **`Seaborn`**: For heatmap visualization.

You can install these libraries using `pip`:

```py
pip install osmnx folium networkx geopandas shapely utm matplotlib
