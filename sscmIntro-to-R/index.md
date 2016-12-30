---
layout: default
title: Introduction to R
---
# Introduction to R
<p align="justify">
This is a one day intensive course on basics and fundamental concepts of R. The course is structured as a set of lecture sessions and computer practicals. It is suitable to a wide range of participants e.g., statisticians, biologists, clinicians and postgraduate students.
</p>

**No prior programming knowledge is assumend**.

## Course outline

 * What is R?: A brief overview of the concepts and features of the R statistical programming environment.
 * Help systems in R: A description of how to use different sources of R help.
 * Data types: A brief introduction to different data types in R including numeric, complex, character, factor and logical data.
 * Data structure: A summary of R's data structure including vectors, matrices, arrays, data frames and lists.
 * Importing data: Describing how to import, edit, save and export data of different formats from R including Excel, SPSS, STATA and SAS data files.
 * Data manipulation: A description of how to use logical operators to manipulate data.
 * Missing values: Describing how R handles missing values.
 * Visualisation: Creating, editing and saving graphics in various formats using R.
 
## Presenter
[Dr. Osama Mahmoud](http://www.osmahmoud.com){:target="_blank"}, Senior Research Associate (Research Statistician), School of Social and Community Medicine, University of Bristol, UK.
 
## Installing the R package (Temporarily Unavailable!)
The R package associated with this course is hosted by the
[drat repository](https://github.com/statcourses/drat){:target="_blank"}. Installing the package can be simply done by running the following code lines into your R session. 

```javascript
install.packages("drat")
drat::addRepo("statcourses")
install.packages("sscmRintro", type="source")
```
The package can then be loaded via

```javascript
library("sscmRintro")
```

<!--
## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * Plotting [cheatsheet](plotting.pdf)
-->