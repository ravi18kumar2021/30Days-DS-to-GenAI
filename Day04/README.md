# 📅 Day 4: Linear Regression (Simple & Multivariable)

## ✅ Topics Covered
- Linear regression fundamentals (simple and multiple)
- Ordinary Least Squares (OLS) derivation
- Understanding intercept and slope
- Model evaluation metrics: R², MSE, RMSE, MAE
- Overfitting, multicollinearity, and model assumptions
- scikit-learn modeling workflow
- VIF (Variance Inflation Factor) for multicollinearity check

## 🛠 Tools
- Python 3.x
- NumPy, pandas
- scikit-learn
- statsmodels (for VIF)
- Google Colab / Jupyter Notebook

---

## 💡 Mini Project: Car Price Prediction (Multivariable Regression)

- Dataset: [Car Price Prediction Dataset](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
- Target: `price`
- Features: All numeric columns (e.g., `enginesize`, `horsepower`, `curbweight`, etc.)

### 🔍 Key Tasks
- Build own Linear Regression Model
- Select and preprocess numerical features
- Check for multicollinearity using VIF
- Train linear regression model using scikit-learn
- Evaluate using:
  - R² Score
  - RMSE
- Analyze learned coefficients

### 🔬 Observations
- Most features showed high VIF values
- Model trained using all features for baseline
- Will revisit feature selection and regularization in future days
