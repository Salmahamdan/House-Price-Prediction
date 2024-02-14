# House-Price-Prediction
## Introduction
This project aims to predict house prices based on various features using machine learning algorithms. The dataset used in this project is sourced from Kaggle.

## Requirements
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Dataset
The dataset consists of 21 columns and 21,613 rows. Here is a brief overview of the columns:
- id: ID of the house
- date: Date of sale
- price: Price of the house
- bedrooms: Number of bedrooms
- bathrooms: Number of bathrooms
- sqft_living: Square footage of the living area
- sqft_lot: Square footage of the lot
- floors: Number of floors
- waterfront: Whether the house has a waterfront view (1 for yes, 0 for no)
- view: Number of views
- condition: Condition of the house
- grade: Grade of the house
- sqft_above: Square footage above ground
- sqft_basement: Square footage of the basement
- yr_built: Year built
- yr_renovated: Year renovated
- zipcode: Zip code
- lat: Latitude
- long: Longitude
- sqft_living15: Square footage of the living area in 2015
- sqft_lot15: Square footage of the lot in 2015

## Data Preprocessing
- Checked for missing values (no missing values found)
- Descriptive statistics and data visualization
- Dropping unnecessary columns ('id', 'date', 'zipcode')

## Exploratory Data Analysis
- Distribution of house prices
- Distribution of living space (sqft_living)
- Relationship between bedrooms and price
- Distribution of bathrooms
- Scatter plot of price vs living space
- Impact of waterfront views on prices
- Correlation matrix to find relationships between features

## Model Building and Evaluation
Three regression models were built and evaluated:
1. Linear Regression
   - R-squared Score (Train): 0.6966
   - R-squared Score (Test): 0.6921
2. Random Forest
   - R-squared Score (Train): 0.9812
   - R-squared Score (Test): 0.8813
3. XGBoost
   - R-squared Score (Train): 0.9769
   - R-squared Score (Test): 0.8814

## Conclusion
Based on the evaluation metrics, the Random Forest and XGBoost models performed better in predicting house prices compared to the Linear Regression model.

