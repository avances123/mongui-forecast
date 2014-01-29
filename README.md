mongui-forecast
===============

Introduction
------------

This is proof of concept to forecast some geodiversity based in SRTMs, land cover data, and satellite precipitation measurements, makes use of postgis raster fundamentally.

As much as naive I can be, I want to forecast life appareance of one kind of mushroom wich shows up near my home town and is very apreciated by the locals. I know some characteristics they need to appear, they appear at some altitude, on a specific type of terrain, and they need several water on them followed to a warm period. Tipically for mushrooms I think.

Data sources
------------

### Elevation
* GeoTiff from [CGIAR](http://srtm.csi.cgiar.org/index.asp)
* UL:(-180º,60º) 
* LR:(180º,-60º)


### Land Cover
* GeoTiff from [glc2000](http://bioval.jrc.ec.europa.eu/products/glc2000/products.php)
* UL:(-180º,90º)
* LR:(180º,-56º)

### Precipitation
* GeoTiff from [TRMM](ftp://trmmopen.gsfc.nasa.gov/pub/gis/)
* UL:(-180º,50º)
* LR:(180º,-50º)

Data import
-----------

TODO raster2postgis
