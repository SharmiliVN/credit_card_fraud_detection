Introduction
This project aims to develop a machine learning model capable of detecting fraudulent credit card transactions. By analyzing various transaction features, the model can identify patterns indicative of fraudulent activity.

Data
The dataset used for this project is taken from kaggle.
features::
Transaction ID
Transaction Amount
Time Elapsed
Various other transaction attributes

Data Preprocessing:
Before training the model, the data undergoes the following preprocessing steps:

Handling Missing Values: Missing values are filled by mode.
Feature Scaling: Features are scaled to a common range to ensure fair comparison.
Data Splitting: The dataset is divided into training and testing sets for model evaluation.

Model Evaluation
The trained model is evaluated on the testing set to assess its performance. Metrics like accuracy, precision, recall, and F1-score are calculated to measure the model's ability to correctly identify fraudulent transactions.
