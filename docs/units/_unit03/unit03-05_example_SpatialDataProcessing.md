---
title: 'Example: Workflow in R'
toc: yes
toc_label: In this example
---

This example provides a schematic workflow for processing vector and raster data in R. 



## Read in data 

### Raster data

Firstly, we import some raster data into our working environment
Therefore, we need to load a package to handle raster data in R, preferable `raster`.
If the package is not available, we need to install it first with `install.packages("raster")`.


```r
library("raster")
```

We now can use the function `getData()` to download some raster data: In this example a global map of precipitation values at 10 minutes spatial resolution.


```r
prec <- getData("worldclim", var="prec", res=10)
``` 


Fortunately, the downloaded data already have a correct CRS:


```r
## class      : RasterStack 
## dimensions : 900, 2160, 1944000, 12  (nrow, ncol, ncell, nlayers)
## resolution : 0.1666667, 0.1666667  (x, y)
## extent     : -180, 180, -60, 90  (xmin, xmax, ymin, ymax)
## crs        : +proj=longlat +datum=WGS84 +ellps=WGS84 +towgs84=0,0,0 
## names      : prec1, prec2, prec3, prec4, prec5, prec6, prec7, prec8, prec9, prec10, prec11, prec12 
## min values :     0,     0,     0,     0,     0,     0,     0,     0,     0,      0,      0,      0 
## max values :   885,   736,   719,   820,   955,  1850,  2088,  1386,   904,    980,    893,    914 
``` 


... and can be quickly and simply visualized with `plot()`. Note that the object type is a `RasterStack` with 12 layers, one for each month of the year.

```r
plot(prec$prec1)
```


<img src="{{ site.baseurl }}/assets/images/map_prec1_global.png" style="display: block; margin: auto;" />



### Vector data

Secondly, we add some vector data to our working environment. For example the administrative boundaries of France at the country level:


```r
fra <- getData('GADM', country='FRA', level=0)
```

Fortunately, also these downloaded data already have a correct CRS:

```r
## class       : SpatialPolygonsDataFrame 
## features    : 1 
## extent      : -5.143751, 9.560416, 41.33375, 51.0894  (xmin, xmax, ymin, ymax)
## crs         : +proj=longlat +datum=WGS84 +no_defs +ellps=WGS84 +towgs84=0,0,0 
## variables   : 2
## names       : GID_0, NAME_0 
## value       :   FRA, France 
```


<img src="{{ site.baseurl }}/assets/images/map_france_GADM.png" style="display: block; margin: auto;" />



# Hier weiter


plot(fra, add=T)


## Vector Operations

Clip and Crop.


## Raster operations


Calculate annual precipitation map.


## Mapping

Combine layers to single map.


## Write out

Write out in some format.




## More information

For more details see [www.rspatial.org](https://www.rspatial.org/raster/spatial/index.html){:target="_blank"} and 
[Geocomputation with R](https://geocompr.robinlovelace.net/spatial-operations.html#spatial-vec){:target="_blank"}



