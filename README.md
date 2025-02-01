# 🏡 HOUSE PRICE PREDICTION WITH MACHINE LEARNING

## 📌 Project Overview
This project aims to predict house prices using machine learning techniques. **LightGBM** and **CatBoost** models are used to optimize the balance between performance and processing time. The dataset is sourced from Kaggle's ["House Prices - Advanced Regression Techniques"](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition.

## 🔍 Key Features
- **Data Preprocessing:** Handling missing values, outlier detection, and categorical feature transformation.
- **Feature Engineering:** Creating new features such as total floor area, lot ratio, and overall quality score.
- **Model Comparison:** Evaluating LightGBM and CatBoost models in terms of speed and accuracy.
- **Hyperparameter Optimization:** Using GridSearchCV to fine-tune model parameters and prevent overfitting.
- **Model Validation:** Applying cross-validation to assess the generalization performance of the model.

## 📂 Dataset
The project dataset consists of **train.csv** and **test.csv** files.  
- **Target Variable:** `SalePrice`  
- **Features:** 80+ variables, including `LotArea`, `OverallQual`, `GrLivArea`, `YearBuilt`, etc.

## 🛠️ Technologies Used
- **Python 3.12.4**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM, CatBoost

## 🚀 Model Selection and Findings
- **CatBoost provides lower RMSE but has a longer computation time.**
- **LightGBM is significantly faster while maintaining an acceptable accuracy level.**
- **Hyperparameter tuning was carefully adjusted to prevent overfitting.**
