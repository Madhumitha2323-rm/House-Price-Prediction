# 🏠 House Price Prediction

## About the Project

This project uses Machine Learning to predict house prices based on different property-related features.

A Linear Regression model is used to predict the price of a house using features such as area, bedrooms, bathrooms, age, and location score.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains the following attributes:

- Area
- Bedrooms
- Bathrooms
- Age
- Location Score
- Price

Dataset file: `house_price.csv`

## Machine Learning Algorithm

### Linear Regression

Linear Regression is used to predict house prices based on the selected input features.

**Input Features:**
- Area
- Bedrooms
- Bathrooms
- Age
- Location Score

**Target:**
- Price

## Project Workflow

1. Load the dataset
2. Explore and understand the data
3. Check for missing values
4. Select features and target
5. Split the dataset into training and testing sets
6. Train the Linear Regression model
7. Predict house prices
8. Evaluate the model
9. Visualize actual vs predicted prices

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The experiment produced an R² score of approximately **0.9385** and a Mean Absolute Error of approximately **178,285** on the test data.

## Visualization

An Actual vs Predicted House Price graph is included to visualize the model's predictions.

## Objective

The main objective of this project is to understand and implement Linear Regression for house price prediction.

## Project Files

- `houseprice.ipynb`
- `house_price.csv`

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
