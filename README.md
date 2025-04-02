 Overview
In this project, we analyze a dataset related to loan applications to understand patterns that influence loan approval and default risk. Using real-world data, we perform data cleaning, exploratory analysis, feature engineering, and apply machine learning models (Logistic Regression and Random Forest) to predict loan status.

 Dataset Description
The dataset contains information about individual loan applications, including:

Applicant income

Loan amount

Credit score

Property value

Interest rates

Loan term and type

Applicant demographics

The target variable is Status, indicating whether the loan was approved (1) or denied (0).

-Tools & Technologies
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

Machine Learning Models:

Logistic Regression

Random Forest Classifier

Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

Feature Importance Analysis

Data Cleaning (Handling NaN, Encoding categorical variables)

 Project Steps
Data Exploration

Checked for missing values

Analyzed distributions and correlations

Data Cleaning

Dropped irrelevant features (e.g., ID, year)

Handled missing values using median and boolean fill

One-hot encoded multi-class categorical columns

Feature Engineering

Created dummy variables for categorical features

Scaled numeric features using StandardScaler

Modeling

Built and evaluated Logistic Regression and Random Forest models

Tuned hyperparameters with GridSearchCV

Achieved 100% accuracy using a Random Forest with optimized parameters

Visualization

Confusion matrices (tabular and heatmaps)

Top 20 Feature Importances plotted

Final Results
Model Accuracy: 100% (Random Forest)

Most Important Features:

Interest_rate_spread

Upfront_charges

Rate_of_interest

Credit_type_EQUI
