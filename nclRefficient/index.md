---
layout: default
title: Efficient R programming
---

# Efficient R programming


This is a one day intensive course on efficient R programming. This course will
be a mixture of lectures and computer practicals.This course is aimed at anyone
who uses R, but wants tips and techniques on speeding up their code.

Prior knowledge: it will be assumed that participants are familiar with R. For
example, inputting data, basic visualisation and data frames. Attending the
introduction to R will be sufficient. This course is suitable to a wide range of
applicants e.g. biologists, statisticians, engineers, students.

See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * Why is your code slow? Code profiling: which part of the code should you optimise.
 * Efficient data structures: object growth and memory allocation.
 * Avoiding loops: accessing the underlying C code faster.
 * Parallel computing: an introduction to multi-core computing.

## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRefficient", type="source")

The package can then be loaded via

    library("nclRefficient")

## Vignettes

The package contains the following vignette

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
