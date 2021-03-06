### Installing KeplerGL from Windows 10

I learn about [KeplerGL](https://kepler.gl/) on a webinar from [DSF Lunch](https://www.datasciencefestival.com/event/dsf-lunch-learn-visualising-location-data-with-keplergl/) but got stuck with the KeplerGL installation. Read from a lot of source, turns out according to [this medium article](https://medium.com/@rschoudhary1999/installing-fiona-on-windows-10-for-keplergl-6af2628b6fc5) I need to:

get [Fiona](https://pypi.org/project/Fiona/) correctly.

What is Fiona? According to their github page:

> Fiona **reads and writes** geographic data files and thereby helps Python programmers integrate geographic information systems with other computer systems. Fiona **contains extension modules** that link the Geospatial Data Abstraction Library (GDAL).

I decided to [re-do all what Choudary already did](https://medium.com/@rschoudhary1999/installing-fiona-on-windows-10-for-keplergl-6af2628b6fc5).

 **1. Learning about Fiona requirement & dependencies**
Fiona has its dependency that stated in its docs/ documentation page:

> Fiona requires `Python versions 3.6+`  
> `GDAL version 1.11–3.0.` 
> Fiona depends on the modules `enum34, six, cligj, munch, argparse,` and `ordereddict` (the two latter modules are standard in Python
> 2.7+). Pip will fetch these requirements for you, but users installing Fiona from a Windows installer must get them separately.

**2. Check your Python Architecture version**
Check your Python architecture (just to make sure):

   

     import platform as p
     print(p.architecture())
     ('64bit', 'WindowsPE')


**3. Download the appropriate GDAL version as your Python architecture (mine is 64bit)**

Go to the GDAL website release [here](http://www.gisinternals.com/release.php) and download the Windows 64 bit. I picked the MSVC2017 x64 and it will be redirect [to the other page](http://www.gisinternals.com/query.html?content=filelist&file=release-1911-x64-gdal-2-4-4-mapserver-7-4-3.zip). Download GDAL version that is in appropriate with your python architecture. There are 4 download files:

 

> - Compiled binaries in a single .zip package (1st row)
>  - Compiled libraries and headers (3rd row)
>  - Installer for the GDAL python bindings (requires to install the GDAL core): my Python version is 3.7 so I pcked
> [GDAL-2.4.4.win-amd64-py3.7.msi](http://download.gisinternals.com/sdk/downloads/release-1911-x64-gdal-2-4-4-mapserver-7-4-3/GDAL-2.4.4.win-amd64-py3.7.msi)
> (3rd last from below)
>  - Installer for the GDAL ECW 3.3 plugin (must be installed to the same directory as the GDAL core, the 3.3 and 5.x versions cannot be
> installed side by side) (last row) After download all the 4 files, do
> the installation.

**4. Installation**

Install GDAL core and then GDAL python binding from msi installers.

**5 Adds GDAL environment variables**
-   GDAL is installed at:  `C:\Program Files (x86)\GDAL\`or `C:\Program Files\GDAL\` (mine is the later)
-   Add `path, gdal_data, gdal_driver_path` to our environment variables:

`PATH`: C:\Program Files\GDAL

`GDAL_DATA`: C:\Program Files\GDAL\gdal-data

`GDAL_DRIVER_PATH`: C:\Program Files\GDAL\gdalplugins

Check the `GDAL_VERSION` in Anaconda terminal and paste the version in a new environment:

    (base) C:\Users\Hafidz>gdalinfo --version
    GDAL 2.3.3, released 2018/12/14

**6. Install Fiona**

Install the Fiona library that has Windows binaries according to your python specification from https://www.lfd.uci.edu/~gohlke/pythonlibs/#fiona `cd` to the `.whl file directory`. Remember, do not forget to install the Fiona dependencies: `enum34, six, cligj, munch, argparse,` and `ordereddict`. 

Redirect to the place where I put the `.whl file download` and then run using `pip install`:

     C:\Users\Hafidz>`pip install Fiona-1.8.13-cp37-cp37m-win_amd64.whl`


https://github.com/benfred/implicit/issues/91
https://medium.com/@rschoudhary1999/installing-fiona-on-windows-10-for-keplergl-6af2628b6fc5

https://github.com/Toblerity/Fiona/issues/220
https://jingwen-z.github.io/how-to-install-python-module-fiona-on-windows-os/

https://github.com/benfred/implicit/issues/76
https://github.com/benfred/implicit/issues/91
https://jingwen-z.github.io/33-things-to-know-about-pandas-dataframe/
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg3NjY1NjY0OSwtMTI1MjE1NTQ3MiwxNj
UyNzQwNzgwXX0=
-->