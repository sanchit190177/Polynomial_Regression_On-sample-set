# Polynomial_Regression_On-sample-set
# Polynomial Regression

## Overview
This project demonstrates Polynomial Regression using Scikit-learn's `PolynomialFeatures` and `LinearRegression` on a synthetically generated quadratic dataset. It covers feature transformation, model training, and smooth curve visualization.

## Concepts Covered
- Polynomial Feature Transformation using `PolynomialFeatures`
- Linear Regression on transformed features
- Difference between `fit_transform()` and `transform()`
- Smooth curve plotting using `np.linspace`
- Overfitting intuition (degree 4 on degree 2 true function)

## Tech Stack
- Python, NumPy, Scikit-learn, Matplotlib

## True Function
y = 0.5x² + x + 2 + noise (true degree-2) | Model fitted at degree-4

## How to Run
pip install numpy scikit-learn matplotlib

## Output
- Printed model weights and bias for all 4 degrees
- Scatter plot of data points (dark red)
- Smooth polynomial fit curve (blue)

## Author
**Sanchit Bhandari** — B.Tech CSE & Data Science | PSIT Kanpur
