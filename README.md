# 🏠 USA Housing Price Prediction using Linear Regression

Welcome to my data science project focused on predicting housing prices using various regression techniques. This project involves end-to-end data analysis—from cleaning and visualization to machine learning model building and evaluation.

---

## 📌 Project Objective

To analyze the **USA Housing dataset** and predict **house prices** using multiple regression models. This includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model evaluation.

---

## 🗃️ Dataset

- **Source**: [Kaggle Dataset (USA Housing)](https://www.kaggle.com/datasets)
- **Attributes**:
  - `Avg_Area_Income`
  - `Avg_Area_House_Age`
  - `Avg_Area_Number_of_Rooms`
  - `Avg_Area_Number_of_Bedrooms`
  - `Area_Population`
  - `Price` (Target Variable)
  - `Address` (Categorical)

---

## 🧰 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model training and evaluation |
| Statsmodels | OLS regression and statistical summary |

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized distributions of features using **distplots** and **boxplots**
- Analyzed **correlation matrix** using heatmaps
- Detected and treated **outliers** using **quantile-based capping**
- Encoded categorical variables (`Address`) with label encoding

---

## ⚙️ Feature Engineering

- Converted `Address` into numerical codes
- Handled missing values (if any) using `fillna()`
- Scaled numerical features using `StandardScaler`
- Separated features and target for model building

---

## 🤖 Machine Learning Models Applied

1. **Ordinary Least Squares (OLS)** – via `statsmodels`
2. **Linear Regression** – `sklearn.linear_model.LinearRegression`
3. **Ridge Regression**
4. **Lasso Regression**
5. **SGD Regressor** – Stochastic Gradient Descent

---

## 🧪 Model Evaluation Metrics

- **R² Score** – Goodness of fit
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **Variance Inflation Factor (VIF)** for multicollinearity detection

---

## 📈 Results Summary

- Compared performance across all models
- Visualized residuals and predictions
- Interpreted model coefficients
- Found that features like `Avg_Area_Income` and `Area_Population` were strong predictors of price

---

## 📚 Key Learnings

- Solidified understanding of **regression techniques**
- Learned practical **data cleaning** and **feature engineering**
- Applied **statistical diagnostics** like VIF and OLS summary
- Understood the trade-offs between **Ridge**, **Lasso**, and **Linear Regression**

---

## 🗂️ Folder Structure
USA-Housing-Regression/
│

├── USA-Housing.ipynb                #Jupyter notebook with full code and analysis

├── USA_Housing.csv                  #Original dataset

├── README.md                        #Project documentation

├── requirements.txt                  #Python dependencies
