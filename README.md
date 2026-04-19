# Bank Marketing Classification - Random Forest

## Overview
This project uses a Random Forest model to predict whether a client will subscribe to a bank product based on marketing campaign data

It focuses on understanding customer behavior and evaluating how well the model can distinguish between different outcomes

## Dataset
The dataset contains information about bank clients, including demographic and campaign-related features

The target variable (`y`) indicates whether the client subscribed to the product.

## Approach
- Data exploration and analysis
- Handling categorical variables using Label Encoding
- Train/test split with stratification
- Random Forest classification model

## Evaluation
The model was evaluated using:
- Accuracy
- ROC AUC score
- Confusion matrix
- Classification report

## Results
The model achieved solid performance and was able to distinguish between classes effectively

Feature importance analysis was also performed to identify the most relevant variables

## Tools and libraries
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn

## Files in this repository
- `random_forest.ipynb` → full analysis and training
- `random_forest.py` → script version
- `requirements.txt`

## Notes
This project goes beyond basic modeling by including evaluation metrics and feature importance analysis, making it closer to a real-world machine learning workflow.
