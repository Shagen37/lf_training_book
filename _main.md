--- 
title: "Assess your landscape with LANDFIRE"
author: "The Nature Conservancy's LANDFIRE team"
site: bookdown::bookdown_site
github-repo: rswaty/lf_training_book
description: "Map and quantify historical and current vegetation on your landscape with LANDFIRE data."
twitter-handle: 
url: 'https\://happygitwithr.com/'
cover-image: img/sign.jpg
---

## Background

[LANDFIRE](https://landfire.gov/index.php) products are extremely useful for natural resource managers, allowing users to complete many tasks, including these that are featured in this website:

![Historical ecosystems map.](img/bps.jpg){style="float:right; margin-left: 25px;" fig-alt="\"Historical ecosystems map of a large region in the western United States." fig-align="right" width="250" }

* Mapping and quantifying historical ecosystems (see map below made with [LANDFIRE's Biophysical Settings data](https://landfire.gov/bps.php))
* Mapping and quantifying existing vegetation type, height and cover
* Comparing reference and current amounts of ecosystem succession classes


While useful, effectively working with LANDFIRE products can be intimidating due to terminology, GIS processing and data wrangling often required.

Additionally, the "fire-hose" of information can pose a problem. Where is a user to start?

## Goals

Often a good way to start learning something is to jump in and take on a meaningful project. Here we show you how to take a shapefile of your area of interest, then:

* Download and process multiple LANDFIRE datasets
* Bring LANDFIRE data into ArcGIS pro, explore ways to make maps that follow Universal Design principles (i.e., easier for everyone to read)
* Quantify and make charts of attributes of interest
* Understand the basics of Biophysical Settings and Models

## Prerequsites

### The following software
* ArcGIS pro, and basic abilities (e.g., starting a project, bringing in data)
* Microsoft Excel (or similar) and/or [R](https://cran.rstudio.com/) and [R-Studio](https://posit.co/download/rstudio-desktop/)
* SyncroSim
* Microsoft word (or similar)

### Other
* A shapefile of your area of interest
* Internet access
* Space to store data
* X# hours




<!--chapter:end:index.Rmd-->

---
title: "BpS Descriptions"
author: "Randy Swaty"
date: "2024-01-03"
output: html_document
---


## Randy's Notes on this page

**Downloading and understanding BpS descriptions**

* going over a BpS document is a great way to not only help people understand BpS, but also to introduce spatial datasets:
    * BpS 
    * EVT though s-class rule table (where we get lifeform)
    * EVC and EVH-rule table
    * S-class--look at succession class descriptions to understand what "A" means in an addtional way (in addtion to s-class table)
* demo downloading BpS descriptions
* describe key features/sections of document
* link to Blankenship et al 2021

<!--chapter:end:bps-description.Rmd-->

---
title: "BpS Models"
author: "Randy Swaty"
date: "2024-01-03"
output: html_document
---

## Randy's notes on this page


* set folks up to explore BpS models (link to veg modeling page, etc.)

## SyncroSim

Where to get.


<!--chapter:end:bps-model.Rmd-->

---
title: "Getting LANDFIRE data"
author: "Randy Swaty"
date: "2024-01-03"
output: html_document
---


## The four ways to download LANDFIRE Spatial Data

LANDFIRE provides three ways to download spatial data:

1. Using the [LANDFIRE Map Viewer](https://www.landfire.gov/viewer/)
2. Downloading CONUS, Hawaii, Alaska or insular area-wide data
3. Streaming the data with a webservice

Additionally, [Mark Buckner](https://markabuckner.com/) has created the [rlandfire](https://github.com/bcknr/rlandfire) package, which allows for direct downloading of LANDFIRE data into an R environment.

For this tutorial we will use option 1, downloading data via the LANDFIRE Map Viewer (LMV).

<!--chapter:end:data-ways.Rmd-->

---
title: "Explore the spatial data"
author: "Randy Swaty"
date: "2024-01-03"
output: html_document
---


## Randy's notes

* explore attribute tables of each dataset
* discuss different attributes of EVT and BpS 
* limitations of sclass data 

<!--chapter:end:gis-explore.Rmd-->

---
title: "Make a map"
author: "Randy Swaty"
date: "2024-01-03"
output: html_document
---


## Randy's notes

### accessibility

* link to Sarah's videos
* highlight challenges

### different maps

* EVT
* EVC or EVH

<!--chapter:end:gis-map.Rmd-->

