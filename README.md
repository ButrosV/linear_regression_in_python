## Goal of the project
Implement in Python a Linear Regression model using two different approaches: the Closed-form solution (Least Squares normal equation) and Gradient Descent optimization.

## Description
This project experiments with fitting a linear model to a set of data points to make predictions. It implements two different methods to compute the model parameters:

1. Least Squares Solution (Closed-form): This method uses the Normal Equation, an analytical solution that directly minimizes the Mean Squared Error (MSE) to find the optimal model parameters.
2. Gradient Descent: This method uses an iterative optimization technique that adjusts model parameters step-by-step in the direction of the gradient of the cost function, aiming to converge to the optimal solution.
The project provides implementations of both methods, along with functions to compute the Mean Squared Error (MSE), add a bias term (intercept) to the feature matrix, and generate synthetic data for testing and visualization.

The solution is implemented in a Jupyter notebook.

## Installation
Project dependencies/required python libraries:
- numpy
- matplotlib
- scipy.stats (For probplot)
- jupyter notebook

## Usage
1. Run Notebook:
    - Make sure to run hepler functions `random_color()` and `random_colormap()`, otherwise graph plotting function may produce errors.
2. If superimposed data in LeastSquaresRegression() and 3D f-function visualizations are not clearly visible, run the corresponding cells again so that different random color patterns are implemented.

### Author
Butros
