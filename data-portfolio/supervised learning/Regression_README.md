# House Price Prediction (Regression)

## 📌 Project Overview
This project aims to predict housing prices using regression models. The dataset used was King County House Sales data from Kaggle.

## 📊 Dataset
- King County housing dataset (21,000+ entries).
- Features: Number of bedrooms, bathrooms, sqft living, location, etc.
- Target variable: Sale price.

## 🛠 Methods
- Feature engineering (log-transformations, removing outliers).
- Regression models tested:
  - Linear Regression
  - Ridge & Lasso Regression
  - Random Forest Regressor
- Evaluation metrics:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² score

## 📈 Results
- Random Forest Regressor achieved the lowest MAE (~$35,000).
- Key drivers of house price: sqft_living, location, grade.

## 🧰 Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
