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
    jupyter labextension install @jupyter-widgets/jupyterlab-manager

### Installation NodeJS, KeplerGL
    conda install -c conda-forge nodejs
    pip install keplergl
https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html


  

 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMTIwMjQ5MzcsNDcxMDY0MzIwLDEzMz
E1MjA4NzUsMTQwNDQ2MDIyNywxOTAyNTMzNDI3LC0yMDYwNzkz
MzYyLC0xMTAxOTMwNjMsMTAyNTcyMzA2NywtMjExMjM1MzQ2OC
wxMjU3OTUwMjcyLDMxMTA5OTQ1MiwxNDUyMDgwODMzLDE0NTM0
OTU2MCwtMTY4MTU4NDYwOSwtMTQ5NTk5MDA2NSwtOTUxNDU0Mz
MwXX0=
-->