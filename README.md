# Mapping Earthquakes

## Project Background

I previously created two earthquake maps with an earthquake overlay. In this project, I used this earthquake data to create another map showing the data in relation to the tectonic plates’ location on the earth, as well as showing all the earthquakes with a magnitude greater than 4.5 on this map. The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

To complete this project, I used a URL for GeoJSON earthquake data from the USGS website, retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days, and then added the data to a map. The approach I used was to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I also used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Deliverables

### Deliverable 1: Add Tectonic Plate Data
Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.

<img width="756" alt="Deliv1Map" src="https://user-images.githubusercontent.com/114960958/226149566-e73480af-e6cd-4ba7-adf9-75275b638418.png">

