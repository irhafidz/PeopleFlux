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

Python Architecture version

    import platform as p
    print(p.architecture())
    ('64bit', 'WindowsPE')

Download the appropriate GDAL version as your Python architecture (mine is 64bit)

Go to the GDAL website release [here](http://www.gisinternals.com/release.php) and download the Windows 64 bit 
 

  
5. Download GDAL version that is in appropriate with your python architecture







<!--stackedit_data:
eyJoaXN0b3J5IjpbMzI1NTk3MTgyLDU3NDI1NDA5NywtMjI1Nz
k3MjI4LC0xNTQ2MjEzNTQxLC03NTc4NzAxLDk5ODEzMjYxNSwx
MDQ5NDU2NjA4LDEwMTc1MDYxMCwtMTYwMzU0OTg2NiwxMDIzNz
M5MjM2LC0xOTA0ODQ0NTM0XX0=
-->