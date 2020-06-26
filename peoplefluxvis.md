https://github.com/irhafidz/PeopleFlux


### Installing KeplerGL from Windows 10

I learn about [KeplerGL](https://kepler.gl/) on a webinar from [DSF Lunch](https://www.datasciencefestival.com/event/dsf-lunch-learn-visualising-location-data-with-keplergl/) but got stuck with the KeplerGL installation. Read from a lot of source, turns out I need to:

get [Fiona](https://pypi.org/project/Fiona/) correctly.

What is Fiona? According to their github page:

> Fiona **reads and writes** geographic data files and thereby helps Python programmers integrate geographic information systems with other computer systems. Fiona **contains extension modules** that link the Geospatial Data Abstraction Library (GDAL).

Fiona has its dependency that stated in its docs/ documentation page:

> Fiona requires `Python versions 3.6+`  
> `GDAL version 1.11–3.0.` 
> Fiona depends on the modules `enum34, six, cligj, munch, argparse,` and `ordereddict` (the two latter modules are standard in Python
> 2.7+). Pip will fetch these requirements for you, but users installing Fiona from a Windows installer must get them separately.

The thing is, 








<!--stackedit_data:
eyJoaXN0b3J5IjpbNTc0MjU0MDk3LC0yMjU3OTcyMjgsLTE1ND
YyMTM1NDEsLTc1Nzg3MDEsOTk4MTMyNjE1LDEwNDk0NTY2MDgs
MTAxNzUwNjEwLC0xNjAzNTQ5ODY2LDEwMjM3MzkyMzYsLTE5MD
Q4NDQ1MzRdfQ==
-->