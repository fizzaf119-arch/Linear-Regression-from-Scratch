# Linear Regression From Scratch (Univariate) — Assignment

This repository contains my implementation of **Univariate Linear Regression from scratch in Python** as part of my Machine Learning assignment. The goal of this task was to understand how Linear Regression actually works internally instead of using built-in regression models.

I implemented everything manually using only basic libraries for data handling and visualization.

---

##  Objective

The objective of this assignment is to learn and implement Linear Regression step by step, including:

* Loading and preprocessing a dataset
* Defining the hypothesis function
* Implementing the cost function (MSE)
* Applying Gradient Descent for optimization
* Visualizing actual vs predicted values

No built-in regression model functions were used.

---

##  Dataset

Dataset used: **real_estate_price_size.csv**

* Feature (X): Size
* Target (y): Price

This is a univariate dataset (one input feature and one output value).

---

##  Libraries Used

Only the following libraries were used (as required):

* numpy — numerical calculations
* pandas — dataset loading and preprocessing
* matplotlib — plotting graphs
* seaborn — improved visualization styling

No sklearn regression models were used.

---

##  Steps Performed

### 1️: Data Loading and Preprocessing

* Loaded CSV file from Google Drive
* Checked dataset structure and summary
* Handled missing values using dropna()
* Applied feature normalization to scale the size feature
* Split dataset into:

  * 80% training data
  * 20% testing data

---

### 2️: Hypothesis Function

Implemented the linear regression hypothesis function:

y_pred = theta0 + theta1 * X

This function predicts the output price based on input size.

---

### 3️: Cost Function (MSE)

Implemented Mean Squared Error cost function to measure prediction error:

* Calculated prediction error
* Squared the error
* Took the average
* Used 1/(2m) factor as defined in formula

This cost value shows how far predictions are from actual values.

---

### 4️: Gradient Descent

Implemented Gradient Descent algorithm from scratch:

* Initialized theta0 and theta1
* Computed partial derivatives
* Updated parameters using learning rate
* Repeated updates for fixed number of iterations
* Stored cost history to observe convergence

This step finds the optimal slope and intercept.

---

### 5:  Visualization

Generated graphs for:

* Actual vs Predicted regression line
* Cost reduction over iterations

These graphs help verify that the model is learning correctly.

---

##  Output

The model successfully:

* Learned optimal parameter values
* Reduced cost over iterations
* Produced a reasonable best-fit regression line
* Showed convergence in cost graph

---

##  What I Learned

Through this assignment I learned:

* How Linear Regression works internally
* How cost functions measure model error
* How Gradient Descent optimizes parameters
* Why feature scaling is important
* How to implement ML algorithms without built-in models
* How to visualize model performance

---

##  Note

This implementation is fully written from scratch for learning purposes and follows assignment constraints.

---
