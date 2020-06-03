Visualizing Data with Leaflet

United States Geological Survey - Last 30 Day Earthquake Maps

![1-Logo](Images/1-Logo.png)

Please add your API key to the config.js file located in static/js file path before opening the index.html file.

This demostrates how Leaflet.js is used to visualize geoJSON data. The javascript uses Leaflet layer control and overlay maps, using a live API feed provided by the USGS (United States Geological Survey). The data includes all earthquake data for the Past 30 Days. Additional layer of tectonic plates provides the relationship between tectonic plates and seismic activites.

Sources Used:
queryUrl = "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.geojson" 
faultlinequery = "https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_plates.json" 
outdoorsmap = https://api.tiles.mapbox.com id: "mapbox.outdoors 
satellitemap = https://api.tiles.mapbox.com id: "mapbox.satellite 
grayscalemap = https://api.tiles.mapbox.com id: "mapbox.light 

![1-Map](Images/220-05-30GreyscaleMap.png)
![2-Map](Images/220-05-30OutdoorMap.png)
![3-Map](Images/220-05-30SatelliteMap.png)

Please see Images folder (inside the Leaflet CHallenge folder) for snapshots of the live data.


