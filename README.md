# Maternal-Health-Risk

## Overview
This project focuses on predicting maternal health risks by classifying pregnant women into low, mid, and high-risk categories based on clinical data. The objective is to identify high-risk cases early for timely interventions.

## Methodology / Tools and Techniques
- Data Source: UC Irvine ML Repository
- Preprocessing: Label Encoding, MinMax Scaling, Outlier Removal
- Models: Decision Tree, Logistic Regression, Gradient Boosting, Random Forest, Ensemble
- Evaluation Metrics: Accuracy, Precision, Recall

## Key Findings
- Gradient Boosting and Random Forest both achieved 87% accuracy, with the ensemble model slightly outperforming them at 88%.
- Key predictors: Systolic and Diastolic Blood Pressure, Blood Glucose, Heart Rate.
- Logistic Regression underperformed with an accuracy of 65%.

## Discussion
Ensemble methods achieved balanced predictive power across risk categories. Future work includes incorporating additional features such as nutritional data and advanced hyperparameter tuning using Bayesian optimization.
