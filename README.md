# Linear Regression: Least Squares, Scikit-learn, and Gradient Descent Comparison

This project implements and compares linear regression using three different approaches: traditional least squares, scikit-learn's LinearRegression, and gradient descent. The goal is to showcase diverse regression methodologies and provide insights into model performance and accuracy.

## Table of Contents
- [Introduction](#introduction)
- [Methods](#methods)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Linear regression is a fundamental machine learning algorithm used for modeling the relationship between a single independent variable and a dependent variable. In this project, we explore three distinct methods to perform linear regression and compare their results. The methods employed are:
1. Least Squares Method
2. Scikit-learn's LinearRegression
3. Gradient Descent

## Methods

### 1. Least Squares Method

The least squares method is a classical approach to linear regression, calculating the line of best fit that minimizes the sum of the squared differences between the observed and predicted values.

### 2. Scikit-learn's LinearRegression

Scikit-learn is a widely used Python library for machine learning. We utilized the LinearRegression module from scikit-learn to perform linear regression on the provided dataset, showcasing its ease of use and efficiency.

### 3. Gradient Descent

Gradient descent is an iterative optimization algorithm used for finding the minimum of a function. We implemented gradient descent to iteratively adjust model parameters to minimize the mean squared error, demonstrating a foundational optimization technique.

## Usage

To run the project and observe the comparison of linear regression methods, follow these steps:
1. Clone the repository.
2. Ensure you have the necessary dependencies installed (NumPy, scikit-learn).
3. Run the provided code and analyze the results.

## Results

We compared the obtained coefficients (slope and intercept) and costs (mean squared error) from each method. Here are the summarized results:
- Least Squares:
  - Slope (m): 1.3530129888064268
  - Intercept (c): 6.481604578730057
  - Cost: 110.34548507080449
- Scikit-learn's LinearRegression:
  - Coefficient (m): 1.35301299
  - Intercept (c): 6.481604578729701
  - Training Score: 0.6454504815883391
  - Testing Score: 0.438073496767603
- Gradient Descent:
  - Slope (m): 1.4788956622797287
  - Intercept (c): 0.0302695172877759
  - Cost: 112.64994426496072

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
