# Term Deposit Prediction

This project aims to predict whether a client will subscribe to a term deposit using historical marketing campaign data from a Portuguese bank. It involves data exploration, visualization, and classification modeling to uncover key insights and build predictive models that can assist in more effective targeting of potential clients.

---

## Project Goals

- Perform **exploratory data analysis (EDA)** to understand customer behavior
- Identify patterns in **marketing campaign performance**
- Build **machine learning models** to predict subscription (`y`: yes/no)
- Generate **business insights** to enhance decision-making for future campaigns

---

## Problem Statement

Direct marketing campaigns are costly and time-consuming. By leveraging data from previous campaigns, we aim to build a predictive model that identifies likely subscribers to a term deposit — helping optimize marketing strategy and resource allocation.

---

## Dataset Overview

- **Records**: ~45,000 client records
- **Features**:
  - Client attributes: age, job, marital status, education, etc.
  - Contact campaign: type, duration, number of contacts
  - Past outcomes and loan details
  - **Target variable**: `y` — Did the client subscribe to a term deposit? (`yes` or `no`)

---

## Key Highlights

-  Clear and interactive visualizations with `seaborn` and `plotly`
-  Data cleaning and preprocessing
-  Insightful patterns: long call durations and successful past campaigns improve conversion
-  ML models: Logistic Regression, Decision Tree, Random Forest
-  Evaluation metrics: accuracy, confusion matrix, precision/recall

---

## Tools & Technologies

- **Python** (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- **Scikit-learn** (classification models & evaluation)
- **Jupyter Notebook**

---

## Results Summary

- **Random Forest** model showed the best overall performance.
- **Duration** of last contact is a highly influential feature.
- Clients with successful outcomes in previous campaigns had significantly higher subscription rates.

---

## Potential Next Steps

- Hyperparameter tuning with GridSearchCV or RandomizedSearchCV
- Introduce ensemble techniques like XGBoost
- Deploy model using Flask or Streamlit
- Implement real-time prediction for marketing platforms

---

---

> ✨ “Predict smart. Market smarter.”  
> _— This project empowers smarter decisions in financial marketing using data-driven insights._
