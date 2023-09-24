# Linear Regression Project

## Project Overview

Welcome to the Linear Regression Project for a Machine Learning course. This project delves into linear regression, gradient descent, and multiple output regression for predicting real values from input data.

## Table of Contents

1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [LinearRegression Class](#linearregression-class)
   - 3.1 Fit Function
   - 3.2 Predict Function
   - 3.3 Score Function
   - 3.4 RMSE Function
4. [Regression with Single Output](#regression-with-single-output)
   - Model 1
   - Model 2
   - Model 3
   - Model 4
   - Model 4 with Ridge Regularization
   - Weight Matrix Comparison
   - Conclusion
5. [Regression with Multiple Outputs](#regression-with-multiple-outputs)
   - Data Preparation
   - Model Training
   - Testing and Optimization

## Project Structure

The project is structured as follows:

- `linear_regression.py`: Contains the implementation of the `LinearRegression` class.
- `regression_models.py`: Includes various regression models and experiments.
- `data/`: Directory for storing datasets used in the project.
- `results/`: Directory for storing project results and visualizations.
- `README.md`: This project documentation file.

## LinearRegression Class

In this section, we discuss the `LinearRegression` class and its functions.

### 3.1 Fit Function

The `fit` method accepts various parameters, including input data (X), target values (y), batch size, regularization factor, maximum epochs, patience, and learning rate. It initializes bias and weights, performs gradient descent, and employs early stopping for training.

### 3.2 Predict Function

The `predict` method accepts input data (X) and predicts target values using the learned model.

### 3.3 Score Function

The `score` method calculates the mean square error (MSE) loss between predicted and actual target values.

### 3.4 RMSE Function

The `rmse` function calculates the root mean square error (RMSE) for evaluating model performance.

## Regression with Single Output

In this section, we explore various regression models, input features, learning rates, and regularization to predict sepal length based on other features using the Iris dataset.

### Model 1:

- Input Features: Sepal Width and Petal Length
- Target: Sepal Length
- Learning Rate: 0.01, Regularization: 0

### Model 2:

- Input Features: Sepal Width and Petal Width
- Target: Sepal Length
- Learning Rate: 0.01, Regularization: 0

### Model 3:

- Input Features: Petal Length and Petal Width
- Target: Sepal Length
- Learning Rate: 0.01, Regularization: 0

### Model 4:

- Input Features: Sepal Width, Petal Length, and Petal Width
- Target: Sepal Length
- Learning Rate: 0.01, Regularization: 0

### Model 4 with Ridge Regularization:

- Input Features: Sepal Width, Petal Length, and Petal Width
- Target: Sepal Length
- Learning Rate: 0.01, Regularization: 0.001

The project includes weight matrix comparisons between regularized and non-regularized models, demonstrating their impact on bias and variance.

## Regression with Multiple Outputs

This section focuses on regression with multiple outputs, including data preparation, model training, testing, and optimization.

## Conclusion

The Linear Regression Project showcases the application of linear regression, gradient descent, and regularization techniques in predicting real values. It highlights the importance of hyperparameter tuning and regularization for model accuracy and robustness.

For detailed code implementation and results, please refer to the respective sections and files in the project directory.
