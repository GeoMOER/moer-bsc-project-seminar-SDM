---
title: 'Example: Workflow in R'
toc: yes
toc_label: In this example
---

This example provides a schematic workflow for processing vector and raster data in R. 



## Read in data 

### Raster data



First, we need to load a package to handle raster data in R, preferable `raster`.
If the package is not available, we need to install it first with `install.packages("raster")`.


```r
library("raster")
```

prec <- getData('worldclim', var='prec', res=10)

plot(prec[[1]])

ger <- getData('GADM', country='DE', level=0)
plot(ger, add=T)

?getData

getData('GADM', country='FRA', level=1)



```yaml
library("raster")
```


## vector manipul

xxx


## raster manipul

xx


## mapping

some maps


## write

get it out




## More information

 Rspatial, Lovelace, whatsoever






