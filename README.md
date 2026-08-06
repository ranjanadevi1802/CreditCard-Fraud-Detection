# Credit Card Fraud Detection

An end-to-end Data Science project that detects fraudulent credit card transactions using Machine Learning and visualizes business insights through Power BI.

---

##  Dataset

This project uses the **Credit Card Fraud Detection** dataset from Kaggle.

The dataset contains **284,807** anonymized credit card transactions made by European cardholders over two consecutive days in **September 2013**. Among these transactions, **492 are fraudulent**, representing only **0.172%** of the data, making it a highly imbalanced binary classification problem.

**Dataset Source:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

> **Note:** The dataset is not included in this repository due to its size. Download `creditcard.csv` from Kaggle and place it inside the `data/` directory before running the notebooks.

---

##  Key Features

- **Time** – Seconds elapsed between each transaction and the first transaction in the dataset.
- **Amount** – Transaction amount.
- **V1–V28** – Principal Components (PCA-transformed features) used to preserve customer confidentiality.
- **Class** – Target variable:
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction

---

##  Project Goals

This project aims to perform an end-to-end Data Science workflow for credit card fraud detection by:

- Cleaning and preprocessing the dataset.
- Performing Exploratory Data Analysis (EDA).
- Handling class imbalance.
- Engineering useful features.
- Training multiple Machine Learning models.
- Evaluating model performance.
- Generating business insights.
- Building an interactive Power BI dashboard.

---

##  Current Progress

| Stage | Status |
|-------|--------|
| Dataset Collection | ✅ Completed |
| Project Setup | ✅ Completed |
| Data Cleaning | ✅ Completed|
| Data Preprocessing | ✅ Completed |
| Exploratory Data Analysis (EDA) | ✅ Completed |
| DAX Measures | ✅ Completed|
| KPI Cards | ⏳ Planned |
| Dashboard Visualizations | ⏳ Planned |
| Dashboard Formatting & Design | ⏳ Planned |
| Power BI Dashboard | ⏳ Planned |

---

##  Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Preprocessing
      │
      ▼
Exploratory Data Analysis
      │
      ▼
DAX Measures and KPI
      │
      ▼
Dashboard Visualizations
      │
      ▼
Final Power BI Dashboard
```

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code
- Jupyter Notebook
- Power BI
- Git & GitHub

---

##  Evaluation Metrics

Since the dataset is highly imbalanced, the models will be evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Precision-Recall Curve (PR-AUC)
- Confusion Matrix

---

##  Planned Dashboard

The final Power BI dashboard will include:

- Total Transactions
- Fraud vs Legitimate Transactions
- Fraud Percentage
- Transaction Amount Distribution
- Fraud Trends
- Feature Importance Analysis
- Interactive Filters
- Business Insights

---

##  Development Approach

This repository is updated regularly as the project progresses. Each stage of the Data Science workflow is committed separately to document the complete development process.

---

## ⭐ Repository Status

 **Work in Progress**

This repository is actively maintained and updated with new notebooks, analyses, machine learning models, and Power BI dashboards as the project progresses.