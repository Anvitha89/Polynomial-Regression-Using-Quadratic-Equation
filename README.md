# Polynomial Regression Using Quadratic Equation

## 📌 Overview

This project demonstrates Polynomial Regression using Python and Scikit-learn. A synthetic dataset is generated using a quadratic equation, and a Linear Regression model is trained using polynomial features to predict the output.

## 🎯 Objectives

- Understand Polynomial Regression.
- Generate synthetic data using a quadratic equation.
- Transform input features into polynomial features.
- Train a Linear Regression model.
- Make predictions and evaluate model performance.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The dataset is synthetically generated using the following equation:

**y = 0.5x² + x + 2 + noise**

Random noise is added to make the data more realistic.

## ⚙️ Implementation Steps

1. Generate synthetic data.
2. Transform the input data using `PolynomialFeatures` with degree 2.
3. Train a `LinearRegression` model.
4. Predict output values using the trained model.
5. Evaluate the model using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

## 📈 Model Evaluation

The model is evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

- **MSE:** 0.9327
- **RMSE:** 0.9683

**Note:** These values may change when the notebook is executed again because the dataset contains randomly generated values and noise. Ensure both metrics are calculated from the same predictions.

## 🧠 Key Learnings

- Polynomial feature transformation
- Quadratic relationships between input and output
- Linear Regression with polynomial features
- Model prediction
- Model evaluation using MSE and RMSE

## 📝 Conclusion

This project demonstrates how Polynomial Features can help a Linear Regression model learn a nonlinear relationship between input and output variables.
