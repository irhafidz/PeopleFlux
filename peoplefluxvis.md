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

Go to the GDAL website release [here](http://www.gisinternals.com/release.php) and download the Windows 64 bit. I picked the MSVC2017 x64 and will be redirect [to the other page](http://www.gisinternals.com/query.html?content=filelist&file=release-1911-x64-gdal-2-4-4-mapserver-7-4-3.zip).
 

  
5. Download GDAL version that is in appropriate with your python architecture







<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMTM5NDc4MSwzMjU1OTcxODIsNTc0Mj
U0MDk3LC0yMjU3OTcyMjgsLTE1NDYyMTM1NDEsLTc1Nzg3MDEs
OTk4MTMyNjE1LDEwNDk0NTY2MDgsMTAxNzUwNjEwLC0xNjAzNT
Q5ODY2LDEwMjM3MzkyMzYsLTE5MDQ4NDQ1MzRdfQ==
-->