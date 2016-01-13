---
layout: post
title: "Lesson 01: The Spatial Data Landscape"
date:   2015-10-29
authors: [Dave Roberts, Tracy Teal, Kaitlin Stack Whitney, Leah Wasser, Megan A. Jones]
contributors: [ ]
dateCreated: 2015-10-23
lastModified: 2016-01-12
packagesLibraries: [ ]
category: [self-paced-tutorial] 
tags: [R, GIS-Spatial-Data, informatics]
mainTag: spatial-data-management-series
description: "Add description here."
code1: 01-spatial-data-landscape.R
image:
  feature: NEONCarpentryHeader_2.png
  credit: A collaboration between the National Ecological Observatory Network (NEON) and Data Carpentry
  creditlink: http://www.neoninc.org
permalink: R/spatial-data-landscape
comments: false
---

{% include _toc.html %}

##About
Add description.

**R Skill Level:** Intermediate - you've got the basics of `R` down.

<div id="objectives" markdown="1">

#Goals / Objectives

After completing this activity, you will:

* Be aware of a variety of tools that can be used to access spatial data. 


##Things You’ll Need To Complete This Lesson
To complete this lesson: you will need the most current version of R, and 
preferably RStudio, loaded on your computer.

###Install R Packages

* **NAME:** `install.packages("NAME")`

* [More on Packages in R - Adapted from Software Carpentry.]({{site.baseurl}}R/Packages-In-R/)

###Download Data


****

{% include/_greyBox-wd-rscript.html %}

**Raster Lesson Series:** This lesson is part of a lesson series introducing
[spatial data and data management in `R` ]({{ site.baseurl }}tutorial/URL).
It is also part of a larger 
[spatio-temporal Data Carpentry Workshop ]({{ site.baseurl }}workshops/spatio-temporal-workshop)
that includes working with  
[raster data in `R` ]({{ site.baseurl }}tutorial/spatial-raster-series),
[vector data in `R` ]({{ site.baseurl }}tutorial/spatial-vector-series)
and  
[tabular time series in `R` ]({{ site.baseurl }}tutorial/tabular-time-series).

****

###Additional Resources
For a list of tools to work with spatial data, visit:
* Wikipedia's <a href="http://en.wikipedia.org/wiki/List_of_geographic_information_systems_software" target="_blank" GIS software page. >
* Wikipedia's <a href="http://en.wikipedia.org/wiki/List_of_spatial_analysis_software" target="_blank" spatial analysis software page. >

</div>


##This lesson overviews Gui vs Non Gui tools, interactive vs non-interactive (nice graphic could go a long way here)

##Gui Tools - Brief Description of this and a few examples of available tools. BRIEF discussion of why coding is potentially more reproducible compared to gui workflows

###Pay: Arcgis

###Open / Free: QGIS, Grass (maybe a line on each and a link to each page

##Non Gui Tools

###R

###Python

###Matlab

###Benefits: Reproducible workflows, more easily documented (inline comments, etc)

##Overview of commonly found spatial data formats -- essentially one line about this with a link to the spatial data formats page.

###Shapefiles (.shp, dbf, etc - group of files )

###Geodatabases (.gdb, ??)

###Csv’s (.csv)

###text files: rasters (.asc) -- essentially one line about this with a link to the spatial data formats page.

###Online: geojson,

##Packages specific to R - with link to the setting up your work environment page

###Raster

###RGDAL

###RasterVis


