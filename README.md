# Bank Customer Churn Prediction

## Overview
This project focuses on predicting customer churn in the banking industry using machine learning techniques. By analyzing a dataset of 10,000 bank customers, we build and compare multiple predictive models to identify customers at risk of leaving the bank.

## Key Findings
- XGBoost model achieved the highest performance with an AUC of 0.866
- Age, number of products, and account activity emerged as the strongest predictors
- Identified high-risk segments including "Senior Inactive French Customers" with 81% churn rate
- Developed segment-specific retention strategies with potential to reduce churn by 25-30%

## Features
- Advanced exploratory data analysis with customer segmentation
- Feature engineering to capture complex relationships
- Model comparison between Logistic Regression, Random Forest, XGBoost, and GBM
- Threshold optimization for real-world application
- Detailed business recommendations and implementation roadmap

## Dataset
The dataset contains information about 10,000 bank customers including:
- Demographic data (age, gender, geography)
- Financial information (credit score, balance, estimated salary)
- Relationship metrics (tenure, number of products, activity level)
- Churn status (whether the customer left the bank)

## Technology Stack
- R for data analysis and modeling
- Libraries: tidyverse, caret, randomForest, xgboost, gbm, pROC
- R Markdown for presentation and documentation

## Structure
- `/code` - R Markdown analysis file
- `/data` - Input dataset
- `/output` - HTML report of the analysis
- `/images` - Key visualizations from the analysis