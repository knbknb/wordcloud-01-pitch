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

<small>
The American Geophysical Union (AGU) is a professional society for Earth Scientists. Once a year, there is a big conference with more than 20000 participants from around the world.
This web-app creates Word Clouds from conference abstracts. Each word-cloud picture "summarizes the summaries" of hundreds of science talks and posters.
In doing so, this app enables users to get a quick overview of important topics, buzzwords and common themes within a certain research area. Many subfields of Earth Science are interesting, related to one's own specialty, but still unfamiliar because of their vastness, technicality and interdiciplinarity.
</small>

--- 

## Slide 4

Note: Only a small subset of conference contributions, grouped by topic, are made queryable in the UI below.

--- 

## Slide 5

