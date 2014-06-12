---
title       : Reproducible Pitch Presentation
subtitle    : Coursera Developing Data Products
author      : Dave Padgitt
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Goals of Project

1. Learn the basics of Shiny and shinyapps.io
2. Continue gaining proficiency with Slidify & Github
3. Develop & Deploy a Shiny application/documentation
4. Share the application link, server.R and ui.R code

### Project Sub-goals

1. Attemp to build on previous project, namely Reproducible Research
2. Delve deeper into exploring the (NOAA) storm database
3. Meet the minimum project requirements

--- 

## Project Strategy

1. Utilize the geographical map functionality in library(maps)
2. Plot basic geographical data from NOAA data set
3. Include an interactive widget: selectInput()

--- 

## Basic use of library(maps)


```r
library(maps)
library(mapproj)
map("state", col = "black", fill = FALSE, projection = "polyconic")
```

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1.png) 


--- 

## Conclusion

1. library(maps) is a simple/easy way to add geographical map functionality in R
2. Some of the NOAA data lends itself well to geographic plotting
3. This project attained its goals!

