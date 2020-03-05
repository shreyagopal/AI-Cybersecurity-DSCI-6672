# AI-Cybersecurity-DSCI-6672:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This repo contains all the programming lab assignments from course AI & Cybersecurity. *The datasets used in the Jupyter notebooks are available in the Data Files folder of this repo.*


## Assignments:

* [Perceptron for Phish Detection](https://github.com/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Perceptron_for_Phish_Detection.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Perceptron_for_Phish_Detection.ipynb)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**What is Perceptron??** A perceptron is a machine learning algorithm for supervised learning of binary classifiers. A binary classifier is a function which can decide whether or not an input, represented by a vector of numbers, belongs to some specific class. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This Jupyter notebook covers the workflow of training a single-layer perceptron model to create a phish detector. The step by step process involves reading data from CSV file, creating samples and target dataframes, splitting the data to train and test datasets, importing and using predefined [Perceptron model from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html), fitting the model with tain dataset, predicting the target values of test dataset and caluclating the preformance of the model. Hyperparameters are tunned to acheive better performance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Dataset Details:** The dataset used in Perceptron for Phish Detection Jupyter Notebook is extracted from UCI Machine Learning Repository: [Phishing Websites Data Set](https://archive.ics.uci.edu/ml/datasets/phishing+websites). 


* [Logistic Regression for Spam Classification](https://github.com/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Logistic%20Regression%20for%20Spam%20Classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Logistic%20Regression%20for%20Spam%20Classification.ipynb)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**What is Logistic Regression??** Logistic regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This Jupyter notebook covers the workflow of training a logistic regression model to create a spam classifier. The step by step process involves reading data from CSV file, creating samples and target dataframes, splitting the data to train and test datasets, importing and using predefined [Logistic Regression model from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html), fitting the model with tain dataset, predicting the target values of test dataset and caluclating the preformance of the model. Hyperparameters are tunned to achieve better performance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Dataset Details:** The dataset used in Logistic Regression for Spam Classification Jupyter Notebook is extracted from UCI Machine Learning Repository: [Spambase Data Set](https://archive.ics.uci.edu/ml/datasets/spambase). 

## References

Here are some things I looked at while making these tutorials. Some of it may be out of date.

- https://en.wikipedia.org/wiki/Perceptron
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html
- https://www.medcalc.org/manual/logistic_regression.php
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
