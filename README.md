Financial Fraud Detection using Machine Learning

Problem Statement

Financial fraud poses a critical threat to digital payment systems, resulting in significant monetary losses and erosion of customer trust. This project focuses on building a robust machine learning model to proactively detect fraudulent transactions in a financial dataset of over 6 million records.

The goal is to accurately classify transactions as fraudulent or legitimate by performing thorough data cleaning, exploratory analysis, and feature engineering — then training and evaluating multiple ML models. Beyond prediction, the project interprets key fraud indicators and proposes an actionable prevention strategy along with a measurable evaluation framework.

Dataset

The dataset simulates 30 days of mobile money transactions (744 hourly steps) with the following features: transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER), transaction amount, origin/destination account balances before and after the transaction, and fraud labels. Fraudulent behavior in this dataset specifically targets account takeovers — draining funds via transfers followed by cash-outs.

The dataset is too large to host here (500MB+). Download it directly from Kaggle:
👉 https://www.kaggle.com/datasets/abhisek34/fraud-detect-data

After downloading, place `Fraud.csv` in the root of the project directory before running the notebook.
