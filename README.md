# PeopleFlux
Mapping Geograph and Heatmap in Python

To start, I was learning from Marcelo Rovai’s article titled [Mapping Geograph Data in Python](https://towardsdatascience.com/mapping-geograph-data-in-python-610a963d2d7f). The article had a good step by step list for making a geo visualization using shapefile in Python. In Python, many libraries are useful for creating geovis for map, for example geopandas (ver 7.0 dated 11 March 2020, on the web https://geopandas.org/index.html).

The steps can be categorized into several important parts:

Input

1.	Shapefile (.shp, .shx, .dbf) 
Shapefile is developed by ESRI as an open specification. A shapefile explained as geometries or spatial format, also called “points”, “polylines” or “polygons”. Other terms from OpenStreetMap that similar for shapefile format are “nodes”, “ways”, or “closed ways”.
The shapefile format has a grouping of several files, that represent different types of geographical data:
•	.shp – shape format; the feature geometry
•	.shx – shape index format; a position index of the feature geometry
•	.dbf – attribute format

2.	
Libraries
Output
