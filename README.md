# Customer Cancellation Analysis

## Overview

This project focuses on analyzing customer churn reasons in a subscription-based application using machine learning. The objective is to predict the primary reason why a user cancelled their subscription based on behavioral, engagement, payment, support, and device-related data.

The target variable consists of four cancellation categories:

- `price_sensitive`
- `bad_experience`
- `found_alternative`
- `lost_interest`

This is a multiclass classification problem where user behavior patterns often overlap, making prediction challenging and realistic.

---

## Dataset Information


The dataset contains customer activity, subscription, engagement, support, and device-related features collected from users before cancellation.

### Target Variable

| Column | Type |
|--------|------|
| `churn_reason` | Multiclass Classification |

### Classes

- `price_sensitive`
- `bad_experience`
- `found_alternative`
- `lost_interest`

### Dataset Features

The dataset includes:

- User demographics
- Subscription details
- Payment behavior
- Session activity
- Support ticket history
- Device information
- App usage patterns
- Notification preferences
- Competitor app indicators

Total:
- 28 Features
- 1 ID Column
- 1 Target Column

---

## Workflow

1. Data Collection  
2. Data Cleaning and Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Encoding and Scaling  
6. Model Training  
7. Cross Validation  
8. Model Evaluation  
9. Prediction and Analysis  

---

## Models Used

- XGBoost
- CatBoost
- LightGBM

---



## Evaluation Metric

- Macro F1 Score

Macro F1 Score evaluates model performance equally across all classes and is suitable for multiclass classification problems with overlapping patterns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost
- LightGBM

---


## Conclusion

This project demonstrates how machine learning can be used to identify and classify customer cancellation reasons in subscription-based platforms. Understanding churn behavior can help businesses improve customer retention, enhance user experience, and make data-driven product decisions.
