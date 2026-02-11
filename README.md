Project Overview
This project builds a Machine Learning model to predict customer churn using a Kaggle dataset.
The objective is to identify customers who are likely to leave the company, helping businesses take proactive retention actions.
🎯 Problem Statement
Customer churn is a major challenge for subscription-based businesses.
Using historical customer data, this project predicts whether a customer will churn (Yes/No).
🛠️ Tech Stack
Python
Pandas
Scikit-learn
XGBoost (optional)
SQLite (for ETL storage)
📂 Project Structure
Copy code

├── raw/              # Raw dataset
├── processed/        # Cleaned datasets
├── output/           # SQLite DB / final outputs
├── model_training.py # ML training script
├── README.md
🔄 ETL Steps Performed
Loaded raw Kaggle CSV dataset
Created folder structure (raw/, processed/, output/)
Removed duplicates and handled missing values
Standardized column names and datatypes
Created derived columns (revenue, margin, segment flags)
Split data into Customers / Orders / Products tables
Exported outputs as CSV and SQLite database
Validated row counts before and after transformation
🤖 Machine Learning Workflow
Data Cleaning
Label Encoding / Feature Engineering
Train-Test Split (80/20)
Model Training:
Logistic Regression (Baseline)
Random Forest
XGBoost (optional)
Model Evaluation using:
Accuracy
Precision
Recall
F1 Score
ROC-AUC
📈 Model Performance
(Example – update with your actual results)
Model
Accuracy
ROC-AUC
Logistic Regression
0.80
0.85
Random Forest
0.84
0.89
XGBoost
0.87
0.92
