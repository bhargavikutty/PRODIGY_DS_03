# PRODIGY_DS_03
PRODIGY_INFOTECH_DATASCIENCE_INTERNSHIP_TASK_3

Bank Marketing Analysis
This repository contains code for analyzing and building a machine learning model to predict if a customer will subscribe to a term deposit based on the Bank Marketing dataset from the UCI Machine Learning Repository.

Dataset
The dataset used in this analysis is the "Bank Marketing" dataset obtained from the UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/222/bank+marketing). It contains data from direct marketing campaigns of a Portuguese banking institution, with the goal of predicting whether a client will subscribe to a term deposit.

The specific dataset used is bank-full.csv, which includes all examples and 17 input features.

Files
Bank_Marketing_Analysis.ipynb: A Jupyter Notebook containing the complete analysis, including data loading, exploration, preprocessing, feature engineering, modeling, and evaluation.

Bank_Full_data_2.csv: The dataset used for analysis.

Analysis Steps

Data Loading and Exploration: Load the dataset and perform initial exploration, checking for missing values, data types, and summary statistics.

Data Preprocessing: Convert object data types to categorical types, and then perform label encoding on categorical features.

Feature Scaling: Apply MinMax scaling to numerical features.

Feature Selection: Analyze feature correlations with the target variable and select the most relevant features.

Exploratory Data Analysis (EDA): Perform univariate and bivariate analysis of features, including visualizations.

Model Building: Split the data into training and testing sets, and build a Decision Tree Classifier model with hyperparameter tuning.

Model Evaluation: Evaluate the model's performance using a confusion matrix and other relevant metrics.

Requirements
Python (version 3.7 or higher)

Pandas (version 1.3.5)

NumPy (version 1.21.6)

Scikit-learn (version 1.0.2)

Matplotlib (version 3.5.1)

Seaborn (version 0.11.2)
