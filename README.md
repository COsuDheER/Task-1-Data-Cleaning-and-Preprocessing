# Task-1-Data-Cleaning-and-Preprocessing
Datasets used:Titanic Dataset from kaggle "https://www.kaggle.com/datasets/yasserh/titanic-dataset"
This repository contains a Python notebook detailing a comprehensive data preprocessing and cleaning workflow. Using the Titanic dataset, I've demonstrated how to prepare raw data for machine learning models by performing the following key steps:
Handling Missing Values:I used mean imputation to fill in missing numerical data in the 'Age' column.
Encoding Categorical Features: I converted categorical features like 'Sex' and 'Embarked' into a numerical format using One-Hot Encoding.
Scaling Numerical Features: I standardized numerical data such as 'Age' and 'Fare' to ensure all features are on a similar scale, which is essential for many machine learning algorithms.
Outlier Detection & Removal: I visualized and identified outliers in the 'Fare' column using boxplots and removed them using the Interquartile Range (IQR) method to improve model performance.

This project serves as a practical guide to essential data cleaning techniques, showcasing how to transform messy, real-world data into a clean, structured format suitable for analysis and modeling.
