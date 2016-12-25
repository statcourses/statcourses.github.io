---
layout: default
title: Advanced graphics
---

# Advanced graphics

This is a one day intensive course on advanced graphics with R. The standard plotting commands in R are known as the Base graphics. In this course, we cover more advanced graphics packages - in particular, ggplot2. The ggplot2 package can create very advanced and informative graphics. For example:

 * [Mapping electrical activity in the human
   neocortex](https://github.com/hadley/ggplot2/wiki/Mapping-electrical-activity-in-the-human-neocortex)
 * [Strainmeter offsets](https://github.com/hadley/ggplot2/wiki/Strainmeter-offsets:-real-or-spurious)
 * [Analysis of music](https://github.com/hadley/ggplot2/wiki/Bach-2-Part-Invention-in-F-Major-BWV779)

A basic knowledge of R is assumed for this course. In particular, attendees
should be familiar with the topics covered in the first course.This course will
be a mixture of lectures and computer practicals. The goal is to enable
participants to apply the techniques covered to their own data. This course is
suitable to a wide range of applicants e.g., biologists, statisticians,
engineers, students.

See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * The grammar of graphics
 * Mastering the grammar
 * Groups, geoms, stats and layers
 * Scales, axes and legends
 * Facets
 
## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRggplot2", type="source")

The package can then be loaded via

    library("nclRggplot2")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * [Practical 3](practical3.pdf), [solutions](solutions3.pdf)
