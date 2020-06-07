# PeopleFlux

## About dataset

The dataset is from https://www.nomisweb.co.uk/census/2011/origin_destination Nomis is an open access data from the Office for National Statistics (ONS) for UK labour market statistics from official sources.
The dataset name is RF03EW - Location of usual residence and place of work. 

## Creating Map

1. Download map data from Local Authority District https://geoportal.statistics.gov.uk/datasets/local-authority-districts-december-2019-boundaries-uk-bfc 
from the ONS Geoportal http://geoportal.statistics.gov.uk/
2. Open .shp, .prj, .dbf file in Mapshaper https://mapshaper.org/
3. Simplify the map
4. Export it to GeoJSON file

The Notebook requires `pandas`, `geopandas`, `geoplot`, and `mapclassify` to run. Other library I need to install: `descartes`
 
You'll also need to install [NodeJS](https://nodejs.org/en/download/) and set up some notebook widgets if you want to render Kepler in your notebook. Full instructions for KeplerGL [are here](https://github.com/keplergl/kepler.gl/tree/master/bindings/kepler.gl-jupyter).
 1. geopandas  
 2. pandas
 3. matplotlib
 4. descartes
 5. mapclassify

## Making a Map: Plotting a basic map

## Vis using KeplerGL


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg4NzYyOTk2MywxNDA0NDYwMjI3LDE5MD
I1MzM0MjcsLTIwNjA3OTMzNjIsLTExMDE5MzA2MywxMDI1NzIz
MDY3LC0yMTEyMzUzNDY4LDEyNTc5NTAyNzIsMzExMDk5NDUyLD
E0NTIwODA4MzMsMTQ1MzQ5NTYwLC0xNjgxNTg0NjA5LC0xNDk1
OTkwMDY1LC05NTE0NTQzMzBdfQ==
-->