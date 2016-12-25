---
layout: default
title: Programming using R
---
# Programming using R
This is a one day intensive course on R programming techniques. The course is structured as a set of lecture sessions and computer practicals. It mainly covers the basic programming tools in R, such as functions and control structures, i.e. conditional expressions and loops.

This course might be benfecial for a wide range of participants e.g., statisticians, biologists, clinicians and postgraduate students.

## Prerequisite
THIS COURSE IS AN INTEGRATED PART FOR THE [INTRODUCTION TO R](sscmIntro-to-R) COURSE. IT IS ASSUMED THAT ALL PARTIIPANTS HAVE THE KNOWLEDGE COVERED BY THAT COURSE.

## Course outline

 * Functions: What is an R function?, how are they structured and used?, how can one understand function's parameters and how can we create our own functions?
 * Control Structures: Describing how we include control structures into R code.
 * Conditional expressions: Using "if" and "ifelse" structures in R.
 * Loops: Introcuding looping techniques in R, with particular focus on "for", "repeat" and "while" statements.
 * "apply" family: using "apply", "lapply", "tapply", "mapply" and "sapply" in R.

## Presenter
[Dr. Osama Mahmoud](http://www.osmahmoud.com), Senior Research Associate (Research Statistician), School of Social and Community Medicine, University of Bristol, UK.
 
## Installing the R package
The R package associated with this course is located in the
[drat repository](https://github.com/statcourses/drat). Installing the package can be simply done by running the following code lines into your R session. 

```javascript
install.packages("drat")
drat::addRepo("statcourses")
install.packages("sscmRprogramming", type="source")
```
The package can then be loaded via

```javascript
library("sscmRprogramming")
```