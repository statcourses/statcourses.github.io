---
layout: default
title: Clustering and classification with applications in R
---
# Clustering and classification with applications in R
<p align="justify">
This is a one day intensive course on statistical learning techniques. The course is structured as a set of lecture sessions and computer practicals. The main focus is to introduce cluster analysis (unsupervised learning) and classification (supervised learning) approaches. This course might be benfecial for a wide range of participants e.g., statisticians, bioinformaticians, data scientists, engineers and postgraduate students.
</p>

## Prerequisite
<p align="justify">
This course assumes all participants have <strong>basic knowledge of R programming</strong>, as covered by the <a href="{{ site.baseurl}}/sscmIntro-to-R">'Introduction to R'</a> and <a href="{{ site.baseurl}}/sscmRprogramming">'Programming using R'</a> courses (or equivalent skills). <strong>Basic concepts in statistics, in particular correlation and linear regression techniques</strong> are also assumed.
</p>

## Course outline

 * Multivariate concepts: Introducing basic statistical notions of multivariate analysis, such as covariance, correlation and Euclidean distance.
 * Similarity measures: A brief summary of various measurements of similarity and its calculations using R.
 * k-means clustering: Introducing concepts of k-means clustering, visualising resulted clusters and discussing applications using R.
 * Hierarchical clustering: Discussing different linkage methods of hierarchical clustering, agglomerative schemes and additive trees with their applications in R.
 * Logistic regression: Introducing logistic regression technique for binary classification problems with R.
 * Bayes classifier and LDA: Some other classification techniques included the Bayes classifier and linear discriminant analysis are covered.
 * Misclassifications: Presenting methods for estimating missclasification error rates for a classifier model using R.
 * CART & Random forest: A description of tree based classifiers and introduction to the random forest approach and its usage in R.

## Presenter
[Dr. Osama Mahmoud](http://www.osmahmoud.com){:target="_blank"}, Senior Research Associate (Research Statistician), School of Social and Community Medicine, University of Bristol, UK.

[Prof. Berthold Lausen](https://www.essex.ac.uk/maths/staff/profile.aspx?ID=1277){:target="_blank"}, Professor of Statistics and Head of Department of Mathematical Sciences, University of Essex, UK.
 
## Installing the R package
The R package associated with this course is located in the
[drat repository](https://github.com/statcourses/drat){:target="_blank"}. Installing the package can be simply done by running the following code lines into your R session. 

```javascript
install.packages("drat")
drat::addRepo("statcourses")
install.packages("essexBigdata", type="source")
```
The package can then be loaded via

```javascript
library("essexBigdata")
```