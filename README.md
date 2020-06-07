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
 
## Making a Map: Plotting a basic map

## Vis using KeplerGL
To use KeplerGL, I need to install [NodeJS](https://nodejs.org/en/download/), set up some notebook widgets to render Kepler in jupyter notebook. Full instructions for KeplerGL [listed here](https://github.com/keplergl/kepler.gl/tree/master/bindings/kepler.gl-jupyter).

### Prerequisites

 - Python >= 2 
 - ipywidgets >= 7.0.0
 
**Installation for ipywigdets**

    conda install -c conda-forge ipywidgets
    conda install -n base -c conda-forge widgetsnbextension

### Installation NodeJS, KeplerGL
    conda install -c conda-forge nodejs
    pip install keplergl


  

 


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTUwMTg3MzExNiw0NzEwNjQzMjAsMTMzMT
UyMDg3NSwxNDA0NDYwMjI3LDE5MDI1MzM0MjcsLTIwNjA3OTMz
NjIsLTExMDE5MzA2MywxMDI1NzIzMDY3LC0yMTEyMzUzNDY4LD
EyNTc5NTAyNzIsMzExMDk5NDUyLDE0NTIwODA4MzMsMTQ1MzQ5
NTYwLC0xNjgxNTg0NjA5LC0xNDk1OTkwMDY1LC05NTE0NTQzMz
BdfQ==
-->