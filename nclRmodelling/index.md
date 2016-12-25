---
layout: default
title: Statistical modelling 
---

# Statistical modelling with R

This is a one day intensive course on modelling in R. This course will be a
mixture of lectures and computer practicals.

Prior knowledge: it will be assumed that participants are familiar with R. For
example, inputting data, basic visualisation and data frames. Attending the
introduction to R courses will provide a sufficient background. This course is
suitable to a wide range of applicants e.g., biologists, statisticians,
engineers, students.

See the [R course](http://www.ncl.ac.uk/maths/rcourse/) for booking details. 

## Course outline

 * Basic hypothesis testing: examples include one-sample t-test, one-sample
   Wilcoxon signed-rank test, independent two-sample t-test, Mann-Whitney test,
   two-sample t-test for paired samples, Wilcoxon signed-rank test.
 * ANOVA tables: 1-way and 2-way tables.
 * Simple and multiple linear regression: including model diagnostics.
 * Clustering: hierarchical clustering, kmeans.
 * Principal components analysis: plotting and scaling data

## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRmodelling", type="source")

The package can then be loaded via

    library("nclRmodelling")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
