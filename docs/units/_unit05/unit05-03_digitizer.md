---
title: The Digitizer
header:
  image: '/assets/images/teaserimages/digitizer_teaser.jpg'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
toc: true
---


## Project introduction

### General setting

The geographical distribution of species is the most crucial piece of information for any kind of biodiversity research. 
Knowledge on species distributions and occurrence localities allows researchers to mechanistically
connect functional traits of species with abiotic properties of the environment, what lies at the heart of any
ecogeographical study (Lomolino et al. 2010). Moreover, understanding how and why Earth’s biodiversity is
distributed as we observe it today will allow to better predict consequences of climate change on ecosystem
functions and services that humans depend upon (Urban et al. 2016).

### Potential

The upcoming digital era opens up unprecedented opportunities for mobilizing and processing those
geographical distribution data of species that hitherto is unavailable for researchers because it is hidden in
thousands of analogue books (La Salle et al. 2016, Nelson & Ellis 2019). The project proposed here aims at
opening up this treasure trove by creating an open-source software toolbox for automatically digitizing
species data from analogue books. In particular, the project will implement processing routines for
extracting the geographical distributions of species from analogue maps. It will furthermore lay the foundation
for extending the software toolbox by text-mining routines for the exploitation of information hidden within
printed text and by deep-learning routines for the exploitation of functional traits hidden within images of
species. Last but not least, a user-friendly software front end will be developed to ensure broad applicability
of the created processing routines.


### Realization

In its initial version, the digitization tool will implement a consecutive series of steps for automatically creating
georeferenced files of distribution ranges from analogue input maps. The book series
“The Butterflies of Palearctic Asia” by Vadim Tshikolovets (e.g. Tshikolovets 1998, 2000, 2003, 2005a, 2005b;
Tshikolovets et al. 2009; Tshikolovets & Nekrutenko 2012) will serve as input data for testing and validating the
software toolbox. The created data will be combined to form the first comprehensive large-scale
collection of distribution data for butterflies in Asia, what will be a powerful basis for future
ecogeographical analyses by the applicant during his career. All books in the book series will be scanned
and stored by the digitization office of the University of Marburg as has already been agreed and cleared for
potential copyright issues. A series of preprocessing steps will then be implemented to prepare the digital
pages for the subsequent step of object detection by machine learning methods. 

The detected objects, in particular maps, text and images, can each be assigned to a specific processing branch
to finally mobilize the hidden analogue data within those object types. For convenience and to ensure a
successful realization of the full stack software development, we will first focus on the extraction of digital
distribution data from the detected maps. The users of the software will have the opportunity to chose from
several pixel classification methods to mask distribution records and background on the detected maps. 
Once the pixels of the distribution data are classified in the detected maps, the user will
input ground control points to automatically project and georeference all input maps into a geographical
coordinate system in a batch processing step. Contour fitting methods will be provided for the users in order
to vectorize the georeferenced raster information into several potential output file formats. Finally,
the quality of the output will be validated by comparison with some of the original data used by V.
Tshikolovets as well as with already available manually digitized distribution data from different sources.


{% include pdf pdf="Boost_table_1.pdf" %}
<figcaption>
Details of the consecutive steps that will be implemented by the proposed software toolbox for
automatically digitizing species distribution data from analogue books.
</figcaption>


## Project homepage

The project homepage can be found 
[here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/){:target="_blank"} (under construction..).


## References

La Salle, J., Williams, K.J. & Moritz, C. (2016) Biodiversity analysis in the digital era. Philosophical
Transactions of the Royal Society B: Biological Sciences, 371, 20150337.

Lomolino, M.V., Riddle, B.R., Whittaker, R.J. & Brown, J.H. (2010) Biogeography, 4th edn. Sinauer
Associates Publishers, Sunderland, Massachusetts.

Nelson, G. & Ellis, S. (2019) The history and impact of digitization and digital data mobilization on
biodiversity research. Philosophical Transactions of the Royal Society B: Biological Sciences, 374,
20170391.

Stelbrink, P., Pinkert, S., Brunzel, S., Kerr, J., Wheat, C.W., Brandl, R. & Zeuss, D. (2019) Colour lightness of
butterfly assemblages across North America and Europe. Scientific Reports, 9.

Tshikolovets, V. V. (1998) The Butterflies of Turkmenistan. Brno, Publ. Konvoj Ltd., pp. 1-237.

Tshikolovets, V. V. (2000) The Butterflies of Uzbekistan. Kyiv-Brno, Publ. by the author, pp. 1-400.

Tshikolovets, V. V. (2003) The Butterflies of Tajikistan. Kyiv–Brno, Publ. by the author, pp. 1-500.

Tshikolovets, V. V. (2005a) The Butterflies of Kyrgyzstan. Kyiv-Brno, Publ. by the author, pp. 1-500.

Tshikolovets, V. V. (2005b) The Butterflies of Ladak (N.-W. India). Kyiv-Brno, Publ. by the author, pp. 1-176.

Tshikolovets, V. V., Yakovlev, R. V., Bálint, Z. (2009) The Butterflies of Mongolia. Kyiv-Pardubice, Publ. by V.
Tshikolovets, pp. 1-320.

Tshikolovets, V. V., Nekrutenko, Y. P. (2012) The Butterflies of Caucasus and Transcaucasia (Armenia, Azerbaijan,
Georgia and Russia). Pardubice, Publ. by V. Tshikolovets, pp. 1-544.

Urban, M.C., Bocedi, G., Hendry, A.P., Mihoub, J.-B., Peer, G., Singer, A., Bridle, J.R., Crozier, L.G., De
Meester, L., Godsoe, W., Gonzalez, A., Hellmann, J.J., Holt, R.D., Huth, A., Johst, K., Krug, C.B., Leadley,
P.W., Palmer, S.C.F., Pantel, J.H., Schmitz, A., Zollner, P.A. & Travis, J.M.J. (2016) Improving the forecast for
biodiversity under climate change. Science, 353, aad8466–aad8466.





