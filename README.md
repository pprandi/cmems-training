# cmems-training
code repo for cmems training stuff

# how to install python on Windows
making this work is pretty straightforward on MacOS and Linux, but can be tricky on Windows, below is something that should work.
Any feedback is appreciated.

dowload anaconda2 from https://repo.continuum.io/archive/.winzip/

download and install netCDF4  https://www.unidata.ucar.edu/software/netcdf/ (http://www.unidata.ucar.edu/downloads/netcdf/ftp/netCDF4.4.1.1-NC4-64.exe)

download and install virtual studio 9.0 http://landinghub.visualstudio.com/visual-cpp-build-tools (https://www.microsoft.com/en-us/download/details.aspx?id=44266 )

dowload the Python netcdf4 package netcdf4-python-master from http://unidata.github.io/netcdf4-python/  and unzip it.

Edit the setup.cfg of python the netCDF4:
    netCDF4_dir = C:\Program Files\netCDF 4.4.1.1
and (for version 4.3.1 of anaconda2 and 3)
    HDF5_libdir = C:\Users\(username)\AppData\Local\Continuum\Anaconda3\Lib\site-packages\h5py
    HDF5_incdir = C:\Users\(username)\AppData\Local\Continuum\Anaconda3\Library\include

init an Anaconda, and run  
    > python setup.py build
    > python setup.py install

Dowlaod Basemap from http://matplotlib.org/basemap/users/download.html
for Python 2.7 you should get basemap-1.0.7.win-amd64-py2.7.exe ;
and execute it. 
