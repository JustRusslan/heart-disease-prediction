# ❤️ Heart Attack Risk Prediction with Logistic Regression

This project demonstrates a complete end-to-end machine learning workflow to **predict the risk of heart attack** using a logistic regression model.

The notebook uses a public dataset from Kaggle containing health-related attributes such as age, cholesterol levels, blood pressure readings, and lifestyle habits. It includes data cleaning, feature engineering, model training, evaluation, and interpretation of results — providing a full view of how logistic regression can be applied in a medical context.

---

## 📌 What's Inside?

### 📂 **Data Exploration**
- Loading and inspecting the dataset from CSV.
- Checking for missing values, duplicates, and feature types.
- Summary statistics and correlation heatmap.

### ⚙️ **Preprocessing and Feature Engineering**
- Removing non-predictive features (`Patient ID`, `Country`).
- Encoding categorical variables using label and one-hot encoding.
- Splitting compound values like `Blood Pressure` into `Systolic_BP` and `Diastolic_BP`.

### 🧠 **Model Training**
- Train-test split with stratification to preserve class balance.
- Logistic regression model with `class_weight='balanced'` to handle imbalanced data.
- Visualization of learned model coefficients.

### 📊 **Evaluation and Results**
- Performance metrics: **accuracy**, **precision**, **recall**, and **F1-score**.
- Confusion matrix visualization.

### 🔍 **Interpretation and Insights**
- Analysis of top positive and negative predictors.
- Discussion of model limitations and real-world applicability.

### 🖼️ **Visualizations**
- Correlation heatmap for exploring feature relationships.
- Confusion matrix for classification evaluation.
- Bar plot of top influential features based on model coefficients.

---

## 🧰 Tech Stack

- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: scikit-learn  
- **Environment**: Jupyter Notebook
