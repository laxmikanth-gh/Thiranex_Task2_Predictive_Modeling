# Thiranex_Task2_Predictive_Modeling
A Predictive Modeling Using Machine Learning to Build a model to predict outcomes based on given data
# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to build and evaluate predictive models capable of estimating house prices based on various property features.

The project was completed as part of a Predictive Modeling and Machine Learning assignment, covering data preprocessing, model training, evaluation, and performance comparison.

---

## Dataset

The Housing dataset contains information about residential properties, including:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room Availability
* Basement
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

### Target Variable

* **Price** (House Price)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Machine Learning Models

Three supervised learning algorithms were implemented:

### 1. Linear Regression

A statistical model used to predict continuous values.

### 2. Decision Tree Regressor

A tree-based model that learns decision rules from the data.

### 3. Random Forest Regressor

An ensemble learning method that combines multiple decision trees.

---

## Data Preprocessing

The following preprocessing steps were performed:

* Dataset loading and exploration
* Missing value inspection
* Categorical variable encoding using One-Hot Encoding
* Feature selection
* Train-Test Split (80:20)

---

## Model Evaluation

Models were evaluated using:

### Mean Absolute Error (MAE)

Measures the average prediction error.

### R² Score

Measures how well the model explains the variance in house prices.

---

## Results

| Model             |       MAE | R² Score |
| ----------------- | --------: | -------: |
| Linear Regression |   970,043 |    0.653 |
| Random Forest     | 1,021,546 |    0.612 |
| Decision Tree     | 1,195,266 |    0.477 |

### Best Performing Model

**Linear Regression** achieved the highest R² Score and lowest MAE, making it the best-performing model for this dataset.

---

## Visualizations

The project includes:

* Model Performance Comparison Chart
* Actual vs Predicted House Prices Plot
* Feature Importance Analysis

---

## Project Structure

```text
House-Price-Prediction
│
├── Dataset
│   └── Housing.csv
│
├── Notebooks
│   └── House_Price_Prediction.ipynb
│
├── Reports
│   └── House Predictiion conclusuion.pdf
│
├── Screenshots
│
└── README.md
```

---

## Learning Outcomes

Through this project, the following concepts were applied:

* Data Preprocessing
* Feature Engineering
* Supervised Learning
* Regression Algorithms
* Model Evaluation
* Performance Visualization

---

## Author

**Danam Laxmikanth**

Machine Learning & Data Science Enthusiast
