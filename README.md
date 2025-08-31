# Rock vs Mine Prediction using Logistic Regression

This project uses Machine Learning (Logistic Regression) to classify whether an object is a Rock (R) or a Mine (M) based on sonar signal data. The dataset used is the Sonar Dataset from the UCI Machine Learning Repository.

# 📂 Project Overview

Objective: Build a predictive system that can classify objects detected by sonar signals as rocks or mines.

Dataset: Sonar Dataset (UCI Repository)

Model Used: Logistic Regression

Evaluation Metric: Accuracy

# ⚙ Dependencies

Make sure you have the following libraries installed:

pip install numpy pandas scikit-learn

# 📊 Steps in the Project

Data Collection & Processing

Loaded the sonar dataset (sonar data.csv) using pandas.

Explored dataset shape, descriptive statistics, and class distribution.

Split features (X) and target labels (Y).

Train-Test Split

Training: 90%

Testing: 10%

Used stratified sampling to preserve class balance.

Model Training

Trained a Logistic Regression model on the training set.

Model Evaluation

Evaluated model performance on training and test data using accuracy score.

Predictive System

Created a system to predict if a new sonar signal corresponds to a rock or a mine.
