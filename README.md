# Mapping_Earthquakes

## Project Overview
The objective of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world.\
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resources
- Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes above 4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0

## Results

### Create a Mapbox account, setup *config.js* and open *index.html*
To interact with the maps API the user have to visit [mapbox.com](https://www.mapbox.com/), create a Mapbox account and retrieve the access token.


To open the *index.html* file, open the command line, navigate to the main folder and on the command line, enter `python -m http.server`.


### Interactive Maps Views

<p align="center">
    <img src="Screen Shot 2021-12-12 at 8.50.40 PM.png">
    Streets view
</p>
<br>
<p align="center">
    <img src="Screen Shot 2021-12-12 at 8.50.53 PM.png">
    Satellite view
</p>
<br>
<p align="center">
    <img src="Screen Shot 2021-12-12 at 8.51.02 PM.png">
    Dark view
</p>
