# Fraud Detection Analysis

## Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning.  
The analysis includes data exploration, feature engineering, multicollinearity checks, and model interpretation to build a reliable fraud detection system.

- Goal: Identify fraudulent transactions and reduce false positives in financial systems.  
- Data: Anonymized transactional dataset with multiple features (amount, transaction type, time, etc.).  
- Tools & Libraries: Python (pandas, numpy, scikit-learn, matplotlib, seaborn), Jupyter Notebook.  

---

## Analysis Workflow
1. Data Import & Overview  
   - Loaded and reviewed the dataset to understand key features, missing values, and distributions.

2. Exploratory Data Analysis (EDA)  
   - Analyzed transactions by type and amount segmentation.  
   - Examined temporal trends of fraudulent vs. non-fraudulent transactions.  

3. Multicollinearity Check 
   - Evaluated correlations between features to avoid redundancy and multicollinearity issues in the model.  

4. Feature Importance  
   - Applied statistical tests and permutation importance to identify the most significant predictors of fraud.

5. Modeling & Evaluation
   - Compared baseline classification models (e.g., Logistic Regression, Random Forest).  
   - Evaluated performance using Precision, Recall, F1-score, and ROC-AUC metrics.

---

## Key Insights
- Certain transaction types and time patterns significantly correlate with fraud probability.  
- Transaction amount segmentation provided clear thresholds where fraud likelihood increases.  
- Feature importance analysis revealed that transaction amount, type, and temporal behavior were strong predictors of fraudulent activity.

---

## Next Steps
- Implement advanced machine learning models (e.g., XGBoost, Gradient Boosting).  
- Address class imbalance with oversampling/undersampling techniques (SMOTE, etc.).  
- Build an API or dashboard for real-time fraud detection.  

---

Author: Sera Park  
Contact: sera.park.2026@anderson.ucla.edu  
