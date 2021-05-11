---
title: Biodiversity data
header:
  image: '/assets/images/teaserimages/digitizer_teaser.jpg'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
---

Remember that all SDM approaches have a similar generic workflow, but now let us focus on the part called "Biodiversity data":


<img src="{{ site.url }}{{ site.baseurl }}/assets/images/zurell/zurell_scheme_mod.png" alt="caption" class="full">
<figcaption> 
"The five main steps in the species distribution modelling cycle. Source: Zurell et. al 2020, https://doi.org/10.1111/ecog.04960. Modified."
</figcaption>


## Biodiversity data?

The most important component of "biodiversity data" for operating SDMs is information on the _occurrence of species._
In particular, it is digital raster or vector data on the spatio-temporal coordinates of species in the real word.
Note that occurrence records are always sampled in the field as point records but are often processed to and subsequently available as gridded data (occupied grid cells or atlas data) or polygons (species ranges), which has to be taken into account when working with spatial data.


Of course, there is and should be a lot of additional information related to the occurrence of species, 
like taxonomic reference system, ecological level, 
biodiversity data sources, sampling design, sample size per taxon, country/region mask, 
details on scaling, data cleaning/filtering, absence data collection, pseudo-absence and background data, 
potential errors and biases in data (all from Zurell et al. 2020),
but the use of biodiversity data in SDM ultimately boils down to the digital numbers of coordinates of species in geographical space.


## Occurrence records

It can be a long way from field sampling to feeding digital occurrence data into an SDM, 
depending on how these data are made available for further usage.
If you sampled your occurrence records yourself, you are in a nice position because you know your data and have direct access to it.
However, as a matter of fact, you will likely not have sufficient data (remember the Wallacean shortfall) because thorough sampling needs many people in a community effort and campaign (if you do not dedicate your life to collecting occurrence records, what might be a nice option, too).

The majority of natural history data on the occurrence of species still is hidden within analogous sources and is thus not directly available for SDM,
e.g. in museum collections, herbaria, private collections, and books.
However, there are ongoing efforts to overcome this problem and mobilize those data to be publicly available in digital data source.
You can find some examples below.


## Digital data sources

* Global Biodiversity Information Facility: [GBIF](http://data.gbif.org){:target="_blank"}
* Ocean Biodiversity Information System: [OBIS](http://iobis.org){:target="_blank"}
* Natural History Museum London: [Data portal](https://data.nhm.ac.uk/){:target="_blank"}



