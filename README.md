# ML-Lab4
WASAN SAEED ALDOSSARY
2240007802
## Overview
This LAB4 focuses on data preprocessing techniques using the Possum dataset. The goal is to clean, prepare, and transform the data for machine learning tasks.

## Dataset
- Dataset: Possum Dataset
- Source: Kaggle / OpenIntro
- The dataset contains biological measurements of possums.

## **Tasks Performed**

### 1. Data Quality Issues
- Checked data types, missing values, and duplicates.
- Identified unnecessary columns such as identifiers.

### 2. Handling Missing Values
- Missing values in numerical columns were handled using mean imputation.
- This method preserves the overall distribution of the data.

### 3. Outlier Detection
- Used the IQR (Interquartile Range) method to detect outliers.
- Outliers were removed to improve data quality.

### 4. Normalization
Two normalization techniques were applied:
- Min-Max Scaling (range between 0 and 1)
- Z-score Standardization (mean = 0, std = 1)

### 5. PCA (Principal Component Analysis)
- Correlation between numerical features was analyzed.
- PCA was applied to reduce dimensionality after normalization.

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## FINLE Results
- Cleaned dataset with no missing values
- Reduced effect of outliers
- Scaled features for better model performance
- Applied PCA for dimensionality reduction
