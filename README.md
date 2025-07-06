# Car-Price-Prediction-Model

## Project Overview

This project develops a machine learning model to predict used car prices based on various features such as engine specifications, dimensions, fuel type, and performance metrics. The dataset contains 205 car samples with 26 features. The model uses linear regression and achieves strong predictive performance.

## Dataset

- 205 rows and 26 columns, no missing or duplicate data.
- Features include numeric attributes (e.g., wheelbase, horsepower) and categorical variables (e.g., CarName, fueltype).
- Key attributes: engine size, curb weight, horsepower, car dimensions, fuel economy, and more.

## Data Preprocessing

- Cleaned inconsistent car brand names using a correction dictionary.
- Encoded categorical variables such as door number (two → 2, four → 4).
- Explored feature correlations to select key predictors.

## Model

- Linear Regression was used for price prediction.
- Dataset split into training (80%) and testing (20%) sets.
- Evaluated using:
  - RMSE: 2601.62
  - MAPE: 20.29%
  - R-squared: 0.78

## Results

- Strong positive correlation between price and features like engine size, curb weight, horsepower, and car width.
- Negative correlation with fuel efficiency metrics (city and highway mpg).
- The model explains about 78% of the price variance.


## Technologies

- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib / seaborn (for EDA, optional)



