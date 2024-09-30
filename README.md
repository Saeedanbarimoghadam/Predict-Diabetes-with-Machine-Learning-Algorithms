# Predict Diabetes with Machine Learning Algorithms
This project aims to predict diabetes using several machine learning algorithms and data processing techniques. The dataset consists of 768 records, each representing a patient's medical information, with features like glucose levels, blood pressure, BMI, and others. The target variable, Outcome, indicates whether a patient has diabetes (1) or not (0).

Algorithms Used:
K-Nearest Neighbors (KNN):

KNN is a simple algorithm that classifies data based on the majority class among its nearest neighbors.
Performance:
Training accuracy: 79%
Test accuracy: 78%
Decision Tree Classifier:

Decision trees split the data into smaller subsets based on the most important features.
Performance:
Training accuracy: 77.3%
Test accuracy: 74%
Feature Importance: Glucose was the most important feature, followed by BMI.
Neural Network (MLP Classifier):

A basic neural network (MLP) was applied to the data.
Performance (without scaling):
Training accuracy: 73%
Test accuracy: 72%
After scaling the data using StandardScaler, the accuracy improved:
Performance (with scaling):
Training accuracy: 82.3%
Test accuracy: 80.2%

The project effectively compares multiple models, demonstrating the impact of feature scaling on neural network performance.
The Neural Network with scaled data provided the best test accuracy at 80.2%.
Feature importance analysis from the Decision Tree shows that glucose levels and BMI are the most critical factors in predicting diabetes.
