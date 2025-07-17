# Iris ML Project

This project uses the classic Iris dataset to predict the species of an iris flower based on its sepal and petal measurements.  
We will use 10 different machine learning models and compare their accuracy.  
The final output will be an accuracy comparison chart and a table showing results of each model.

## Step 1: Load and Explore the Iris Dataset

We are using the built-in Iris dataset from Scikit-learn.  
It contains 150 records of iris flowers with 4 features:
- sepal length
- sepal width
- petal length
- petal width

The goal is to predict the `species` of the flower using these features.


## Step 2: Logistic Regression

Logistic Regression is a simple classification algorithm.  
It works well when the relationship between features and output is linear.  
Here, we'll use it to predict the species of a flower based on 4 features.

We will:
- Split the data into training and testing sets
- Train a Logistic Regression model
- Predict on the test set
- Measure the accuracy
