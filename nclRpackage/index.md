---
layout: default
title: Building an R package
---
# Building an R package

This is a one day intensive course on building an package. This course will be a
mixture of lectures and computer practicals. The main focus will be getting a
working R package ready for distribution. It is assumed that all applicants have
a basic knowledge of R.

## Course outline

Participants can bring their own code or they can use the provided example code
to write a fully functional R package.

 * Why create an R package.
 * What is in an R package.
 * Writing documentation with roxygen.
 * Creating packages with rstudio.
 * Distributing your package.

## Installing the R package

The package is located in the
[drat repository](https://github.com/rcourses/drat). Installing the package is
straightforward

    install.packages("drat")
    drat::addRepo("rcourses")
    install.packages("nclRpackage", type="source")

The package can then be loaded via

    library("nclRpackage")

## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)

