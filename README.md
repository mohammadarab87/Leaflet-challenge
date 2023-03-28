# Earthquake Visualization with USGS Data

The United States Geological Survey (USGS) collects a vast amount of earthquake data from around the world every day, and needs a meaningful way to visualize this data.

The purpose of this project is to create a tool that allows USGS to educate the public and government organizations about issues facing our planet.

## Dataset

To begin, I will use earthquake data provided by the USGS in JSON format, updated every 5 minutes.

The data can be accessed by visiting the ***USGS GeoJSON Feed page*** .

## Visualization

![Screenshot 2023-03-28 093608](https://user-images.githubusercontent.com/113273722/228257656-7bdaecdf-2cf4-4ac5-887b-7098111142a9.png)


I will use Leaflet to create a map that plots all the earthquakes from the selected dataset based on their longitude and latitude

The data markers will reflect the magnitude of the earthquake by their size, and the depth of the earthquake by color.

Earthquakes with higher magnitudes will appear larger, and earthquakes with greater depth will appear darker in color.

Popups will provide additional information about each earthquake when its associated marker is clicked

## Steps to Create the Visualization

* Select a dataset to visualize from the USGS GeoJSON Feed page
* Use the URL of the JSON representation of the selected dataset to pull in the data for the visualization
* Use Leaflet to create a map and plot the earthquakes based on their longitude and latitude
* Size the markers according to the magnitude of the earthquake and color them according to the depth of the earthquake
* Include popups that provide additional information about each earthquake when its associated marker is clicked
* Create a legend that provides context for the map data

## Tools Used

* Leaflet - an open-source JavaScript library for creating interactive maps
* JavaScript - the programming language used to create the visualization
* HTML - the markup language used to structure the visualization web page
* CSS - the style sheet language used to style the visualization web page
