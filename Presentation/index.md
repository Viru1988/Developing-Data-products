---
title       : Developing Data Products-Project Presentation
subtitle    : 
author      : Vijay anand M
job         : Software Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Project BackGround

This application is created using Shiny and hosted in Shinyapps.IO. This presentation is developed as part Developing data products course and helps reader to understand the application easily.The tools used to build this application and presentation are,

* Data Product application built on Shiny
* Slidify is used to create the presentation.

---

## Application Overview

   I have used MTCARS dataset to do a small manipulation on it. This Dataset provide information about the list of cars and their milegage based on Per Gallon.This assignment helped us to ensure which cars provides more milage with repect to various parameters.
Now this application has been deployed in this link,https://vijayanand.shinyapps.io/Developing-Data-products

* This application allows the users to check the milage based on various parameters.
* The Parameters used in this application are Cylinder,Transmission,Gear.

---

## Data Overview

The Data for this project has been otained from inbuilt datasets in the Rstudio itself. MTCARS is the dataset used for this project.
This dataset was used by us in various coursera courses.

The source code for this application can be obtained from Github,
https://github.com/Viru1988/Developing-Data-products

---

## Data Processing


```r
dt<-mtcars
head(dt)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```


---

Thank you
---


