Tufts Metadata Generator
========================

This project provides a Talend Job to generate ISO metadata from Geographical Files.


Requirements
------------

- Talend Studio version (5.6.0): http://sourceforge.net/projects/talend-studio/files/Talend%20Open%20Studio/5.6.0/

- Talend Spatial (5.4.0): http://sourceforge.net/projects/sdispatialetl/files/sdispatialetl/TOS.spatial.5.4.0/

- GDAL (http://trac.osgeo.org/gdal/wiki/DownloadingGdalBinaries)


Development
-----------

- Install the required applications/libraries

- Checkout the code

```
$ git clone git@eos.geocat.net:tufts/metadata_generator.git
```

- Open Talend Studio and import the folder metadata_generator, created in previous step.

For windows:

- Add to the ```PATH``` variable these values:

```
C:\Program Files\GDAL\
C:\Program Files\GDAL\java
```

- Define environment variable ```LD_LIBRARY_PATH``` with this value:

```
C:\Program Files\GDAL\java
```

For linux/mac:

- Add this in the advanced run tab of the process (set correct path):

```
-Djava.library.path=/path/to/gdal-1.9.1/swig/java
```

Build/Create intaller
---------------------

TODO