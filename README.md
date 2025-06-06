# ❤️ Heart Attack Risk Prediction with Logistic Regression

This project applies logistic regression to predict whether a patient is at risk of a heart attack, using a medical dataset containing clinical and lifestyle indicators.

The goal is to identify the most influential factors and evaluate model performance using standard classification metrics.

---

## 🧪 Key Objectives

- Clean and preprocess medical data for binary classification
- Engineer features from structured clinical data
- Train and evaluate a logistic regression model
- Visualize feature importance and prediction outcomes
- Interpret medical significance of results

---

## 📊 Tools & Libraries

- **Python** (Pandas, NumPy, Scikit-learn)
- **Visualization**: Seaborn, Matplotlib
- **Notebook Environment**: Jupyter

---

## 📁 Structure

- `notebook.ipynb` — full end-to-end workflow with code, visuals, and insights
- `/data/` — raw heart attack dataset (Kaggle-sourced)
- `/images/` — output charts and feature importance plots
- `README.md` — project overview and documentation

---

## 📌 Key Features

- Removal of non-predictive features (e.g., `Patient ID`, `Country`)
- One-hot and label encoding of categorical variables
- Blood pressure splitting into `Systolic` / `Diastolic` values
- Confusion matrix and performance metrics (Accuracy, Precision, Recall, F1)
- Coefficient-based feature interpretation
