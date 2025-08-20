**Credit Card Fraud Detection Project (No-Code Edition)**
1. Project Overview
This project focuses on identifying patterns of fraudulent credit card transactions using a no-code approach. The objective is to analyze anonymized transaction data and develop visual tools that highlight suspicious activity. The final deliverables include a cleaned dataset, exploratory analysis, an interactive dashboard, and a professional report.

2. Tools Utilized
**Microsoft Excel** – Data cleaning, filtering, and preliminary analysis

**Google Looker Studio **– Development of interactive dashboards

**IBM Cognos Analytics** – Generation of structured reports and narrative insights

3. Dataset Description
Source: Kaggle – [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv)

Contains anonymized transaction records with a binary classification column ("Class") indicating fraudulent (1) or legitimate (0) transactions

Highly imbalanced dataset with approximately 0.17% fraudulent entries

4. Data Preparation
**Performed in Excel:**

Removal of duplicate records

Handling of missing values

Optional normalization and scaling of numerical features

Creation of derived columns:

Transaction hour

Amount categories (low, medium, high)

Weekend versus weekday indicator

Both raw and cleaned datasets are stored in the repository

5. Exploratory Analysis
**Using Excel pivot tables and charts:**

Fraud distribution by time of day and transaction amount

Frequency of fraud across anonymized features (V1–V28)

Comparison of average transaction amounts between fraudulent and non-fraudulent cases

Key findings are documented in findings.md

6. Dashboard Development
**Implemented in Google Looker Studio:**

Visualization of total versus fraudulent transactions

Time-based trends in fraud occurrence

Filters for transaction amount, time of day, and other variables

Use of conditional formatting to emphasize anomalies

7. Reporting
**Prepared in IBM Cognos Analytics:**

Summary statistics and visualizations

Narrative insights (e.g., increased fraud activity between 2–4 AM)

Recommendations for monitoring and prevention strategies

Final report exported as PDF and included in the repository
