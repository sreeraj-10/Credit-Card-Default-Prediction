# Credit Card Default Prediction

## Overview
This project aims to analyze and predict credit card defaults using machine learning techniques. The dataset used for this project contains information on credit card clients, including their demographic details, credit history, and repayment status.

## Dataset
#### Source:
- UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
- Number of Records: 30,000

#### Features: 
- LIMIT_BAL: Amount of given credit
- SEX: Gender (1 = Male, 2 = Female)
- EDUCATION: Education level
- MARRIAGE: Marital status
- AGE: Age in years
- PAY_1 to PAY_6: Past repayment status
- BILL_AMT1 to BILL_AMT6: Bill statement amounts
- PAY_AMT1 to PAY_AMT6: Payment amounts
- Is_Defaulter: Target variable (1 = Default, 0 = No Default)

## Technique used:
- Data Collection & Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Development
- Pipeline Implementation
- Model Evaluation & Optimization

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imblearn

## Results
- Best-performing model: Random Forest Classifier
- Achieved accuracy: 87.64%

## Machine Learning Pipeline
1. Data Preprocessing: Handling missing values and feature scaling.
2. Feature Selection: Selecting the most relevant features for prediction.
3. SMOTE Implementation: Addressing class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).
4. Model Training: Training a Random Forest Classifier within the pipeline.

## Conclusion
This research focused on predicting default payments among customers in Taiwan using various machine learning models. In this project, we explored multiple machine learning models to predict defaulters, with Random Forest emerging as the best-performing model after hyperparameter tuning. The model achieved a balanced trade-off between precision and recall, ensuring reliable predictions.

## Author
Sreeraj S
