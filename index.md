---
title       : Fighting Information Overload 
subtitle    : with Word Clouds
author      : Knut Behrends, Sept. 2014
logo        : Screenshot-shinyapp-wordclouds.png
job         : Reproducible Pitch Presentation for Online Course 'Developing Data Products'
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Slide 2
### Information Overload in the STEM Sciences

- There is more scientific literature produced than can be possibly read
- A staggering 6,000 papers are published every day 
- Source: [Nature News & Comment, Sept. 3, 2014](http://www.nature.com/news/how-to-tame-the-flood-of-literature-1.15806)

###  Information Overload in small subfields of sciences

- Even a single big conference releases an overwhelming amount of information
- Let's develop a new tool to tame this
- Stategy: Interactively summarize the summaries

--- 

## Slide 3
### My Shiny App: Word Clouds

- it visualizes the most common phrases used in conference abstracts, AGU Fall Meeting 2012
- Each word-cloud picture "summarizes the summaries" of hundreds of science talks and posters.

- Example: 



--- 

## Slide 4

### The American Geophysical Union (AGU) 

- is a professional society for Earth Scientists. 
-  Once a year, there is a big conference with more than 20000 participants from around the world.

- Over the years, number of participants has increased considerably.

<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />





--- 

## Slide 5

- Only a small subset of conference contributions, grouped by topic, are made queryable in the UI of the app.

- Data was gathered by manual screen-scraping 
- Tidying up data took much more  time than creating the shiny app.
