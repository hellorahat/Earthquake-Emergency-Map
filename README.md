# Earthquake-Emergency-Map

## Gathering Data

Data was gathered from the United States Geological Survey. By inputting a range for location and time, it generated a CSV file containing info of all Earthquakes in a specific region.

## Creating the Visualization

Within the CSV file, one of the details that was given was the geom coordinates for the earthquake. Geopy was used to convert the coordinates into states within the U.S.

Using this data, a choropleth map of the amount of earthquake occurrences per state was created, and a choropleth of the average earthquake magnitude per state was also created.
