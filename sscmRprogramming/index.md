---
layout: default
title: Programming using R
---
# Programming using R
<p align="justify">
This is a one day intensive course on R programming techniques. The course is structured as a set of lecture sessions and computer practicals. It mainly covers the basic programming tools in R, such as functions and control structures, i.e. conditional expressions and loops. This course might be benfecial for a wide range of participants e.g., statisticians, biologists, clinicians and postgraduate students.
</p>

## Prerequisite
<p align="justify">
<strong>This course is a follow-on from the <a href="{{ site.baseurl}}/sscmIntro-to-R">'Introduction to R'</a> course</strong>. Both courses together, "Introduction to R" and this course, form a series titled '<em>Mastering Data Analysis & Visualisation Using R</em>'. <u>It is assumed that all participants have the knowledge covered by the former course</u>.
</p>

## Course outline

 * Functions: What is an R function?, how are they structured and used?, how can one understand function's parameters and how can we create our own functions?
 * Control Structures: Describing how we include control structures into R code.
 * Conditional expressions: Using "if" and "ifelse" structures in R.
 * Loops: Introcuding looping techniques in R, with particular focus on "for", "repeat" and "while" statements.
 * "apply" family: using "apply", "lapply", "tapply", "mapply" and "sapply" in R.

## Presenter
[Dr. Osama Mahmoud](http://www.osmahmoud.com){:target="_blank"}, Senior Research Associate (Research Statistician), School of Social and Community Medicine, University of Bristol, UK.
 
## Installing the R package
The R package associated with this course is located in the
[drat repository](https://github.com/statcourses/drat){:target="_blank"}. Installing the package can be simply done by running the following code lines into your R session. 

```javascript
install.packages("drat")
drat::addRepo("statcourses")
install.packages("sscmRprogramming", type="source")
```
The package can then be loaded via

```javascript
library("sscmRprogramming")
```