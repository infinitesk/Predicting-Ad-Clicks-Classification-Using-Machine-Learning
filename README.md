# Predicting Ad Clicks: Classification Using Machine Learning

## Project Overview
This project focuses on designing and implementing machine learning models to predict user likelihood of clicking on advertisements, thereby optimizing targeted marketing strategies. Using historical data, the model identifies critical factors influencing user engagement, improving the efficiency of advertising campaigns for an Indonesian company.

## Problem Statement
The company currently uses a "shotgun" strategy, displaying ads to all users, resulting in:
- A click rate of only **50%**.
- High advertisement costs with suboptimal ROI.

### Objective
- Develop machine learning models to reliably predict which users are likely to click on an ad.
- Evaluate models based on recall, accuracy, simplicity, and prediction time.
- Identify key factors influencing user behavior.
- Provide actionable recommendations for targeted advertising strategies.
- Estimate the impact of model implementation on cost, click rate, and profit.

## Dataset Description
The dataset was sourced from Rakamin Academy and contains the following features:
- **Unnamed: 0**: Customer ID
- **Daily Time Spent on Site**: Time spent by the user on the site (in minutes).
- **Age**: Customer's age (years).
- **Area Income**: Average income of the user's geographical area.
- **Daily Internet Usage**: Average daily internet usage (minutes).
- **Male**: Gender of the customer (1 for male, 0 for female).
- **Timestamp**: Time when the user interacted with the ad.
- **Clicked on Ad**: Target variable (1 if the user clicked on the ad, 0 otherwise).
- **City**: User's city.
- **Province**: User's province.
- **Category**: Advertisement category.


## Machine Learning Approach
Multiple models were implemented and evaluated, including:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost

### Methodology
1. Data preprocessing (handling missing values, feature engineering).
2. Hyperparameter tuning for optimal performance.
3. Evaluation of models based on recall, accuracy, and prediction time.
4. Business simulation to quantify financial impact.

## Key Results
### Before Model Implementation
- **Click Rate**: 50%
- **Total Cost**: Rp.1,000,000
- **Total Revenue**: Rp.2,000,000
- **Profit**: Rp.1,000,000

### After Model Implementation
- **Click Rate**: 96.8%
- **Total Cost**: Rp.499,000
- **Total Revenue**: Rp.1,932,000
- **Profit**: Rp.1,433,000

### Impact
- Reduced advertising costs by **50.1%**.
- Increased profit by **43.3%**.
- Enhanced targeting efficiency, improving ROI significantly.

## Conclusion
By implementing a predictive model, the company transitioned from a generalized advertising approach to a precision-driven strategy, achieving higher engagement and profitability.
