## Mapping Earthquakes Project Plan

### Scope
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

### Deliverables
To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

### Resources
Data Sources:
1. https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
2. https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
3. https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

Software: Visual Studio Code 1.71.2

### Requirements
The approach will use JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. In addition, it'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.