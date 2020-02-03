# Visualizing Data with Leaflet (Leaflet challenge)

This project uses Leaflet and United States Geological Survey to visualize, educate the public and other government organizations on issues facing our planet. 
The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over 
the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data.

* [Background](#background)
* [File Structure](#file)
* [Running](#run)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visited the USGS GeoJSON Feed page and picked a 
data set to visualize. When we click on a data set, for example 'All Earthquakes from the Past 7 Days', we will be getting a JSON 
representation of that data. We will be using the URL of this JSON to pull in the data for our visualization.
 * Basic Visualization an earthquake data set
	![Basic](/Images/2-BasicMap.jpg)
 
The USGS wants to plot a second data set on map to illustrate the relationship between tectonic plates and seismic activity. 
Need to pull in a second data set and visualize it along side your original set of data. 
Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.
 * Second data set on map with number of base maps to choose from as well as separate out our two different data sets into overlays.
	![Advanced](/Images/5-Advanced.jpg)

## <a name="file"></a>File Structure

 * Leaflet-Step-1 and Leaflet-Step-2 are two folders which contains code for basic and advanced Maps.
 * The base webpage template is index.html.
 * /css holds styling file, style.css.
 * /js holds logic.js, the latter of which runs the javascript code that contains the visualization

##  <a name="Run"></a>Running the project

 This project was developed with the python -m http.server method.

##  <a name="technologies"></a>Technologies Used

* Javascript 
* HTML\CSS
* geomap library
* Leaflet library
