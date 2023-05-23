---
title: Species distribution modelling
layout: splash
date: '2019-10-15 13:00:00 +0100'
header:
  overlay_color: "#000"
  overlay_filter: 0.6
  overlay_image: "/assets/images/titleimage/QGIS_Pakistan_2.png"
  caption: 'Photo: [Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
  cta_label: Go to course units
  cta_url: "/units.html"
excerpt: Get an overview of species distribution modelling techniques and use R for handling, modelling and visualizing geodata
feature_row_intro:
- excerpt: International course of the Department of [Physical Geography](https://www.uni-marburg.de/en/fb19/disciplines/physisch){:target="_blank"} at [Marburg University](https://www.uni-marburg.de/en){:target="_blank"}
feature_row_ilos:
- image_path: "/assets/images/envobs_ilos.jpg"
  alt: PC monitor laying in the garden of the institute.
  title: Intended learning outcomes
  excerpt: "Template..."
---

{% include feature_row id="feature_row_intro" type="center" %}

Species distribution modelling (SDM) is a key competence for ecogeographical research and applied nature conservation. 
It allows researchers to estimate current distributions of species and to also predict their future distributions under climate change scenarios.
SDM encompasses various area-wide spatial predictions techniques and requires profound skills related to organizing, handling, analyzing and visualizing geodata. 

By using the programming environment R, this course will open the door to the cosmos of SDM techniques and will provide a flexible baseline for workflow automation in various research projects. Special emphasis will be on R Markdown and GitHub for proper documentation and reproducibility. 


# Intended learning outcomes
At the end of this course you should be able to

* feel comfortable with the usage of R and GitHub,
* distinguish between and apply major SDM techniques,
* analyse, share and reproduce your spatial data with R Markdown,
* use open GIS to manage, visualize and georeference your spatial data,
* include and process remote sensing data in your workflow,
* learn how to implement a research project in a collaborative approach, and last but not least to
* critically evaluate your analyses and results.


# Course features

This course is intended as a blended learning module in our study program although the provided introductions, explanations and examples might be useful for self-study, too.
Given the enormous body of literature and methods available for SDM, it can only be an entry point for more sophisticated and project-specific modelling techniques.
Each course aims to create area-wide species distribution maps for a group of organisms and a particular area of the world for which hitherto no species richness maps exist.

This course will take place in the classroom (**F 14 | 00A12**). The first session will take place **on Tuesday 11.04.2023 at 09:15 am**.
Course material will be provided in the [Ilias course environment](https://ilias.uni-marburg.de/goto.php?target=crs_3203176){:target="_blank"} (only accessible for members of the course who are logged-in into Ilias). 
Please also seriously check and follow the [Information on the Coronavirus](https://www.uni-marburg.de/de/universitaet/administration/sicherheit/coronavirus){:target="_blank"} of the University of Marburg.
{: .notice--info}


# Course times

Tuesdays 09:15 - 13:45.


# Syllabus

| Session |  Date | Topic                        | Content                                                                          |
|---------|-------|------------------------------|----------------------------------------------------------------------------------|
||| **Basics** ||
| 01 | 11.04.2023 | The very basics              | Course introduction, expectations, organisational matters, R, R Studio, R Markdown, GitHub     |
| 02 | 18.04.2023 | More basics                  | Data types, object types, indexing, work environment, data input and output                    |
| ~~03~~ | ~~25.04.2023~~ | Session cancelled     |  |
| 04 | 02.05.2023 | Working with spatial data    | Raster data, vector data, coordinate reference systems, reading and writing spatial data, spatial operators, mapping |
| 05 | 09.05.2023 | SDM Basics                   | Why SDM?, applicability of SDM, ecological concepts, SDM modelling cycle. Student tutorial assignment                          |
||| **Exemplary SDM workflow**          ||
| 06 | 16.05.2023 | SDM workflow I               | Overview, conceptualisation, data processing which SDM packages and functions to choose?          |
| 07 | 23.05.2023 | SDM workflow II              | Model fitting, assessment, and predictions                                 |
||| **Student tutorials**           ||
| 08 | 30.05.2023 | Free working time             |   You can use the time of this session to work on your student tutorials and ask questions                                      |
| ~~09~~ | ~~06.06.2023~~ | Session cancelled        |                         |
| 10  | 13.06.2023 | SDM methods I                | Student tutorials presentations: Unbiased conditional inference forest (cforest), GLM mit Lasso penalty                                     |
| 11  | 20.06.2023 | SDM methods II              | Student tutorials presentations: Boosted Regression Trees                       |
| 12 | 27.06.2023 | SDM methods III               | Student tutorials presentations: XGboost, spatialMaxent                        |
| 13 | 04.07.2023| Built-in hold ||
||| **Synthesis**                                ||
| 14 | 11.07.2023 | Wrap up                      | Get and give feedback from your peers and instructors, tell us how you self-assess your skills, and happy holidays |





# Deliverables

The course certificate will be based on individual assignments written in R Markdown and published on GitHub.
Participants will prepare a graded student tutorial about an SDM method of their choice, which will be published on this page.




# Preparation and prerequisites

Basic knowledge of R and of handling spatial data is beneficial, but not required.
All software needed for this course is free and open source.

This course uses additionally provided material for teaching basic R skills, 
which can be found [here](https://geomoer.github.io/moer-base-r/){:target="_blank"}.
{: .notice--success}


# Team

{% for author in site.data.authors %} {% include author-profile.html %}
{% endfor %}


<!--
[Go to course units]({{ site.baseurl }}{% link _pages/units.md %}){: .btn .btn--success .btn--large .align-center}
-->


