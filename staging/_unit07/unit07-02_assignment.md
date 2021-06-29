---
title: "Assignment: Execute the Digitizer"
header:
  image: '/assets/images/digitizer/digitizer_teaser_georeferencing.png'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
---

Now the time has come to execute the Digitizer and run object detection and pixel classification.
This worksheet will also introduce you to georeferencing.


## Things you need for this assignment

### Software

- [QGIS](https://www.qgis.org/en/site/){:target="_blank"}
- In QGIS:
  - A connection to data from [Open Street Map](https://www.openstreetmap.org/){:target="_blank"}
  - The [GDAL Georeferencer plugin](https://docs.qgis.org/3.16/en/docs/user_manual/working_with_raster/georeferencer.html)
  
### Data

- High resolution tiff files of your example pages will be provided by the instructors


## Tasks

1. Perform object detection with template matching on tiff files for extracting all maps in your example book (output: files of clipped maps in one folder).
Delete unwanted maps in the output folder of object detection afterwards (output: cleaned files of clipped maps in one folder).
1. Do pixel classification for all those remaining maps (output: files with maps showing masked occurrence points).
1. Georeference five of those output maps


Note that the tasks for this assignment are described in more detail in the 
tutorial part of the [Digitizer webpage](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/tutorial.html){:target="_blank"}.
Also watch the recording of the session if anything is unclear.
{: .notice--info}




## Deliverables

Upload one output image for each assignment task in your GitHub classroom repository.


Note that you will need to gather considerably more information to solve this task than provided in the input parts of this course.
{: .notice--info}



<!--


### Other
  
* Use EPSG 102025 as projection in QGIS.
* The url to the Open Street Map server is https://tile.openstreetmap.org/{z}/{x}/{y}.png
* Our tutorial on how to do georeferencing can be found [here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/tutorial.html){:target="_blank"}.


  - QGIS
    - Install
    - Watch some QGIS Introduction video
    - Install add-ons
      - openstreetmap
      - georeferencer
        - Maybe watch some georeferencing tutorial
  - Install Python 3.6 (maybe this gets installed with the installation of QGIS already?)

-->
















