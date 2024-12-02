# Python Assignment 3

This repository contains the solution to Python Assignment 3, which explores a variety of numerical methods and machine learning algorithms, including Gradient Descent, Linear Regression, Logistic Regression, and Image Classification.

## Objectives

The assignment is structured to:

1. Enhance problem-solving skills using Python.
2. Implement and optimize machine learning algorithms.
3. Visualize results for better understanding and interpretation.
4. Familiarize with using Jupyter Notebooks for clear documentation and reproducibility.

## Project Tasks

### 1. Good Presentation of Code and Outputs (10 pts)
- Ensure well-commented code.
- Add titles, legends, and axis labels for plots.
- Divide code into logical blocks for better readability.

### 2. Gradient Descent Implementation (60 pts)
- Function: \(f(x) = \sqrt{x^2 + 5}\)
- Tasks:
  - Derive and plot the function.
  - Implement Gradient Descent with multiple step sizes.
  - Analyze and visualize convergence rates.
- **Sample Output:**
  ![Gradient Descent Example](results/linear_regression_gradientDescent.png)

### 3. Linear Regression (30 pts)
- Generate synthetic 2D data.
- Perform linear regression using the normal equation.
- Plot data and the regression plane.
- **Sample Output:**
  ![Linear Regression Plot](results/linear_regression_plane.png)

### 4. Logistic Regression (20 pts)
- Fine-tune learning rate and epochs.
- Add meaningful comments to the provided logistic regression code.
- **Sample Output:**
  ![Logistic Regression Example](results/logistic_boundary_train.png)
  ![Logistic Regression Example](results/logistic_boundary_train.png)

### 5. Image Binary Classification (30 pts)
- Implement a binary classification model.
- Analyze and display misclassified test cases.
- Re-train and evaluate the model using a modified dataset.
- **Sample Output:**
  ![Misclassified Images](images/misclassified_examples.png)

## Results Summary

### Gradient Descent
- Final \(x_T\) for various step sizes:
  - \(0.1\): 5.22
  - \(0.5\): 0.0007
  - \(1.0\): ~0

### Linear Regression
- Intercept: 3.80
- Coefficients: [4.11, 0.47]

### Logistic Regression
- Training Accuracy: 88%
- Test Accuracy: 100%

### Image Classification
- Training Accuracy: 88%
- Test Accuracy: 100%
- Misclassified examples displayed.