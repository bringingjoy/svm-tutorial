 # Understanding your data and using the SVM algorithm for classification
If you've ever wanted to build a predictive model that learns the aspects of your data which make it fall into one category or another, then this is tutorial was written for you!
In this tutorial, you learn some tools for better understands the dataset you are working with via visualization tools, data preprocessing tips, and dimensionality reduction options.
You'll also learn about a classic Machine Learning (ML) algorithm known affectionately as SVM, or the Support Vector Machine model. 

The two focuses of this article will walk you through:
# I. Working with your data:
####  1) Preliminaries: 
Loading a datafile into a Numpy (multidimensional) array
####  2) Preprocessing: 
Converting categorical "features" into numerical representation, "one-hot" encoding, and preparing the dataset for binary classification
####  3) Visualization: 
Building intuition about what your data "looks like"
####  4) Big data: 
Basic dimensionality reduction options
####  5) Cross-validation: 
How to split your data into parts your model can be trained and tested on

# II. The Support Vector Machine Algorithm:
##  1) Background: 
What the heck is a support vector anyway?
##  2) Intuition: 
How the SVM learns to separate your data into two classes
##  3) Kernels: The Mathematics of SVM
Special functions which help SVM learn to classify your data
##  4) Debugging: 
Why doesn't it seem to be working? Why isn't my SVM learning anything? 
##  5) Optimization & Tuning: 
How to tweak the special *knobs* of SVM to get better performance

### We assume that:
<b>1)</b> You have a <b>basic understanding</b> of what Machine Learning is or does (if not, please check out this excellent resource: ) <br>
<b>2)</b> <b>Basic Python/coding skills</b> (Numpy experience not necessary, but you should understand what a for-loop is or not be afraid to read the Python documentation) <br>
<b>3)</b> You have some basic mathematics knowledge, are familiar with a vector, matrix, or can look up these definitions. <br>
<b>4)</b> You have a dataset with <b>binary classes</b> (2 classes): <br>
If not, we will be using the following datasets from the UC Irvine Machine Learning repository in this tutorial: 
- [Epileptic Seizure Recognition Data Set](http://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition) <br>

<script src="https://github.com/bringingjoy/svm-tutorial/svm-tutorial-notebook.ipynb"></script>


