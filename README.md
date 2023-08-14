# Air-Quality-Index-Classifier-by-PySpark

This project focuses on building a classification model for air quality prediction using a dataset containing 16 features and approximately 707,876 observations. The goal is to predict the Air Quality Index (AQI) category, which is divided into six classes: Moderate, Satisfactory, Poor, Very Poor, Good, and Severe.

# Dataset Overview
The dataset comprises the following aspects:

Features: 16 attributes characterizing different aspects of air quality.
Observations: Around 707,876 instances.
Exploratory Data Analysis (EDA)
An exploratory data analysis was conducted in the first file to gain insights into the data. This step involved visualizations, statistical summaries, and identification of potential trends or patterns.

# Data Preprocessing
Data cleaning steps were executed to ensure data quality and consistency. This included handling missing values, outliers, and any inconsistencies in the dataset.

# Feature Engineering and Dimensionality Reduction
To enhance model performance, feature engineering was applied, including the use of Principal Component Analysis (PCA) to reduce dimensionality while retaining essential information.

# Model Implementation
Three classification algorithms were implemented in the modeling file:

Random Forest: Utilized a Random Forest classifier for robust predictions.
Decision Tree: Implemented a Decision Tree classifier as a baseline model.
Naive Bayes: Utilized the Naive Bayes classifier for its probabilistic approach.

# Performance Enhancement
The following steps were undertaken to optimize model performance:

Removed Unnecessary Features: Identified and removed features that didn't contribute significantly to the predictive power of the model.
Model Hyperparameters: Fine-tuned the hyperparameters of each classifier to achieve optimal performance.




