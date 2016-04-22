---
title       : An easy to use tool for generating random normal numbers
subtitle    : Day to day tools for the datascientist
author      : Raymond Theodore Usher Vargas
job         : data scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      #
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The need
Commonly for testing your models and doing various **data scientist** stuff you will need some random numbers generated in an easy to use way.

This is exactly what this product does it generates numbers with an easy to use UI.

--- .class #id

## Have you ever ...

Have you ever executed the following code snippet in your R Console


```r
rnorm(10, mean=5, sd=50)
```

```
##  [1]  37.478471 -19.039657  -5.495918  31.748407  -8.691460 104.409755
##  [7]  62.782240 -36.349235  63.985138  33.261522
```

Surely you have, because the previous code is commonly used, due to the relevance of normal distribution.

--- .class #id

## Behind the scenes

Behind the scenes all that is happening is an execution of

```r
rnorm(sampleSize, mean=mean, sd=mean)
```
but with a browser interface wich make it supper accesible and user friendly, making the usage a breeze.

--- .class #id

## What we offer
<br/>
A super easy to use tool that you will certantly use in your day to day use in data science, with a web ui so you can access it anywhere you might need random normal numbers. 
