# Handwritten-Digits-Recognition
Handwritten Digit Recognition is an interesting machine learning problem in which we have to identify the handwritten digits through various classification algorithms. There are a number of ways and algorithms to recognize handwritten digits, including Deep Learning/CNN, SVM, Gaussian Naive Bayes, KNN, Decision Trees, Random Forests, etc. In this project, we will deploy a variety of machine learning algorithms from the SkLearn’s library on our dataset to classify the digits into their categories.

Problem Statement

To Implement Machine Learning Classification Algorithms to Recognize Handwritten Digits.

Dataset Description

We will use Sklearn’s load_digits dataset, which is a collection of 8x8 images (64 features)of digits. The dataset contains a total of 1797 sample points.
 
The syntax to load the dataset is as follows:

from sklearn.datasets import load_digits
digits = load_digits()


Parameters:               
n_class : integer, between 0 and 10, optional (default=10)
The number of classes to return.
return_X_y : boolean, default=False.
If True, returns (data, target) instead of a Bunch object.

