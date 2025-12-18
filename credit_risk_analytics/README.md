# Credit risk analytics & Loan Default Prediction
This project focuses on analyzing customer-level loan data to understand **credit risk patterns** and they predict and examine the likelihood of loan default. 
The dataset was **manually generated using a custom Python script**and this simulate realistic banking behavior.

---
## Problem Statement
Banks need to identify risky customers early to reduce loan defaults.
In this project, I have totatly analyze customer financial behavior and build **rule-based** and **machine-learning-based** risk indicators.

---

## Dataset
- Generated using `generate_data.py`
- ~200+ customer records
- Each row represants a loan customer

**Key columns:**
- customer_id
- income
- loan_amount
- credit_score
- late_payments
- loan_status(1 = default, 0 = non-default)

---

## Tools & Technologies
- Python
- Pandas
- SQLite 
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Analysis steps
1. Data loading & quality checks
2. Feature engineering (laon-to-income, risk flags)
3. Rule-based high-risk customer identification
4. SQL- based risk segmentation using SQLite
5. logistic Regression model is for the default prediction 
6. Visualization and business insights

---

## key Insights
- Customers with **low credit scores** and **high loan-to-income ratios** which shows higher default risk.
- Rule-based  risk flags aligend well with machine learning predictions.
- SQL analysis clearly shows that the incresing default rates which are in lower credit score buckets.

---

## How to Run
```bash
pip install pandas matplotlib scikit-learn
jupyter notebook
