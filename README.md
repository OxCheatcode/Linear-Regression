# Linear Regression Labs (ISLP, Chapter 3)

This repository contains my practice notebooks from *An Introduction to Statistical Learning with Python (ISLP)*, Chapter 3 labs.  
The focus is on linear regression, extending from simple models to more flexible approaches using the typical Boston Housing Data of houses around
Boston neighborhood from 2005 to create a model which predicts future house prices

---

## 📌 Topics Covered

1. Simple Linear Regression
   - Fitting medv ~ lstat (Boston dataset)
   - Interpreting coefficients
   - Confidence intervals & hypothesis testing
   - Residual plots & diagnostics

2. Multiple Linear Regression
   - Adding predictors
   - Checking model fit with R² and adjusted R²
   - Assessing statistical significance

3. Polynomial Regression
   - Adding polynomial terms (poly(lstat, degree=2,3,...))
   - Capturing curvature in relationships
   - Model comparison with ANOVA

4. Interaction Terms
   - Modeling joint effects (rm * lstat)
   - Interpreting interactions

5. Qualitative Predictors
   - Using dummy variables for categorical data
   - Example: chas (Charles River indicator)

6. Model Diagnostics
   - Variance Inflation Factor (VIF) for multicollinearity
   - ANOVA for nested models
   - Residual analysis for assumptions

---

## 🛠 Tools & Libraries
- Python (3.9+)
- pandas, numpy
- statsmodels
- matplotlib
- ISLP package

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/islp-linear-regression.git
   cd islp-linear-regression
