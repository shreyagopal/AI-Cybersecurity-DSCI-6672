# AI-Cybersecurity-DSCI-6672:

This repo Contains all the programming lab assignments from course AI & Cybersecurity

## Assignments:

* [Perceptron for Phish Detection](https://github.com/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Perceptron_for_Phish_Detection.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shreyagopal/AI-Cybersecurity-DSCI-6672/blob/master/Perceptron_for_Phish_Detection.ipynb)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**What is Perceptron??** A perceptron is a machine learning algorithm for supervised learning of binary classifiers. A binary classifier is a function which can decide whether or not an input, represented by a vector of numbers, belongs to some specific class. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This Jupyter notebook covers the workflow of training a single-layer perceptron model to create a phish detector. The step by step process involves reading data from CSV file, creating samples and target datasets, splitting the data to train and test datasets, importing and using [Perceptron model from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html), fitting the model with tain dataset, predicting the target values of test dataset and caluclating the preformance of the model. Hyperparameters are tunned to acheive better performance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Dataset Details:** The dataset used in Perceptron for Phish Detection Jupyter Notebook is extracted from UCI Machine Learning Repository: [Phishing Websites Data Set](https://archive.ics.uci.edu/ml/datasets/phishing+websites). And the dataset is also provided in the Data Files folder of this repo.


## References

Here are some things I looked at while making these tutorials. Some of it may be out of date.

- https://en.wikipedia.org/wiki/Perceptron
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html
