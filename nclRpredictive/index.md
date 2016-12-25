---
layout: default
title: Predictive Analytics
---
# Predictive Analytics

This is a two day intensive course on using the R programming language for
predictive analytics. This course will be a mixture of lectures and computer
practicals. It will be assumed that participants are familiar with R. For
example inputting data, basic visualisation, basic data structures and use of
functions. Attending the introduction to R course will provide a sufficient
background.

See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * Introduction to analytics: a general introduction into analytics and some of the techniques that are in common use.
 * Simple regression problems: simple and multiple linear regression and model diagnostics.
 * Classification: KNN, clustering, logistic regression, Linear Discriminant analysis and associated diagnostics.
 * Model selection: various model selection procedures, subset selection, shrinkage.
 * Advanced regression techniques: polynomial regression, splines, local regression, GAMs, trees and random forests.


## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRpredictive")

The package can then be loaded via

    library("nclRpredictive")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * [Practical 3](practical3.pdf), [solutions](solutions3.pdf)
 * [Practical 4](practical4.pdf), [solutions](solutions4.pdf)

