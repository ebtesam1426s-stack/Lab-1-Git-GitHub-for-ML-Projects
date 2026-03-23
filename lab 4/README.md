Data Preprocessing and Analysis – Titanic Dataset
Overview

This project applies data preprocessing techniques on the Titanic dataset, including handling missing values, detecting outliers, normalization, and PCA.

Dataset

Titanic dataset from Kaggle containing passenger information such as Age, Fare, Pclass, and Survival.

Target Variable:
Survived (0 = Did not survive, 1 = Survived)

Task 1: Data Quality Issues
Missing values in Age and Cabin
Mixed data types
Presence of outliers in numerical features

Task 2: Missing Values
Age filled using median
Cabin dropped due to many missing values

Task 3: Outliers (IQR)
Applied on Age and Fare
Extreme values removed
Task 4: Normalization

Min-Max Scaling
Z-score Standardization
Applied to Age and Fare

Task 5: PCA

PCA applied because numerical features show correlation.

Tools

Python, Pandas, NumPy, Matplotlib, Scikit-learn

Conclusion

Preprocessing improved data quality and prepared the dataset for further analysis and modeling.
