---
layout: operations
title: Raster

tutorial: operations
num: 2
---

#### Raster operations

Manipulation and processing of raster data is a large part of the GeoTrellis library. The approach taken to the organization of raster operations is in line with C. Dana Tomlin's Map Algebra, as detailed in the book [GIS and Cartographic Modeling](http://www.amazon.com/GIS-Cartographic-Modeling-Dana-Tomlin/dp/158948309X). Map Algebra breaks focal operations into three main categories:

- [**Local Operations**]({{site.baseurl}}/operations/raster/local.html): Local operations calculate resulting raster cell values based on the value at the same cell location in one or more input rasters.
- [**Focal Operations**]({{site.baseurl}}/operations/raster/focal.html): Focal operations calculate resulting raster cell values based on the values in a defined in a neighborhood around the same cell location in one or more input rasters.
- [**Zonal Operations**]({{site.baseurl}}/operations/raster/zonal.html): Zonal operations calcuate resulting raster cell values based on the values associated with that cell's zone in one or more input rasters.

**Note:** For each Operation that takes an input Raster and returns a Raster, the data type of the output Raster will be the same as the input Raster, unless otherwise noted.
