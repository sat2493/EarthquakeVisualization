# Earthquake Visualization

This is a visualization was made with the intent of visualizing daily earthquake data. An earthquake occurence is visualized based on its location, and magnitude.

Table of contents
=================

<!--ts-->
   * [Dataset](#Dataset)
   * [View](#View)
   * [Features](#Features)
   * [Tools](#Features)
   * [Limitations](#Limitations)
<!--te-->

# Dataset

The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their data sources can be found [here](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). 

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. The dataset is all earthquakes within the past 7 days.

# View

The web display of all earthquakes within the last 7 days can be viewed [here](https://sat2493.github.io/EarthquakeVisualization/).

# Features

The web display has the features of <Google Maps>. An earthquake occurence is represented by a circle marker on the map. The size and color of this marker reflects the magnitude of this earthquake. The legend displays the guide to interpreting the color of these earthquakes. 
  
Selecting and clicking an earthquake marker displays a popup with information on the magnitude, and location of the earthquake.

Tectonic plates, by default, have been added to the map. They add another visual representation of the relationship between earthquakes and tectonic plate locations.

The map layout itself is adjustable to three parameters: streets, satelite, light. An adjustment controller is available on the top right to modify the visualization of the map to your preference. Furthermore, displays of the actual earthquake pins and tectonic plates can be removed or added.

# Tools

Two JavaScript libraries and tools,[Leaflet](https://leafletjs.com/) and [D3](https://d3js.org/) were used for the adding functionality, earthquake dots, and tectonic lines onto the map, while [Mapbox](https://www.mapbox.com/) provided the actual map object information necessary to place our data. 

# Limitations

A clear relationship can be seen between earthquakes and tectonic plates. It is evident from the map that earthquakes tend to occur along tectonic borders. One limitation of this visualization is the lack of time parameters. It is not only important to know how severe an earthquake is, but also the frequency at which it shakes a region. An additional time parameter can allow more insight on the proclivity of some regions to experience earthquakes to others.
