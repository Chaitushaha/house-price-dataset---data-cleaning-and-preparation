# house-price-dataset---data-cleaning-and-preparation
House Price Data Cleaning Project
#Project Overview
#This project focuses on data cleaning and missing value handling for the House Price Prediction dataset.
The main goal is to prepare a clean and reliable dataset suitable for machine learning models.

# Dataset
Dataset Name: House Prices – Advanced Regression Techniques
Source: Kaggle
Type: Tabular (Numerical + Categorical features)
# Libraries Used
Pandas
Matplotlib
# Data Loading and Missing Value Analysis
Dataset loaded using Pandas.
Missing values identified using .isnull().sum().
Missing value patterns visualized using bar charts for better understanding.
# Data Cleaning Steps
Numerical columns:
Missing values handled using median imputation.
Categorical columns: Missing values handled using mode imputation. Columns with extremely high missing values were checked and removed if required.

# Data Validation
Dataset re-checked after cleaning to ensure no missing values remain.
Dataset size (rows and columns) compared before and after cleaning.

# Results
All missing values successfully handled.
No rows were dropped during cleaning.
Data quality improved and became consistent.

# Conclusion
The dataset is now clean, complete, and ready for further machine learning tasks such as House Price Prediction.

# File Structure
Untitled19.ipynb" : Jupyter Notebook containing complete data cleaning and analysis
README.md : Project documentation

Untitled19.ipynb : Jupyter Notebook containing complete data cleaning and analysis

README.md : Project documentation
