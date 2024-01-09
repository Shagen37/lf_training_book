--- 
title: "LANDFIRE Powered Assessments"
author: "The Nature Conservancy's LANDFIRE team"
site: bookdown::bookdown_site
documentclass: book
cover-image: "img/watch-me-diff-watch-me-rebase-smaller.png"
---

# Assess your landscape with LANDFIRE data: a beginner's guide {-}

<div class="figure">
<img src="img/watch-me-diff-watch-me-rebase-smaller.png" width="669" height="400" alt="Cover image" />
<p class="caption">Still from <a href="https://www.youtube.com/watch?v=uBWrpVrazzA">Heaven King video</a></p>
</div>

##Goals 
<!--Are these goals right? They don't follow the TOC/page structure. It would be cool if they did - we want a walkthrough like first we'll teach you this, then this, then this-->
Often a good way to start learning something is to jump in and take on a meaningful project. Here we show you how to take a shapefile of your area of interest, then:
  * Download and process multiple LANDFIRE datasets
  * Bring LANDFIRE data into ArcGIS pro, explore ways to make maps that follow Universal Design principles (i.e., easier for everyone to read)
  * Quantify and make charts of attributes of interest
  * Understand the basics of Biophysical Settings and Models
  
##Prerequisites
###The following software
  * ArcGIS Pro and basic abilities (e.g., starting a project, bringing in data)
  * Microsoft Excel (or similar) and/or [R](https://cran.rstudio.com/) and [R-Studio](https://posit.co/download/rstudio-desktop/)
  * SyncroSim <!--SH Note: I would love it if we had a whole page on this site that's just dedicated to how you end up where you need to be with SyncroSim. Not suggesting recreating their tutorials, but also acknowledging that I can never find what I need there as a novice and infrequent user and it's a frustrating experience.-->
  * Microsoft Word (or similar)

###Other
  * A shapefile of your area of interest
  * Internet acccess
  * Space to store data
  * Time and patience!
   
<!--I would love if we could reword this and include it somewhere in this page. We might also consider dividing this page into sub pages. I just feel like this info is great "here's who our target audience is, but others are welcome also. Here is what this thing is going to walk you through.-->

The target reader is someone who uses [ ] <!--fill in the blank--> <!--R for data analysis or who works on R packages-->, although some of the content may be useful to those working in adjacent areas.

The first two parts, [Installation](#install-intro) and [Connect Git, GitHub, RStudio](#connect-intro), provide a "batteries included" quick start to verify your setup.

In [Early GitHub Wins](#usage-intro), we rack up some early success with the basic workflows that are necessary to get your work onto GitHub. We also show the special synergy between R/R Markdown/RStudio and GitHub, which provides a powerful demonstration of why all this setup is worthwhile.

The use of Git/GitHub in data science has a slightly different vibe from that of pure software development, due to differences in the user's context and objective. Happy Git aims to complement existing, general Git resources by highlighting the most rewarding usage patterns for data science. This perspective on the Git landscape is presented in [Basic Git Concepts](#git-intro) and [Daily Workflows](#workflows-intro). 

