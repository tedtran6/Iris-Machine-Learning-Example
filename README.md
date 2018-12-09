# Iris-Machine-Learning Example

This project exercises simple Machine Learning using the Iris dataset in using DecisionTreeClassifier, visualizing it, and then also creating two different classifiers of my own.

The classifiers that I create are:

* A Random Classifier, which simply selects a random label and uses that as the prediction.
* A Nearest Neighbor Classifier, which uses the euclidean distance formula.
addition from a previous notebook

The accuracy score for the Decision tree classifier with the particular split that I obtained was 0.96, which is pretty good.
The accuracy score for the Nearest neighbor classifier that I built obtained was around 0.96 as well.

## Notes

The project was compiled in python 3.7

Graph visualizations were created using Graphviz

below are some photos of the charts created.

This is some data using striclty the decision tree classifier so we can visualize it with a graphviz tree
Running the split between the training and testing split once

### Example of a decision tree created from the classifier.
<img src = "images/graph1.png" width = "400">

We will be analyzing the results that the classifier got **right** in trying to assign labels in order to analyze the thought process.

<img src = "images/image1.png" width = "800">

<img src = "images/graph1_examples.png" width = "900">

### This is a NEW decision tree created from the classifier, fed different training data.
<img src = "images/graph2.png" width = "400">

This time we will be analyzing the results that the classifier got **wrong** in trying to assign labels in order to analyze the thought process.

<img src = "images/image2.png" width = "800">

<img src = "images/graph2_examples.png" width = "900">
