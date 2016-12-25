---
layout: default
title: Introduction to R
---
# Introduction to R

This is a one day intensive course on R. This course will be a mixture of
lectures and computer practicals. The main focus will be to introduce
fundamental R concepts. No prior programming knowledge of any kind is assumed.
This course is suitable for a wide range of applicants e.g., biologists,
statisticians, engineers, students.

See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * Introduction to R: A brief overview of the background and features of the R statistical programming system.
 * Entering Data: A description of how to import and export data from R.
 * Data types: A summary of R's data types.
 * R environment: A description of the R environment including the R working
   directory, creating/using scripts, saving data and results.
 * R Graphics: Creating, editing and storing graphics in R.
 * Manipulating data in R: Describing how data can be manipulated in R using logical operators.


## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRintroduction", type="source")

The package can then be loaded via

    library("nclRintroduction")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * Plotting [cheatsheet](plotting.pdf)
