# Building a Machine Learning Model
## Overview
With the help of AI I architected a high-recall predictive pipeline using a Random Forest classifier to identify at-risk customers with 91% sensitivity. By implementing SMOTE to resolve a significant 4:1 class imbalance, the model was optimized to minimize "False Negatives," ensuring the bank captures the vast majority of potential churners for proactive intervention.

# Technical Highlights
* Imbalance Management: Applied SMOTE (Synthetic Minority Over-sampling Technique) to synthetically balance the training set, shifting the model focus from simple accuracy to effective churn detection.
* Hyperparameter Optimization: Utilized RandomizedSearchCV to fine-tune the Random Forest ensemble, ensuring the model generalizes well to unseen customer data.
* Performance Metrics: Achieved a Recall of 0.91 and an F1-Score of 0.94 for the churn class, providing a highly reliable tool for the Collections and Marketing teams.
* Feature Importance: Identified LoginFrequency and AmountSpent as the top systemic drivers of retention, allowing for data-driven strategy development.
