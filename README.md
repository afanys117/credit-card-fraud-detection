# Credit Card Fraud Detection Project

## Overview:
This Jupyter Notebook presents a machine learning project focused on detecting fraudulent credit card transactions. The dataset used in this project contains transactions made by European cardholders in September 2013.

## Dataset Characteristics:
- **Source:** [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions over two days
- **Imbalance:** 492 frauds (0.172% of transactions)
- **Features:** Principal components obtained through PCA, 'Time,' and 'Amount'

## Modeling Approach:
- **Algorithm:** Random Forest Classifier
- **Hyperparameter Tuning:** Performed using GridSearchCV
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, and Confusion Matrix (with a focus on AUPRC due to class imbalance)

## Acknowledgments:
- The dataset is a result of a collaboration between Worldline and the Machine Learning Group (MLG) of ULB.

## Project Workflow:
1. Data Exploration and Preprocessing
2. Model Selection and Hyperparameter Tuning
3. Model Evaluation on Test Data
4. Training Final Model on Full Data
5. Evaluation of Final Model on Full Test Data
6. Saving and Loading the Final Model
