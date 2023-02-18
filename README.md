# Titanic Survival Predictions | Classification
In this project, we aim to predict the survival of passengers on the Titanic based on certain features. We will go through the following steps:

## 1) Import Necessary Libraries
First, we import the necessary Python libraries such as numpy, pandas, matplotlib, and seaborn.

## 2) Read in and Explore the Data
We then read in the training and testing data using pd.read_csv and take a first look at the training data using the describe() function.

## 3) Data Cleaning and Preprocessing
We perform data cleaning and preprocessing steps, such as dealing with missing data, converting categorical features, and dropping unnecessary columns.

## 4) Exploratory Data Analysis
We visualize and explore the data using count plots and histograms.

## 5) Building our Model
We train and test various binary classifiers using 80% of our training data and predict for the remaining 20%. We then calculate the accuracy of each model and choose the best one.

## The following models are tested:

* Naive Bayes
* Logistic Regression
* Support Vector Machine
* Decision Tree Classifier
* Random Forest Classifier
* KNN or k-Nearest Neighbors
* Stochastic Gradient Descent
* Gradient Boosting Classifier

The best model is chosen based on the accuracy score, and we use it to predict survival on the testing data.
