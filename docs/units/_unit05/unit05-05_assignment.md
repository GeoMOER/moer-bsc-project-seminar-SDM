---
title: "Assignment: Detecting maps on scanned book pages"
header:
  image: '/assets/images/digitizer/digitizer_teaser_object_detection.png'
  caption: '[Environmental Informatics Marburg](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics){:target="_blank"}'
---

Now the time has come to test the digitizer for a specific task.
Let us assume that you already obtained a book with distribution maps, scanned it, stored it and preprocessed the data.
Then the next step would be to detect maps on the digital images of pages in that book.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/digitizer/digitizer_teaser_object_detection.png" alt="caption" class="full">
<figcaption> 
Step "Object detection" for detecting maps on scanned book pages in the workflow of the Digitizer.
</figcaption>

<br>
This is what the Digitizer should do for you, with a little training.


## Things you need for this assignment

* The installed and running Digitizer. The instructions for downloading and installing 
can be found [here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/installation.html){:target="_blank"}.

* The tutorial for how to detect maps on scanned book pages with template matching, 
which can be found [here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/tutorial.html){:target="_blank"}.

* Data for testing the Digitizer, 
which can be obtained [here](https://environmentalinformatics-marburg.github.io/distribution_digitizer_webpage/data.html) 
and will be individually assigned during the session.


## Deliverables

1. Find the real size in cm² of maps on your test images by trying several resolutions in dots per inch (DPI).
1. Find the maximum value for the threshold of template matching.
1. Most important: Write down everything you found to be annoying while using the Digitizer. 
Being honest is highly appreciated as it will help us improve the software. 
Also save error messages, which will help us with troubleshooting. 

We will collect and discuss the real size and threshold values with examples in the next session.
This assignment will NOT be marked.
{: .notice--info}



















