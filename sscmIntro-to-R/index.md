---
layout: default
title: Introduction to R
---
# Introduction to R

This is a one day intensive course on basics and fundamental concepts of R. The course is structured as a cobmination of lecture sessions and computer practicals.

    No prior programming skills are required
    
This course might be benfecial for a wide range of participants e.g., statisticians, biologists, clinicians and postgraduate students.

## Course outline

 * What is R?: A brief overview of the concepts and features of the R statistical programming environment.
 * Help systems in R: A description of how to use different sources of R help.
 * Data types: A brief introduction to different data types in R including numeric, complex, character, factor and logical data.
 * Data structure: A summary of R's data structure including vectors, matrices, arrays, data frames and lists.
 * Importing data: Describing how to import, edit, save and export data of different formats from R including Excel, SPSS, STATA and SAS data files.
 * Data manipulation: A description of how to use logical operators to manipulate data.
 * Missing values: Describing how R handles missing values.
 * Visualisation: Creating, editing and saving graphics in various formats using R.
 
## Installing the R package

The R package associated with this course is located in the
[drat repository](https://github.com/statcourses/drat). Installing the package can be simply done by running the following code lines into your R session. 

```javascript
install.packages("drat")
drat::addRepo("statcourses")
install.packages("sscmRintro", type="source")
```
The package can then be loaded via

    library("sscmRintro")

<!--
## Vignettes

The package contains the following vignettes

 * [Practical 1](practical1.pdf), [solutions](solutions1.pdf)
 * [Practical 2](practical2.pdf), [solutions](solutions2.pdf)
 * Plotting [cheatsheet](plotting.pdf)
-->