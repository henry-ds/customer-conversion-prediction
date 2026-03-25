# Customer Conversion Prediction for Targeted Marketing

## Overview
This project develops a machine learning model to predict customer response to a marketing campaign using a real-world banking dataset. The goal is to identify high-probability customers and support more efficient, data-driven marketing strategies.

The model achieves approximately *80–85% accuracy*, demonstrating strong predictive performance and the ability to capture key drivers of customer behavior.

---

## Objectives
•⁠  ⁠Analyze customer and campaign data
•⁠  ⁠Identify key factors influencing conversion
•⁠  ⁠Build a predictive model for customer response
•⁠  ⁠Generate actionable insights for marketing optimization

---

## Dataset
•⁠  ⁠Source: UCI / Kaggle Bank Marketing Dataset  
•⁠  ⁠Size: 45,000+ customer records  
•⁠  ⁠Target: Subscription to term deposit (Yes/No)

---

## Tools & Technologies
•⁠  ⁠Python  
•⁠  ⁠Pandas, NumPy  
•⁠  ⁠Scikit-learn  
•⁠  ⁠Matplotlib  
•⁠  ⁠Jupyter Notebook  

---

## Methodology

### 1. Exploratory Data Analysis
•⁠  ⁠Examined customer demographics and campaign variables
•⁠  ⁠Identified class imbalance in target variable
•⁠  ⁠Analyzed relationships between features and conversion

### 2. Feature Engineering
•⁠  ⁠Created behavioral and campaign-based features:
  - Contact intensity
  - Financial pressure score
  - Campaign grouping
•⁠  ⁠Encoded categorical variables for modeling

### 3. Modeling
•⁠  ⁠Trained a Random Forest classifier
•⁠  ⁠Evaluated using:
  - Accuracy
  - ROC AUC
  - Classification metrics

---

## Model Performance
•⁠  ⁠Accuracy: ~80–85%  
•⁠  ⁠Strong ROC AUC indicating good class separation  
•⁠  ⁠Balanced performance across classes  

---

## Key Insights

•⁠  ⁠Customers with *longer call durations* are significantly more likely to convert  
•⁠  ⁠*Moderate campaign contact* performs better than excessive outreach  
•⁠  ⁠Customers with *previous interactions* show higher conversion rates  
•⁠  ⁠Behavioral and engagement features are strong predictors of response  

---

## Business Impact

This model enables:
•⁠  ⁠Prioritization of high-probability customers  
•⁠  ⁠Improved campaign targeting  
•⁠  ⁠Reduced marketing costs  
•⁠  ⁠Increased conversion efficiency  

By focusing on customers most likely to respond, organizations can optimize resource allocation and improve marketing ROI.

---

## Important Note

The model includes the ⁠ duration ⁠ variable, which significantly improves predictive performance. However, since this variable is only known after the call, it introduces post-contact information. In a real-world deployment, a pre-contact model would exclude this feature.

---

## How to Run

1.⁠ ⁠Download dataset from UCI/Kaggle  
2.⁠ ⁠Place ⁠ bank-full.csv ⁠ inside the ⁠ data/ ⁠ folder  
3.⁠ ⁠Run notebooks in order:
   - ⁠ 01_eda.ipynb ⁠
   - ⁠ 02_feature_engineering.ipynb ⁠
   - ⁠ 03_modeling.ipynb ⁠

---

## Future Improvements

•⁠  ⁠Build a pre-contact model excluding duration  
•⁠  ⁠Implement hyperparameter tuning  
•⁠  ⁠Develop a Power BI dashboard for business visualization  
•⁠  ⁠Deploy model as an API  

---

## Author
Emeka Henry Anumba  
Data Analyst | Data-Driven Marketing Enthusiast
