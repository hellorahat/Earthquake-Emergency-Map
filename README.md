![CrossCompute Log](https://crosscompute.com/images/CrossCompute-LogoBrand-Horizontal-20200420.svg)

# Earthquake-Emergency-Map
## Add a gif or a couple of images of the visualization

## Introduction -- Write a summary that answers the questions: what is this tool, how does it work,  

## Gathering Data

Data was gathered from the United States Geological Survey. By inputting a range for location and time, it generated a CSV file containing info of all Earthquakes in a specific region.

https://earthquake.usgs.gov/earthquakes/search/

## Creating the Visualization

Within the CSV file, one of the details that was given was the geom coordinates for the earthquake. Geopy was used to convert the coordinates into states within the U.S.

Using this data, a choropleth map of the amount of earthquake occurrences per state was created, and a choropleth of the average earthquake magnitude per state was also created.

## Add Your Bio, include your email, link to your linkedIn