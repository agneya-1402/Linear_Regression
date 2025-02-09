# Implementing Linear Regression from Scratch

This repository contains an implementation of Linear Regression from scratch using Python. The code demonstrates how to build a simple linear regression model without relying on machine learning libraries like Scikit-Learn.

## Reference
This implementation was inspired by the following article:
https://medium.com/@pritioli/implementing-linear-regression-from-scratch-747343634494

## Features
- Implements Linear Regression using NumPy
- Supports batch gradient descent
- Visualizes the regression line and data points
- Evaluates model performance using Mean Squared Error (MSE)

## Installation
Ensure you have Python installed along with the required libraries. You can install dependencies using:

```bash
pip install numpy matplotlib
```

## Usage
Run the Jupyter Notebook to see the step-by-step implementation:

```bash
jupyter notebook LinearRegression.ipynb
```

## Files
- `LinearRegression.ipynb` - Jupyter Notebook with the complete implementation and explanations

## How It Works
1. Load the dataset
2. Implement hypothesis function: `y = mx + c`
3. Compute the cost function (MSE)
4. Implement gradient descent to optimize parameters
5. Train the model and visualize results

## Results
The notebook includes visualizations of the fitted regression line over sample data points and a performance evaluation.

## License
This project is licensed under the MIT License.

