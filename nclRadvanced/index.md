---
layout: default
title: Advanced R programming
---
# Advanced R Programming

This is a two day intensive course on R. The course will be a mixture of
lectures and computer practicals. The main focus of the course is advanced R
programming techniques, such as S3/S4 objects, reference classes and function
closures.

The course follows on from the [Programming with R course](/nclRprogramming). It
is assumed that all students have attended this course (or have equivalent
skills). This course is suitable to a wide range of applicants e.g. biologists,
statisticians, engineers, students.

## Course Outline

 * Functions: 
   - Scoping rules (including lexical scope)
   - The ... argument
   - Functions as first class objects
   - Functions closures and mutable states
   - Argument matching
 * Customising your workspace:
   - The Rprofile and Renviron files
 * Dealing with errors:
   - Messages, warnings and errors
   - Using try and tryCatch effectively
 * S3 classes: 
   - Introduction to object oriented programming
   - Constructing S3 objects
   - Drawbacks
 * S4 and reference classes: 
   - Creating and using S4 and reference classes
   - Differences between S3 and S4
   
## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRadvanced", type="source")

The package can then be loaded via

    library("nclRadvanced")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * [Practical 3](practical3.pdf), [solutions](solutions3.pdf)
 * [Practical 4](practical4.pdf), [solutions](solutions4.pdf)  
