# Machine-Learning #
This repository contains code from beginners level to advanced level of machine learning.
All of the code is in Python and is devided to subjects for example:
* Clustering
  * Hierarchical Clustering
  * K-Means Clustering
  
most of the algorithems are based on the principle of minimizing the MSE (mean squere error)
this could be shown with simple inear regression:

## Simple linear regression ##
is a statistical method that allows us to study relationships between two continuous (quantitative) variables:
* One variable, denoted x, is regarded as the predictor or independent variable.
* The other variable, denoted y, is regarded as the response, outcome, or dependent variable.

Simple linear regression gets its adjective "simple," because it concerns the study of only one predictor variable. In contrast, multiple linear regression gets its adjective "multiple," because it concerns the study of two or more predictor variables.
in most cases the relationship between the variables is not perfect and if we plot them on a scatter graph we will have a hard time
to find the best line who describes the connection with minimmum error.

let's take the MSE (mean squer error) function to measure the error between the depended variable to the predicted depended value,
we can describe it like this:

* y  = independed value
* y' = predicted depended value
* n  = number of depended values

### MSE = (1/n)*SUM((y'-y)^2) ###

![picture alt](https://github.com/amitsason/Machine-Learning/blob/master/Regression/Simple%20Linear%20Regression/mse.JPG)


![picture alt](https://github.com/amitsason/Machine-Learning/blob/master/Regression/Simple%20Linear%20Regression/mse%20example.JPG)

Our goal is to minimize the error function and take the model in which the cost function is the smallest, and it describes the relation 
between x and y in the best way.

enjoy my repository!



