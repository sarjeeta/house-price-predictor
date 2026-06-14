# House Price Predictor using Machine Learning

## Overview

This project predicts house prices using Machine Learning techniques on the California Housing Dataset. The goal is to build and compare multiple regression models to accurately estimate housing prices based on features such as median income, house age, average rooms, population, and geographic location.

## Dataset

The project uses the California Housing Dataset available in Scikit-learn.

### Features

* MedInc – Median Income
* HouseAge – Median House Age
* AveRooms – Average Number of Rooms
* AveBedrms – Average Number of Bedrooms
* Population – Population of the Area
* AveOccup – Average Occupancy
* Latitude – Latitude Coordinate
* Longitude – Longitude Coordinate

### Target Variable

* Price – Median House Value

---

## Project Workflow

1. Data Loading and Exploration
2. Data Quality Check
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Feature and Target Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison

---

## Exploratory Data Analysis

Performed:

* Dataset inspection using Pandas
* Missing value analysis
* Correlation matrix analysis
* Price distribution visualization
* Feature relationship visualization using scatter plots

Key observation:

* Median Income (MedInc) showed the strongest positive correlation with house prices.

---

## Models Implemented

### 1. Linear Regression

A baseline regression model that assumes a linear relationship between features and house prices.

### 2. Decision Tree Regressor

A tree-based model capable of capturing non-linear relationships.

### 3. Random Forest Regressor

An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Model Performance

| Model                   | MAE   | RMSE  | R² Score |
| ----------------------- | ----- | ----- | -------- |
| Linear Regression       | 0.533 | 0.746 | 0.576    |
| Decision Tree Regressor | 0.456 | 0.707 | 0.619    |
| Random Forest Regressor | 0.328 | 0.506 | 0.805    |

### Best Model

Random Forest Regressor achieved the best performance with:

* MAE: 0.328
* RMSE: 0.506
* R² Score: 0.805

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

house-price-predictor/

├── data/

├── notebooks/

├── models/

├── src/

├── README.md

└── requirements.txt

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Machine Learning with Scikit-learn
* Data Visualization

---

## Future Improvements

* Hyperparameter Tuning
* Feature Scaling
* Cross Validation
* XGBoost Regressor
* Model Deployment using Flask/FastAPI
* Interactive Web Application using Streamlit

---

## Author
Sarjeeta