# Real-Estate-House-Price-Prediction-Using-Machine-Learning
📊 Real Estate House Price Prediction using Machine Learning. Built multiple regression models (Linear, Ridge, Lasso, XGBoost, etc.) to predict property prices from real-world housing data. Includes preprocessing, visualization, and model evaluation.

# 🏠💡 Real Estate House Price Prediction Using Machine Learning

**Project Type**: Machine Learning | Regression  
**Dataset**: Makaan_Properties_Buy_Dataset.csv  
**Goal**: Predict real estate prices using features like location, size, number of BHKs, and property status.

---

## 🎯 Objective

Build a regression-based prediction model to estimate property prices using various ML algorithms.  
This project focuses on core data science concepts such as:

- Data Cleaning & Feature Engineering  
- Label Encoding & Standardization  
- Regression Modeling & Evaluation  
- Visualization & Outlier Detection

---

## 📂 Dataset Overview

**Features Used**:
- `Property_type`
- `Property_status`
- `City_name`
- `Size`
- `No_of_BHK`
- `Price_per_unit_area`
- `is_furnished`
- `is_RERA_registered`

**Target**: `Price` (Continuous Value in ₹)

---

## 🔍 Workflow Summary

### 1️⃣ Data Cleaning & Preparation
- Dropped irrelevant columns (e.g. `Property_ID`, `builder_id`, etc.)
- Handled missing values using mode
- Applied Label Encoding to categorical columns

### 2️⃣ Exploratory Data Analysis (EDA)
- Used boxplots, violin plots, and heatmaps for visualization
- Dropped less impactful features
- Analyzed feature correlations

### 3️⃣ Feature Engineering
- Scaled numerical features using `StandardScaler`
- Defined `X` (input features) and `y` (target)

### 4️⃣ Model Building & Comparison
- Split data into training and testing sets
- Implemented and evaluated:
  - ✅ Linear Regression
  - ✅ LassoCV / RidgeCV / ElasticNetCV
  - ✅ Decision Tree Regressor
  - ✅ Random Forest Regressor
  - ✅ XGBoost & LightGBM

### 5️⃣ Evaluation
- Used `r2_score` for model accuracy
- Compared training vs testing scores
- Selected the best-performing model

---

## 📊 Key Insights

- Tree-based models like **Random Forest** handled complex patterns well  
- `r2_score` was effective for model evaluation  
- Scaling and encoding improved performance  
- Outlier analysis helped reduce model bias

---

## 🛠 Tools & Technologies Used

- **Programming**: Python  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `lightgbm`, `matplotlib`, `seaborn`  
- **IDE/Environment**: Jupyter Notebook  

---

## ✅ Conclusion

This project provided end-to-end experience in building a regression model using real-world housing data.  
It enhanced my understanding of preprocessing, model comparison, and performance evaluation.

