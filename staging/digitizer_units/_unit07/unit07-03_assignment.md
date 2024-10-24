---
title: "Assignment: Execute the Digitizer"
header:
  image: '/assets/images/digitizer/digitizer_teaser_output.png'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
toc: true
---

Use the updated version of the Digitizer for detecting occurrence records on maps with pixel classification, transfer them to geographical space, 
produce classified and georeferenced output files, and extract the coordinates of the occurrence records. 


## Things you need for this assignment

### Software

- The Digitizer (available [here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/){:target="_blank"})
- QGIS (available [here](https://www.qgis.org/en/site/){:target="_blank"})
- In QGIS:
  - A connection to data from [Open Street Map](https://www.openstreetmap.org/){:target="_blank"}
  - The [GDAL Georeferencer plugin](https://docs.qgis.org/3.16/en/docs/user_manual/working_with_raster/georeferencer.html)
  

### Tutorial

The updated tutorial for executing the Digitizer can be found on the [Digitizer webpage](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/tutorial.html){:target="_blank"}.


### Data

- High resolution tiff files of your assigned book will be provided by the instructors, [here](http://85.214.102.111/data/books_full/){:target="_blank"}.




## Which book to choose?


Book title                                                       | Folder name | International participant   | German participant |
-----------------------------------------------------------------|-------------------------------------------|--------------------|
The Butterflies of Altai, Sayans and Tuva 			 | book_02     | Hanny Lidetu Solomon        | Daniel Bothe       |
The Butterflies of Russian Far East, Sakhalin, and Kuril Islands | book_03     | Lidet Mehari Mulatu         | Mona Hallenberger  |
The Butterflies of Mongolia 					 | book_04     | Tesfanesh Feseha Ashagre    | Leander Heyer      |
The Butterflies of Transbaikal Siberia 				 | book_05     | Bezawit Genanaw Alemayehu   | Katharina Kunstman |
The Butterflies of Tajikistan 					 | book_06     | Haseeb Kamran               | Sascha Lüer        |
The Butterflies of Kazakhstan 					 | book_07     | Maria Riaz                  | Luis Maecker       |
The Butterflies of Kyrgyzstan 					 | book_08     | M. Anwar-ul-Haq             | Jens Meyer         |
The Butterflies of Uzbekistan 					 | book_09     | M. Majid Ijaz               | Jan-Niklas Tripp   |
The Butterflies of Caucasus and Transcaucasia 			 | book_10     | Muhammad Farooq             |                    |
The Butterflies of Iran and Iraq 				 | book_11     | Mazhar Hussain              |                    |
The Butterflies of Ladak 					 | book_12     | Uneeba Shahid               |                    |
The Butterflies of Pakistan 					 | book_13     | Muhammad Hamza Khan         | Gabriel Behnke     |
The Butterflies of Afghanistan 					 | book_14     | Zain Umer                   | Mohammed Ahmed     |
-----------------------------------------------------------------|-------------|-----------------------------|--------------------|






## Assignment tasks

Use the Digitizer to execute the following steps with all .tif images from your assigned book:

1) Set your working directory

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/1_working_directory.png)

2) Create templates for detecting the maps and symbols on it

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/2_templates.png)

3) Use the created templates for detecting maps and writing them to disc

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/3_detect_maps.png)

4) Classify the points on these maps

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/4_classify_points.png)

5) Georeference those classified maps

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/5_georeferencing.png)

6) Postprocess those georeferenced maps

![Digitizer Interface]({{site.baseurl}}/assets/images/shiny/steps/6_postprocessing.png)




Do not get confused with old versions of the Digitizer. 
The most up-to-date version of the software and how to use it can be found on the [Digitizer webpage](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/){:target="_blank"}.
{: .notice--info}




## Deliverables

* Upload the content of the Digitizer's data/output/georeferencing/ folder into your GitHub Classroom repository. 
Note that this might be quite large (~300 x 3MB). If your encounter internet upload problems, contact Madhu for sharing it outside of GitHub.

* Please create a new folder for all content called "assignment_4" for this task in your repository


Please also open at least one issue for reporting problems or potential improvements on the Issues page of the Digitizer GitHub repository.
You can find this page [here](https://github.com/environmentalinformatics-marburg/distribution_digitizer_students/issues){:target="_blank"}).
{: .notice--warning}





This assignment will NOT be marked.
(You need to deliver it for passing the course, though.)
{: .notice--info}








<!--


### Other
  
Book title 									                     | Original name        | Folder name |   Participant             |
-----------------------------------------------------------------|----------------------|-----------------------------------------|
The Butterflies of Turkmenistan 				                 | 2020_suprascan_00030 | book_01     | Mohammed Ahmed            |
The Butterflies of Altai, Sayans and Tuva 			             | 2020_suprascan_00031 | book_02     | Hanny Lidetu Solomon      |
The Butterflies of Russian Far East, Sakhalin, and Kuril Islands | 2020_suprascan_00032 | book_03     | Lidet Mehari Mulatu       |
The Butterflies of Mongolia 						             | 2020_suprascan_00033 | book_04     | Tesfanesh Feseha Ashagre  |
The Butterflies of Transbaikal Siberia 				             | 2020_suprascan_00034 | book_05     | Bezawit Genanaw Alemayehu |
The Butterflies of Tajikistan 						             | 2020_suprascan_00036 | book_06     | Haseeb Kamran             |
The Butterflies of Kazakhstan 					                 | 2020_suprascan_00038 | book_07     | Maria Riaz                |
The Butterflies of Kyrgyzstan 						             | 2020_suprascan_00042 | book_08     | M. Anwar-ul-Haq           |
The Butterflies of Uzbekistan 					                 | 2020_suprascan_00043 | book_09     | M. Majid Ijaz             |
The Butterflies of Caucasus and Transcaucasia 				     | 2020_suprascan_00044 | book_10     | Muhammad Farooq           |
The Butterflies of Iran and Iraq 					             | 2020_suprascan_00045 | book_11     | Mazhar Hussain            |
The Butterflies of Ladak 						                 | 2020_suprascan_00047 | book_12     | Uneeba Shahid             |
The Butterflies of Pakistan 						             | 2020_suprascan_00049 | book_13     | Muhammad Hamza Khan       |
The Butterflies of Afghanistan 					                 | 2020_suprascan_00050 | book_14     | Zain Umer                 |
-----------------------------------------------------------------|----------------------|-------------|---------------------------|

-->

