# Bike Sharing Demand Prediction

## General Information
This project aims to predict bike-sharing demand using multiple linear regression. The dataset consists of daily bike rental counts, along with various influencing factors such as weather conditions, seasonality, and working days. 

## Dataset
The dataset `day.csv` contains information about daily bike rentals, including:
- **Season, Weather, Temperature, Humidity, Wind Speed**
- **Casual and Registered Users**
- **Total Bike Rentals (Target Variable: `cnt`)**

## Objective
- Identify key factors influencing bike rental demand.
- Build a multiple linear regression model to predict bike demand.
- Evaluate the model's performance using R-squared and residual analysis.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib & Seaborn

## How to Run the Notebook
1. Install required libraries: `pip install pandas numpy scikit-learn statsmodels matplotlib seaborn`
2. Open `bike_sharing_regression.ipynb` in Jupyter Notebook.
3. Run all cells to train the model and evaluate results.

## Results
- R-squared value: Measures model accuracy.
- Feature importance: Identifies key predictors of bike demand.
- Residual analysis: Evaluates model assumptions.


