# Customer Churn Analysis

This project focuses on predicting customer churn by analyzing various behavioral and demographic data. The goal is to help businesses identify at-risk customers and take proactive retention measures.

## Project Summary

This end-to-end churn analysis includes:

- Data collection and merging from multiple sources
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering and encoding
- Model selection and hyperparameter tuning
- Model evaluation and business recommendations

## Dataset Overview

The following datasets were used:

- **Customer Demographics** – Age, gender, marital status, income level
- **Transaction History** – Purchase frequency, amount spent, product category
- **Customer Service** – Interaction type, resolution status
- **Churn Status** – Target label (Active / Churned)

## Key Steps

### Exploratory Data Analysis

- Identified patterns in churn rate by gender, age, and resolution outcomes
- Analyzed customer value through spending patterns
- Visualized relationships between features and churn

### Data Preprocessing

- Handled missing values (dropped or imputed)
- Removed outliers using Z-score method
- Standardized numerical features
- Applied one-hot encoding to categorical variables

### Model Building

- Performed stratified train-test split
- Used Random Forest Classifier with GridSearchCV for tuning
- Evaluated using F1-score and ROC-AUC

## Model Performance

- **Accuracy**: 90%
- **ROC-AUC**: 0.95
- **Precision and recall** balanced for both churned and active customers

## Recommendations & Business Implications

- Target high-spending but potentially churning customers with loyalty incentives
- Improve resolution processes, especially for unresolved or repeated issues
- Focus retention campaigns on segments with higher churn risk (e.g., certain age groups or income levels)
- Leverage churn predictors to develop real-time alerts for at-risk customers

## Files Included

- **Customer_Churn_Analysis.ipynb**: Main notebook with full code
- **Customer_Churn_Data_Large.xlsx**: Original dataset

## How to Use

1. Clone the repository:  
   `git clone https://github.com/Manikanta898/Customer-Churn-Analysis.git`
2. Install dependencies:  
   `pip install -r requirements.txt` or manually install required libraries like `pandas`, `numpy`, `scikit-learn`, etc.
3. Run the Jupyter notebook (`Customer_Churn_Analysis.ipynb`) to explore the analysis and model results.


## GitHub Repository

[https://github.com/Manikanta898/Customer-Churn-Analysis](https://github.com/Manikanta898/Customer-Churn-Analysis)
