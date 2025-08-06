# Fraud Detection Analysis

## Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning.  
The analysis includes data exploration, feature engineering, multicollinearity checks, and model interpretation to build a reliable fraud detection system.

- Goal: Identify fraudulent transactions and reduce false positives in financial systems.  
- Data: Anonymized transactional dataset with multiple features (amount, transaction type, time, etc.).  
- Tools & Libraries: Python (pandas, numpy, scikit-learn, matplotlib, seaborn), Jupyter Notebook.  

---

## Analysis Workflow

### 1. Data Import & Overview
- Loaded anonymized transaction dataset, reviewed feature distributions, and identified data types.
- Evaluated potential multicollinearity among features to prevent redundancy in modeling.

### 2. Exploratory Data Analysis (EDA)
- **By Transaction Type:**  
  Analyzed fraud rates across different transaction types (e.g., TRANSFER, CASH_OUT).
- **By Amount Segmentation:**  
  Examined transaction amount distributions (log-transformed for normalization) and their relationship with fraud likelihood.
- **By Time Trend:**  
  Investigated fraud occurrence patterns over time and by hour of day.

### 3. Feature Importance
- **Statistical Tests:**  
  Conducted T-tests and Chi-squared tests to determine statistically significant features.
- **Permutation Importance:**  
  Assessed feature importance using model-based permutation techniques to understand their predictive power.

### 4. Model Evaluation
- Built baseline models and evaluated performance using a confusion matrix and classification metrics.

---

## Key Insights
- Fraudulent transactions were most common in specific transaction types (e.g., TRANSFER and CASH_OUT).  
- Log-transformed amounts revealed clearer thresholds for distinguishing fraudulent behavior.  
- Certain balance differences (origin/destination) were strong indicators of fraud.  
- Statistical tests and permutation importance highlighted features most correlated with fraud likelihood.  

---

## Key Visualizations


### Transaction Analysis
<img src="./images/amount_distribution_transfer.png" width="48%"> <img src="./images/amount_distribution_cashout.png" width="48%">
<img src="./images/boxplot_transaction_amount.png" width="48%"> <img src="./images/amount_distribution_log_transformed.png" width="48%">

### Balance & Time Trends
<img src="./images/balance_diff_dest_boxplot.png" width="48%"> <img src="./images/balance_diff_dest_distribution.png" width="48%">
<img src="./images/transactions_frauds_over_time.png" width="48%"> <img src="./images/fraud_spikes_by_hour.png" width="48%">

### Feature Analysis & Model
<img src="./images/feature_correlation_isfraud.png" width="48%"> <img src="./images/feature_significance_tests.png" width="48%">
<img src="./images/confusion_matrix.png" width="48%"> <img src="./images/transactions_scatter_scaled.png" width="48%">

---

Author: Sera Park  
Contact: sera.park.2026@anderson.ucla.edu  
