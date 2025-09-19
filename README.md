# 🚗 Used Car Price Prediction

This project predicts the **selling price of used cars** using machine learning techniques.  
The main goal was to **showcase data exploration, feature engineering, and advanced ensemble modeling skills**.

---

## 📊 Dataset
- Shape: **4300 rows × 9 columns**
- Contains features related to car attributes (e.g., year, present price, fuel type, etc.).
- Target variable: **Selling Price**.

---

## 🔍 Project Workflow

### 1. Data Exploration
- Performed **univariate and bivariate analysis**.
- Checked data distribution, missing values, and outliers.
- Created meaningful visualizations to better understand the relationships between variables.

👉 You can view all visualizations here:  
[📂 Visualizations Folder](./Visualiaztons)

### 2. Data Preprocessing
- **Cleaning**: Handled missing values and outliers.
- **Feature Engineering**: Added new relevant columns for better prediction.
- **Feature Encoding**: Converted categorical variables into numeric form.
- **Feature Scaling**: Standardized numerical features.

### 3. Machine Learning Models
- Trained multiple regression models to predict car prices.
- Implemented a **Stacking Ensemble Regressor**:
  - **Base Models**:
    - Support Vector Regressor (SVR)
    - Random Forest Regressor
    - Gradient Boosting Regressor
    - XGBoost Regressor
  - **Meta-Model**: Linear Regression
  - Used **5-Fold Cross Validation** and passthrough for better generalization.

### 4. Model Evaluation
- Evaluated using **RMSE**, **R²**, and **Adjusted R²**.
- Stacking ensemble improved performance compared to individual models.

---

## 🛠 Tech Stack
- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy, Matplotlib, Seaborn** (Data Exploration & Visualization)
- **Scikit-learn, XGBoost** (Modeling)

---

## 🎯 Goal
The primary goal of this project was to **demonstrate strong data exploration and visualization skills**, along with applying a **stacking ensemble method** to improve regression performance.

---

## 📂 Files
- `Car_Price_Prediction.ipynb` → Main notebook containing analysis & modeling  
- `Car.csv` → Dataset (4300 × 9)  
- `Visualiaztons/` → Folder with plots and visualizations  
- `README.md` → Project documentation  

---
