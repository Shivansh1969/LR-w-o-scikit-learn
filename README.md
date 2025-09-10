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

- **Model Equation**:  
  \( h(x) = m \cdot x + c \)

- **Cost Function (Mean Squared Error)**:  
  \[
    J(m, c) = \frac{1}{n} \sum_{i=1}^{n} (y_i - (m \cdot x_i + c))^2
  \]

- **Gradient Descent Updates**:  
  \[
    m := m - \alpha \frac{\partial J}{\partial m}
  \]
  \[
    c := c - \alpha \frac{\partial J}{\partial c}
  \]

---

## Getting Started

### Requirements

- Python 3.x
- NumPy
- Matplotlib
- pandas
