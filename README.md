# Heart-Disease-Detection.


This project implements a logistic regression model for the classification of heart disease. The dataset used in this project is sourced from the "heart.csv" file.

## Overview

The code in this repository performs the following steps:

1. Importing the required libraries, including `pandas`, `numpy`, and scikit-learn modules.
2. Loading the heart disease dataset using `pd.read_csv`.
3. Preprocessing the dataset by splitting it into features and target arrays.
4. Splitting the dataset into training and test sets using `train_test_split`.
5. Scaling the features using `StandardScaler` from scikit-learn.
6. Constructing a logistic regression model using `LogisticRegression`.
7. Performing hyperparameter tuning with grid search using `GridSearchCV` to find the best model configuration.
8. Training the best model on the entire training set.
9. Evaluating the best model using cross-validation and calculating the mean accuracy.
10. Predicting the target variable on the test set using the best model.
11. Calculating the accuracy score, confusion matrix, and classification report for model evaluation.
12. Displaying the results on the console.

## Getting Started

To run the code on your local machine, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python 3 and the required libraries installed.
3. Place the "heart.csv" dataset file in the same directory as the code file.
4. Open a terminal or command prompt and navigate to the project directory.
5. Run the code using the command: `python heart_disease_classification.py`.
6. View the results displayed on the console.

## Dependencies

The code relies on the following libraries:

- `pandas`: For data manipulation and analysis.
- `numpy`: For mathematical operations.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.

Install these dependencies using the following command:

```shell
pip install pandas numpy scikit-learn
