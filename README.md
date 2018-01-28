# Indian Liver Patient Classification

The Indian Liver Patient Dataset has been downloaded from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29). The dataset consists of 583 instances, 10 attributes and no missing values. There are 416 liver patient records and 167 non-liver patient records, which have been labeled by experts.

This project is being completed as part of the DSCI 573 Feature and Model Selection course at the University of British Columbia for the Master of Data Science Program

# Purpose and Methodology

For this dataset, my goal was to explore different models to classify patients. There are many models to explore, hyper-parameters to tune, and accuracies to report. This is meant to be only a small subset of the possible models you could use.

In this analysis, we clean up the data and split it into training, validation, and testing sets. We perform feature selection, and illustrate an example of using the `GridSearchCV` function in Scikit-learn to optimize the parameters. Later on, we loop through the parameters and plot the errors to illustrate their effects.

The analysis consists of:

* Decision Tree Classifier

* Random Forests

* kNN

* Logistic Regression

We ended up using the Random Forest Classification on our test data. 

# Running the Analysis

* Clone the repository on your local machine.

* Follow along with `ipynb` file on Jupyter Notebook.

  * Feel free to edit and manipulate the models on your own!

# Author

Ivan Despot

January 2018
