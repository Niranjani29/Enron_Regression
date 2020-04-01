# Enron_Regression
In this project, you will use regression to predict financial data for Enron employees and associates.



A python dictionary can’t be read directly into an sklearn classification or regression algorithm; instead, it needs a numpy array or a list of lists (each element of the list (itself a list) is a data point, and the elements of the smaller list are the features of that point).

We’ve written some helper functions (featureFormat() and targetFeatureSplit() in tools/feature_format.py) that can take a list of feature names and the data dictionary, and return a numpy array.

In the case when a feature does not have a value for a particular person, this function will also replace the feature value with 0 (zero).

<h5>Output Before removing the outliers</h5>
<img src='https://github.com/Niranjani29/Enron_Regression/blob/master/reg_bef.png'>


Just by adding these two lines, we can remove the outliers than hammer the plotted line and change the slpoe of the line


<h5>Output After removing the outliers</h5>
<img src='https://github.com/Niranjani29/Enron_Regression/blob/master/output_reg.png'>
