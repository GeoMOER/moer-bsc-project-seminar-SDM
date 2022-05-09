---
title: "Assignment: Spatial Data Processing"
header:
  image: '/assets/images/teaserimages/world_temp.png'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
---

This exercise will lead you through some of the most basic and important steps for spatial data processing.


## Things you need for this worksheet
  * [R](https://cran.r-project.org/){:target="_blank"} — the interpreter can be installed on any operation system.
  * [RStudio](https://www.rstudio.com/){:target="_blank"} — we recommend to use R Studio for (interactive) programming with R.
  * [Git](https://git-scm.com/downloads){:target="_blank"} environment for your operating system.
  * An internet connection for downloading raster and vector data (~5mb).



## Spatial Data Processing

1) Create a map of your country of residence with the following features:

- a raster background map showing elevation data,
- a vector map showing the country boundary,
- use the vector map to clip the raster map,
- map point locations denoting the places of residence of the course participants in your country (if any), 
which you can enter [here](https://hessenbox.uni-marburg.de/getlink/fiWHwceuGtJ4tYNNJ2gZd8Ye/participant_locations.xlsx){:target="_blank"}
(use a `SpatialPointsDataFrame` object with the correct CRS for this task),
- map the three largest cities of your selected country with different symbols, and
- get bonus points by adding a legend, rivers, and other cartographic elements as well as
- the distances of the places of residence to Marburg.

Use the code provided in the tutorial "Example: Workflow in R" from the previous page for this task.
Save your R functions and Rmd file in your course repository, knitr it, update (i.e. commit) your local repository and publish (i.e. push) it to the GitHub classroom. 
Make sure that the created html file is also part of your GitHub repository and also include the text of each task prior to your solutions.
Also make sure that the created map does not exceed 2mb file size.
{: .notice--info}


2) Create your first HTML tutorial

Create your own markdown-based HTML tutorial for task 1), but this time avoid using functions from the packages sp and raster.

This assignment will 
a) get you ready for the more extensive student tutorials later in the course an will 
b) additionally prepare yourself for the end of life of the packages sp and raster, with which you have to deal in the future.

Do not use functions from the packages sp and raster for this task.
Save your R functions and Rmd file in your course repository, knitr it, update (i.e. commit) your local repository and publish (i.e. push) it to the GitHub classroom. 
Make sure that the created html tutorial file is also part of your GitHub repository. 
You may copy the text in the tutorial "Example: Workflow in R" from the previous page for this task.
{: .notice--info}






