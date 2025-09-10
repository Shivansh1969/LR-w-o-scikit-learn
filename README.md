# Linear Regression from Scratch

A simple project implementing **Linear Regression** with one predictor and one target variable, without using scikit-learn or similar libraries. The main purpose is to understand and demonstrate the mathematical workings of Linear Regression through manual coding and visualization.

---

## Motivation

This project was created for learning purposes, to build a fundamental understanding of how linear regression models work internally–especially the role of the cost function, gradients, and iterative parameter updates. The focus is on clarity, transparency, and step-by-step computation.

---

## Project Features

- Univariate Linear Regression (one feature, one target)
- Manual Gradient Descent implementation
- Clear mathematical code structure
- Visualization of fitted line versus data points

---

## Mathematical Formulation

- **Compute Means**
  
  x̄ = (1/n) Σ x_i
  ȳ = (1/n) Σ y_i

- **Sum of Squares**

  SSxx = Σ (x_i - x̄)^2
  SSxy = Σ (x_i - x̄)(y_i - ȳ)

- **Slope (m) and Intercept (c)**

  m = SSxy / SSxx
  c = ȳ - m * x̄

- **Regression Model**

  ŷ = m * x + c

---

## Getting Started

### Requirements

- Python 3.x
- NumPy
- Matplotlib
- pandas
