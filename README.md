# Credit-Card-Customer-Payment-Behaviour
## In this project we developed a K-Nearest Neighbors (KNN) classification model to classify credit-card customers based on their payment behavior.

Performed data cleaning, exploratory data analysis, feature engineering, and feature scaling, followed by selecting an optimal K value and evaluating the model using accuracy, confusion matrix, precision, recall, and F1-score.

----

## Project Overview
- Dataset: **"CC GENERAL.CSV"**

- Target variable: **PRC_FULL_PAYMENT**
  
- Model used: **KNN - K nearest neighbour

----

## Workflow
**Import Libraries** -> numpy, pandas, matplotlib, seaborne, scikit-learn 
**Dataset** -> "CC GENERAL.CSV"
**Data Understanding** -> column names, data types, statistical summary, checking missing values, checking duplicate values
   
Data Cleaning -> handling missing values
   
Target Creation -> PRC_FULL_PAYMENT >= 0.5  → Full Payer
                   PRC_FULL_PAYMENT < 0.5   → Partial/Non-Full Payer 
                   
EDA -> box plots, distributions, coprrelation heatmaps 
   
Feature Selection.
   
Train-Test Split -> 80% training and 20% testing
   
Feature Scaling -> used standard scaler
   
KNN Model. 
   
Optimal K Selection.
   
Prediction.
   
Model Evaluation.

Final Accuracy.
