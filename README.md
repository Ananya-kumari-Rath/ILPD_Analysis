# ILPD Data Analysis Project

## Overview:
This project performs a data analysis of the Indian Liver Patient Dataset (ILPD) using logistic regression. 
The main objective is to predict the likelihood of liver disease based on various health metrics in the dataset. 
The analysis involves data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

## Dataset:
The dataset used in this project is the Indian Liver Patient Dataset (ILPD), which includes various features related to liver function tests and demographic details of patients. 
Each record in the dataset represents either a liver patient or a non-liver patient based on test results.

*Key Features:*
Age: Age of the patient.
Gender: Gender of the patient (Male/Female).
Total Bilirubin: Measure of bilirubin in the blood.
Direct Bilirubin: Measure of direct bilirubin in the blood.
Alkaline Phosphatase: Enzyme level.
Alanine Aminotransferase (ALT): Enzyme level.
Aspartate Aminotransferase (AST): Enzyme level.
Total Proteins: Total proteins in the blood.
Albumin: Blood protein level.
Albumin and Globulin Ratio: Ratio of albumin to globulin.
Label: Target variable indicating liver disease (1 for liver patient, 0 for non-liver patient)

## Project Structure
data/: Contains the ILPD dataset.
notebooks/: Jupyter notebooks for data preprocessing, EDA, and model training.
src/: Scripts for data processing, feature engineering, and model training.
models/: Directory for saving trained models.
README.md: Project description and instructions.

## Prerequisites
Python 3.x
Libraries:
pandas - For data manipulation
numpy - For numerical operations
scikit-learn - For logistic regression and model evaluation
matplotlib & seaborn - For visualization
Install the required packages by running:


## Steps in Analysis
1. Data Preprocessing
Handling Missing Values: Address any missing values in the dataset.
Encoding: Encode categorical features such as gender.
Scaling: Normalize the feature values for better model performance.
2. Exploratory Data Analysis (EDA)
Distribution Analysis: Check the distribution of features and the target variable.
Correlation Analysis: Identify correlations among features to understand their relationships.
3. Model Building
Logistic Regression: Fit a logistic regression model to predict the presence of liver disease.
Feature Selection: Use methods like Recursive Feature Elimination (RFE) to select important features.
4. Model Evaluation
Metrics: Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
Confusion Matrix: Analyze the confusion matrix to understand classification performance.

## Results
The results section presents the performance metrics of the logistic regression model and insights from the analysis. Findings include the most significant predictors of liver disease and potential improvements for the model.

## Usage
To run the analysis, execute the main script.

## Conclusion
This project provides a framework for understanding the ILPD and using logistic regression to predict liver disease. Further improvements could include using other classification models (e.g., decision trees, SVM) and more feature engineering.
