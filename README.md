# Linear Regression: Predicting Fuel Efficiency (MPG)

> A hands-on regression project exploring how linear relationships between vehicle characteristics can be used to accurately predict fuel efficiency. This project demonstrates practical data preprocessing, exploratory analysis, and model development using industry-standard tools in Python.

## 🚀 Project Summary

This project builds and evaluates a **linear regression model** to predict **Miles Per Gallon (MPG)** of vehicles using attributes such as engine displacement, horsepower, weight, and acceleration. It highlights the power and limitations of simple regression models and emphasizes the importance of feature relationships and data integrity in machine learning pipelines.

---

## 📊 Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (`LinearRegression`, `train_test_split`, metrics)
- **Jupyter Notebook**
- **Mathematical Modeling** (OLS regression, R² score, residual analysis)

---

## 📁 Dataset Overview

The dataset used contains technical specifications of vehicles, including:

- `mpg`: Miles per gallon (target variable)
- `displacement`, `horsepower`, `weight`, `acceleration`: Independent variables
- `origin`: Region code (used for future expansion)

This dataset is a classic benchmark for regression models in the automotive domain.

---

## ⚙️ Workflow Breakdown

### 1. **Data Preparation**
- Cleaned and standardized column names
- Handled missing or malformed entries
- Converted data types for numerical consistency

### 2. **Exploratory Data Analysis (EDA)**
- Visualized distributions of all variables
- Used scatterplots to identify linear relationships
- Detected correlations to prioritize features

### 3. **Model Development**
- Built a linear regression model with scikit-learn
- Split data into training (80%) and testing (20%) sets
- Trained and tested using key variables like displacement and horsepower

### 4. **Performance Evaluation**
- Calculated **R² (coefficient of determination)** to assess model accuracy
- Visualized predicted vs. actual MPG
- Plotted **residuals** to diagnose variance and bias

---

## 📈 Key Results

- The model demonstrated a clear linear relationship between **engine displacement** and **fuel efficiency**.
- Residual plots revealed areas for improvement, such as variance at higher MPG values.
- R² score provided a transparent view of how well the model captured variance in the data.

---

## 💡 Learning Outcomes

- Developed intuition around linear modeling assumptions and trade-offs
- Strengthened skills in data cleaning, visualization, and scikit-learn workflows
- Gained experience in interpreting regression metrics and debugging models

---

## 🔁 Potential Improvements

- Incorporate **multivariate regression** with more predictors
- Apply **feature scaling** and polynomial regression
- Experiment with **regularization techniques** (Ridge, Lasso)


