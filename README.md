# Loan Default Dataset Analysis

This repository contains an analysis of the Loan Default Dataset obtained from [Kaggle](https://www.kaggle.com/datasets/yasserh/loan-default-dataset/data). The analysis includes data preprocessing, exploratory data analysis (EDA), feature selection using Information Value (IV), and model building to predict loan defaults.

## Overview

The goal of this project is to develop a predictive model that can effectively predict loan defaults based on various borrower attributes. The dataset provides information on borrowers demographics, financial history, and loan details.

## Contents

- **Notebooks**:
  - `Data_Cleaning_and_EDA.ipynb`: Notebook detailing data cleaning, KNN imputation and exploratory data analysis.
  - `Loan_Default_Prediction`: Notebook performing feature selection using  IV, preparing data for modeling and implementing several machine learning models to predict loan defaults..
  
- **Dataset**:
  - `Loan_Default.csv`: The original dataset downloaded from Kaggle.
  -  `Loan_Default_imputed.csv`: The imputed dataset using KNN imputation.

## Notebooks Overview

1. **Data Preprocessing and Exploratory Data Analysi**:
   - Handling missing values using KNN imputation.
   - Cleaning and transforming data to prepare for analysis.
   - Exploring relationships and distributions within the dataset.
   
2. **Feature Selection and Model Building**:
   - Using IV to select features most predictive of loan defaults.
   - Implementing various machine learning models (e.g., Logistic Regression, Decission Tree, etc.) to predict loan defaults.
   - Evaluating model performance metrics.
   - Optionally, focusing on minimizing False Negatives to reduce the risk of approving loans that may default.
   
