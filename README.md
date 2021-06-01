# Data Access: Webscraping with R

Data Science Summer School
July 20, 2021

* Instructor: [Rochelle Terman](http://rochelleterman.com/), rterman@uchicago.edu

* TA: Pete Cuppernull

* Time: TBD


### Overview

This short course teaches students how to extract, store, and process data from the Internet using the R statistical programming language. Students will learn how to collect internet data in a variety of forms, including application programming interfaces (APIs) and scraping the open web. We will assume students have basic knowledge of R and RStudio. Participants with no prior experience with R are encouraged to complete this brief tutorial (requiring 2-3 hours) to learn the basics of R before the course.

### Objectives 

This course is geared towards social scientists who work with are interested in extracting, processing, and analyzing data from the internet. By the end of the course, participants will:

1.  Understand basic legal and ethical issues surrounding web scraping.
2.  Collect data via RESTful APIs:
    * Master key principles and concepts of RESTful APIs.
    * Use plug-n-play R packages for popular APIs such as Twitter, Google Translate, and others.
    * Write a custom API query to extract data from RESTful APIs, such as the New York Times Article API.
3.  Collect data via web scraping:
    * Understand how HTML & CSS work to display a website.
    * Inspect a website using Google Developer Tools and SelectorGadget to understand its underlying structure and identify elements.
    * Write a program that scrapes multiple webpages using R.
4.  Clean, transform, and wrangle data using `tidyverse` packages.

### Prerequisites

Students must have basic computer skills, must be familiar with their computer’s file system, and must be comfortable entering commands in a command line environment. 

The workshop will also assume basic knowledge of the R programming language. Participants with no prior experience with R are strongly encourged to complete [this brief tutorial](https://www.codeschool.com/courses/try-r) to learn basics of R before the course.

### Software Required

See the [tech requirements page](A-Tech-Requirements.md) for detailed information on the software we'll be using. Please download and install **before coming to the workshop.** If you have difficulties installing, please contact Rochelle at rterman@uchicago.edu

### Materials

All course notes will be available on GitHub, including class notes, code demonstrations, sample data, etc. 

Download the materials on your computer by running the following code in RStudio. Note that for this to work, you will need to have installed `tidyverse` installed.

```
# install tidyverse if you haven't already done so.
install.packages("tidyverse")

library("usethis")
use_course("rochelleterman/webscraping-R")
```

### Contact

Rochelle Terman, Assistant Professor in Political Science, University of Chicago
rterman@uchicago.edu

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).


