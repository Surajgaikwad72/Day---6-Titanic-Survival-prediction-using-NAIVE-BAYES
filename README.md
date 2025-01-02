# Day---6-Titanic-Survival-prediction-using-NAIVE-BAYES
I have taken a challenge to make project on every algorithm of Machine Learning. [ Day - 6 | Titanic Survival prediction using NAIVE BAYES]

Day-6 Titanic Survival Prediction Using Naive Bayes
Project Overview
This project focuses on predicting the survival of passengers on the Titanic using the Naive Bayes classification algorithm. The Titanic dataset contains information about the passengers such as their age, class, sex, and whether they survived or not. The objective is to build a machine learning model that can predict the survival status of passengers based on these features.

Naive Bayes is a probabilistic classifier based on Bayes' theorem, and it's particularly effective for classification tasks where the features are conditionally independent. In this case, we will apply the Gaussian Naive Bayes algorithm, which assumes that the features follow a Gaussian (normal) distribution.

Key Objectives
Preprocess and Clean Data: Clean the Titanic dataset, handle missing values, and prepare it for model training.
Train a Naive Bayes Classifier: Build and train a Naive Bayes model using the preprocessed dataset.
Evaluate the Model: Evaluate the classifier’s performance on the test data using accuracy and other metrics.
Make Predictions: Use the trained model to predict the survival of passengers on the Titanic.
Algorithm: Naive Bayes
Naive Bayes is a simple and effective classification algorithm based on Bayes' Theorem. It assumes that all features are independent, which simplifies the computation of the conditional probabilities.

Gaussian Naive Bayes: This version of Naive Bayes assumes that continuous features (like age) follow a Gaussian distribution. It is suitable for the Titanic dataset, where numerical features need to be modeled as such.
Training Process: The model learns the probability of survival (or non-survival) based on the given features (such as age, gender, and class) using maximum likelihood estimation.
