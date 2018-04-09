# EGU 2018 short course 

**"Building and maintaining R packages"** <br> Wed, 11 Apr, 13:30–15:00 / Room -2.16

## Welcome 

Welcome to the EGU 2018 short course on "Building and maintaining R packages". Michael Dietze and Sebastian Kreutzer may guide the course, but it will be driven by you, the audience. 

### The conveners 

Michael is a postdoctoral researcher at the [Geomorphology Section of GFZ Potsdam](https://www.gfz-potsdam.de/en/staff/michael-dietze/). He is working on environmental seismology (utilising the seismic signals emitted by geomorphic processes to constrain Earth surface dynamics) and has become an R enthusiast about ten years ago. He has developed and contributed about ten packages covering geomorphometry, geochronology, grain-size statistics, physical modelling and environmental seismology.

Sebastian is currently based in the luminescence group of the [IRAMAT-CRP2A](http://www.iramat-crp2a.cnrs.fr/) a ‘laboratoire d'excellence’ at the [Université Bordeaux Montaigne](http://www.u-bordeaux-montaigne.fr/fr/index.html) in France. He is a geographer, geochronologist specialised in luminescence dating and data scientist. He started working with R in 2011. Shortly later, in 2012, he introduced his first R package (‘Luminescence’), a powerful toolbox to handle luminescence data.
Today, he maintains two R packages and regularly co-authors the development of other R packages.

## Topcis covered

The course reaches out to advanced R users that work with **R** and *RStudio* on a  regular basis, and that have already developed their functions and perhaps recognised the increasing difficulty to adequately share their work and keep track of changes and dispersion.

In about 90 minutes we will justify the concept and contents of **R** packages, illustrate how R packages are initiated, how functions are added and how these functions are tagged and documented using 'roxygen2', a package for consistently forging code and documentation. We will show how to implement self-consistent tests, finally build the package, and share and maintain it using *Git*.

## Preparation

First of all, do yourself a favour and download the slides before the course starts. You can get the 4.2 MB large ZIP-file [here](https://github.com/R-Lum/EGU2018/blob/master/R_course_egu_2018.html.zip?raw=true). The ZIP-archive contains an HTML-file with the slides we will use in the course. 

Don't worry, we will not talk through all of the 99 slides. 

Second, and even more important, please make sure you have the following things installed at their latest version:

- R (version 3.4.4, download see [here](https://cloud.r-project.org)
- RStudio (version min. 1.0.143, download see [here](https://www.rstudio.com/products/rstudio/download/)
- Git (https://git-scm.com/downloads)
- R packages 
     + roxygen2 (version 6.0.1)
     + devtools (version 1.13.5)
     + testthat (version 2.0.0)
     
We will need all these items to run the course properly. We will **NOT** have time and resources (especially concerning the internet connection) to handle installations during the workshop.

## Evalulation

Not so much a prerequisite, but definitely an essential favour to improve the experience for future short courses. Please help us and fill a 3-4 minutes evaluation form [here](https://docs.google.com/forms/d/e/1FAIpQLSdbhcwH_-_qVA5OxJzYyRrEtbzdRF3yE49JAsAOFcYqKKCi5g/viewform).

Finally, it would help us significantly if you could start with a blank screen on *RStudio*, i.e., an empty workspace, no open files and no opened project. 


