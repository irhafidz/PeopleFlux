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
https://stackoverflow.com/questions/35940880/how-to-compare-two-string-variables-in-pandas
https://github.com/keplergl/kepler.gl/tree/master/bindings/kepler.gl-jupyter

  

 


<!--stackedit_data:
eyJoaXN0b3J5IjpbNDY0NjU5NzU4LC0zMTkxNTI2MDEsNDcxMD
Y0MzIwLDEzMzE1MjA4NzUsMTQwNDQ2MDIyNywxOTAyNTMzNDI3
LC0yMDYwNzkzMzYyLC0xMTAxOTMwNjMsMTAyNTcyMzA2NywtMj
ExMjM1MzQ2OCwxMjU3OTUwMjcyLDMxMTA5OTQ1MiwxNDUyMDgw
ODMzLDE0NTM0OTU2MCwtMTY4MTU4NDYwOSwtMTQ5NTk5MDA2NS
wtOTUxNDU0MzMwXX0=
-->