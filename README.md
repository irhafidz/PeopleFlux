# PeopleFlux

##About dataset

Link to the dataset: https://www.nomisweb.co.uk/census/2011/origin_destination
The UK government Office for National Stat # Welcome to Nomis

Nomis is a service provided by the Office for National Statistics, ONS, to give you free access to the most detailed and up-to-date UK labour market statistics from official sources.

Origin-destination data (also known as flow data) will include the travel-to-work and migration patterns of individuals, cross-tabulated by variables of interest (for example occupation). New products for the 2011 Census will also provide the migration patterns of those living at a student address one year ago and provide information on individuals with second residences.

##About the map
1. Download map data from Local Authority District https://geoportal.statistics.gov.uk/datasets/local-authority-districts-december-2019-boundaries-uk-bfc 
from the ONS Geoportal http://geoportal.statistics.gov.uk/
2. Open .shp file in Mapshaper https://mapshaper.org/
3. Export it to GeoJSON file

Library or Package needed
geopandas
pandas
matplotlib


Installation

    conda install geopandas































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
eyJoaXN0b3J5IjpbMTI1Nzk1MDI3MiwzMTEwOTk0NTIsMTQ1Mj
A4MDgzMywxNDUzNDk1NjAsLTE2ODE1ODQ2MDksLTE0OTU5OTAw
NjUsLTk1MTQ1NDMzMF19
-->