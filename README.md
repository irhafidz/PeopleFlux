# PeopleFlux

##About
Mapping people flux d






























Mapping Geograph and Heatmap in Python

To start, I was learning from 
1. Marcelo Rovai’s article titled [Mapping Geograph Data in Python](https://towardsdatascience.com/mapping-geograph-data-in-python-610a963d2d7f).
2. GIS and Python from Uni of Helsinki webpage [GeoPython Auto GIS](https://automating-gis-processes.github.io/2016/course-info.html)

The article had a good step by step list for making a geo visualization using shapefile in Python. For making a geograph, you'll need:
* a shapefile
* Python libraries, such as geopandas, Python shapefile (PyShp)

Shapefile (.shp, .shx, .dbf) 

A shapefile explained as geometries or spatial format, also called “points”, “polylines” or “polygons”. Other terms from OpenStreetMap that similar for shapefile format are “nodes”, “ways”, or “closed ways”. The shapefile format consist of different files that represent different types of geographical data:
•	.shp – shape format; the feature geometry
•	.shx – shape index format; a position index of the feature geometry
•	.dbf – attribute format

1. Installing Libraries: PyShp
In Python, many libraries are useful for creating geovis for map, for example geopandas (ver 7.0 dated 11 March 2020, on the web https://geopandas.org/index.html). the list of libraries/ package needed for the geovis are:
* Python Shapefile (Pyshp)
* numpy
* pandas
* geopandas
* matplotlib
* seaborn

[PyShp](https://pypi.org/project/pyshp/) is a python shapefile library that will reads and writes ESRI shapefiles in Python. To install Python shapefile library (PyShp) in [Anaconda prompt](https://anaconda.org/conda-forge/pyshp) for Jupyter from Anaconda prompt:

`conda install -c conda-forge pyshp` 

or install them from pip:
`pip install pyshp`

2. Installing and Importing other libraries
We need to imported the libraries we need for the visualization, such as numpy, pandas, geopandas, matplotlib and seaborn

conda install -c anaconda numpy
conda install -c anaconda pandas
conda install -c anaconda geopandas


conda install -c anaconda numpy 







<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMTc3NTg2MDUsLTk1MTQ1NDMzMF19
-->