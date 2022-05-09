---
title: Species Distribution Modelling
layout: splash
date: '2019-10-15 13:00:00 +0100'
header:
  overlay_color: "#000"
  overlay_filter: 0.6
  overlay_image: "/assets/images/titleimage/QGIS_Pakistan_2.png"
  caption: 'Photo: [Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
  cta_label: Go to course units
  cta_url: "/units.html"
excerpt: Get an overview of species distribution modelling techniques, use R for handling, modelling and visualizing geo-datasets, and conjointly develop software for digitizing species distribution records
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

This course will take place in a hybrid setting (except for the first session) with a digital classroom and additional students being present in person in the physical classroom (**F 14 | 00A12**).
Details on this synchronous hybrid classroom format will be provided in the first session, which will take place **in presence only on Tuesday 19.04.2022 at 10:15 am**.
The link to the digital classroom will be provided in the [Ilias course environment](xxxx){:target="_blank"} (only accessible for members of the course who are logged-in into Ilias). 
Please also seriously check and follow the [Information on the Coronavirus](https://www.uni-marburg.de/de/universitaet/administration/sicherheit/coronavirus){:target="_blank"} of the University of Marburg.
{: .notice--info}


# Course times

Tuesdays 10:15 - 12:45.


# Syllabus

| Session |  Date | Topic                        | Content                                                                          |
|---------|-------|------------------------------|----------------------------------------------------------------------------------|
||| **Basics** ||
| 01 | 19.04.2022 | The very basics              | Course introduction, expectations, organisational matters, R, R Studio, R Markdown, GitHub     |
| 02 | 26.04.2022 | More basics                  | Data types, object types, indexing, work environment, data input and output                    |
| 03 | 03.05.2022 | Working with spatial data    | Raster data, vector data, coordinate reference systems, reading and writing spatial data, spatial operators, mapping |
| ~~04~~ | ~~10.05.2022~~ | Session cancelled        |                         |
| 05 | 17.05.2022 | SDM Basics                   | Why SDM?, applicability of SDM, ecological concepts, SDM modelling cycle. Student tutorial assignment                          |
||| **Digitizing distribution records**          ||
| 06 | 24.05.2022 | Software development I       | Project introduction, objectives, testing software for digitizing species records |
| 07 | 31.05.2022 | Software development II      | Work on projects                                                                  |
| 08 | 07.06.2022 | Applying the software        | Use the digitizer for extracting butterfly distribution records across Asia  |
| ~~09~~ | ~~14.06.2022~~ | Project week Department of Geography        | Session cancelled |
| 10 | 21.06.2022 | Merging                      | Merging all digitized data into one dataset |
||| **Species Distribution Modelling**           ||
| 11 | 28.06.2022 | SDM methods I                | Student tutorials presentations: Profile and regression methods                                 |
| 12 | 05.07.2022 | SDM methods II               | Student tutorials presentations: Machine learning methods, model averaging                      |
||| **Synthesis**                                ||
| 13 | 12.07.2022 | Wrap up                      | Get feedback from your peers and instructors, tell us how you self-assess your skills, and happy holidays |


# Deliverables

The course certificate will be based on individual assignments written in R Markdown and published on GitHub.
Participants will prepare a graded student tutorial about an SDM method of their choice, which will be published on this page.




# Preparation and prerequisites

Basic knowledge of R and of handling spatial data is beneficial, but not required.
All software needed for this course is free and open source.

This course uses additionally provided material for teaching basic R skills, 
which can be found [here](https://geomoer.github.io/moer-base-r/){:target="_blank"}.
{: .notice--success}


# Instructor
{% include author-profile.html %}

<!--
[Go to course units]({{ site.baseurl }}{% link _pages/units.md %}){: .btn .btn--success .btn--large .align-center}
-->


