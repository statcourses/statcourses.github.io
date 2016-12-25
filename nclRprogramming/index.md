---
layout: default
title: Programming with R
---
# Programming with R

This is a one day intensive course on R. The course will be a mixture of
lectures and computer practicals. The main focus of the course is R programming
techniques, such as functions, for loops and conditional expressions.

The course follows on from the Introduction to R course. It is assumed that all
students have attended this course (or have equivalent skills). This course is
suitable to a wide range of applicants e.g., biologists, statisticians,
engineers, students.


See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * Vector operations: details of R's vectors operations.
 * Conditionals: using "if" and "else" statements in R
 * Functions: what is function is, how are they used, and how can we construct our own functions.
 * Looping in R: an introduction to the concept of looping in R. In particular "for" and "while" loops.
 * The apply functions: apply, tapply and other members of the apply family.

## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRprogramming", type="source")

The package can then be loaded via

    library("nclRprogramming")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * [Practical 3](practical3.pdf), [solutions](monopoly_solutions.pdf)

