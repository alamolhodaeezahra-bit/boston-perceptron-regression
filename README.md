Boston Housing — Perceptron Regression (MLP) with 3D Surface Plot
This project trains an MLP Perceptron Regression model on the Boston Housing Dataset using two highly correlated features (RM and LSTAT) to predict MEDV (median home value).
A 3D surface representing the model’s predictions is generated along with the real data points.
📌 Project Overview
Load and preprocess the Boston Housing dataset
Compute correlations and select the most effective features
Train an MLPRegressor model for regression
Build a 2D feature grid using meshgrid
Predict values on the grid and reshape them into a 3D surface
Visualize:
  Model prediction surface
  Real data points
Files:
model.ipynb   — main notebook (training + visualization)
README.md     — project description
requirements:
  numpy
  pandas
  matplotlib
  scikit-learn
📊 Output
A 3D plot showing:
X-axis: RM (average number of rooms)
Y-axis: LSTAT (% lower-status population)
Z-axis: Predicted MEDV
with both the regression surface and actual data scatter points.
