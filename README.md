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

As shown below, the [index.html](https://github.com/cedoula/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html) calls for the Mapbox API key in the *config.js* file. 
<p align="center">
    <img src="https://user-images.githubusercontent.com/68669675/97131133-54d41480-1711-11eb-8bd2-1b8539f65d2e.png"> 
</p>


<br>
To open the *index.html* file, open the command line, navigate to the main folder and on the command line, enter `python -m http.server`.


### Interactive Maps Views

<p align="center">
    <img src="">
    Streets view
</p>
<br>
<p align="center">
    <img src="">
    Satellite view
</p>
<br>
<p align="center">
    <img src="">
    Dark view
</p>