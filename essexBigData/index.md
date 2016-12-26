---
layout: default
title: Clustering and classification with applications in R
---
# Clustering and classification with applications in R
<p align="justify">
This is a one day intensive course on statistical learning techniques. The course is structured as a set of lecture sessions and computer practicals. The main focus is to introduce cluster analysis (unsupervised learning) and classification (supervised learning) approaches.  Using R, participants will analyse real as well as example data sets and compute estimates of the misclassification rate, of the area under the receiver-operating characteristic (ROC) and of other relevant measurements. This course might be benfecial for a wide range of participants e.g., statisticians, bioinformaticians, data scientists, engineers and postgraduate students.
</p>

## Prerequisite
<p align="justify">
This course assumes all participants have <strong>basic knowledge of R programming</strong>, as covered by the <a href="{{ site.baseurl}}/sscmIntro-to-R">'Introduction to R'</a> and <a href="{{ site.baseurl}}/sscmRprogramming">'Programming using R'</a> courses (or equivalent skills). <strong>Basic concepts in statistics, in particular correlation and linear regression techniques</strong> are also assumed.
</p>

## Course outline

 * Multivariate concepts: Introducing basic statistical notions of multivariate analysis, such as covariance, correlation and Euclidean distance.
 * Similarity measures: Various measurements of similarity are discussed and applied in R.
 * k-means clustering: Concepts of k-means clustering and its visualising solutions are covered.
 * Hierarchical clustering: Linkage methods, agglomerative hierarchical clustering and additive trees are presented and applied in R.
 * Logistic regression: Introducing logistic regression technique for binary classification problems with R.
 * Bayes classifier and LDA: Other classification techniques included the Bayes classifier and linear discriminant analysis are introduced as further examples of statistical learning methods.
 * CART & Random forest: Descriping tree-based classifiers and introducing the random forest technique.
 * Bootstrap & Cross-validation: Methods for assessing classifiers by estimating missclasification error rates are  Presenting and applied in R.
 * ROC: Estimating the area under the receiver-operating characteristic (ROC) using R.

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