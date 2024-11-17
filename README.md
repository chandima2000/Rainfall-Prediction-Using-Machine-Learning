# Rainfall-Prediction-Using-Machine-Learning

## Introduction

This project demonstrates building a Random Forest model for predicting target variables based on a given dataset. The project includes data preprocessing steps such as handling missing values, feature scaling, down-sampling technique, encoding categorical variables and hyperparameter tuning.

##  Dataset
The dataset used in this project contains various weather parameters. Each row represents a different time point with features such as temperature, humidity, wind speed, etc.

## Features
Data Cleaning: Handling missing values with mode and median.
Feature Scaling: Standardizing numerical features.
Modelling: Building a Random Forest model.
Evaluation: Assessing model performance with metrics such as accuracy, Cross-validation score, Confusion Matrix and Classification Report.

##  Data Preprocessing
### 1. Handling Missing Values
Missing values were filled using the median and Mode.

### 2. Down-Sampling Technique
Addressed class imbalance by using the down-sampling technique to balance the dataset.

### 3. Label Encoding
Applied Label Encoding to convert categorical variables into numerical values for better model performance.

### 4. Drop Highly Correlated Columns
Dropped columns with a correlation coefficient to reduce multicollinearity and improve model performance.

### 5. Feature Scaling
Used Standard Scaler to standardize the dataset for uniform feature distribution.

##  Model Building & Hyperparameter Tuning

### 1. Random Forest Classifier
Built a Random Forest model to predict the target variable.

### 2. Hyperparameter Tuning
Used GridSearchCV for tuning the hyperparameters to find the best combination for maximum model performance.


## Results
Accuracy: Achieved an accuracy of 74.47% on the test set.
Confusion Matrix: Shows model performance on each class.
Classification Report: Provides precision, recall, and F1-score.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes.
