https://github.com/irhafidz/PeopleFlux


### Installing KeplerGL from Windows 10

I learn about [KeplerGL](https://kepler.gl/) on a webinar from [DSF Lunch](https://www.datasciencefestival.com/event/dsf-lunch-learn-visualising-location-data-with-keplergl/) but got stuck with the KeplerGL installation. Read from a lot of source, turns out I need to:

get [Fiona](https://pypi.org/project/Fiona/) correctly.

What is Fiona? According to their github page:

> Fiona **reads and writes** geographic data files and thereby helps Python programmers integrate geographic information systems with other computer systems. Fiona **contains extension modules** that link the Geospatial Data Abstraction Library (GDAL).

Fiona has its dependency that stated in its docs/ documentation page:

> Fiona requires `Python versions 3.6+`   `GDAL version 1.11–3.0.` 
> Fiona depends on the modules `enum34, six, cligj, munch, argparse,`
> and `ordereddict` (the two latter modules are standard in Python
> 2.7+). Pip will fetch these requirements for you, but users installing Fiona from a Windows installer must get them separately.






<!--stackedit_data:
eyJoaXN0b3J5IjpbOTk5MTYyNjk4LC0xNTQ2MjEzNTQxLC03NT
c4NzAxLDk5ODEzMjYxNSwxMDQ5NDU2NjA4LDEwMTc1MDYxMCwt
MTYwMzU0OTg2NiwxMDIzNzM5MjM2LC0xOTA0ODQ0NTM0XX0=
-->