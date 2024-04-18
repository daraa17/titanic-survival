## Titanic Survival

# Titanic Survivor Prediction: 
 
# Introduction: 
This project aims to build a machine learning model that predicts the likelihood of survival for passengers aboard the Titanic based on various attributes such as age, gender, ticket class, etc. 

# Overview

The data has been split into two groups:

Training set (train.csv): Used to build machine learning models. The outcome (ground truth) for each passenger is provided.

Test set (test.csv): Used to evaluate how well the model performs on unseen data. The ground truth for each passenger is not provided, and it is the job of the model to predict these outcomes.

# Features Used

The following features were used in building the model:

Age

Gender (Sex)

Ticket class (Pclass)

Embarked port (Embarked)

# Libraries Used

The following libraries were used in this project:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Model Building Process

Data Loading: Load the training data (train.csv) using Pandas.

Preprocessing: Preprocess the data by handling missing values and encoding categorical variables.

Model Training: Train a Logistic Regression model using the preprocessed data.

Model Evaluation: Evaluate the model's performance using accuracy score.

Prediction: Predict survival probabilities for passengers in the test data (test.csv).

Output Generation: Generate predictions and save them to a CSV file (predictions.csv).
Results

The model predicted that around 38.04% of the passengers in the test dataset would survive the Titanic sinking.

# Files Included

train.csv: Training data containing features and ground truth labels.

test.csv: Test data containing features without ground truth labels.

gender_submission.csv: Example submission file with predictions assuming all and only female passengers survive.

predictions.csv: CSV file containing predicted survival outcomes for the passengers in the test data.

model_performance.csv: contains the performance metrics of different model configurations, such as accuracy, achieved during the evaluation process

Data Obtained from : https://www.kaggle.com/competitions/titanic/data
