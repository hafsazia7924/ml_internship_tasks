# California Housing Price Prediction

Predicting median house values using OLS, Ridge (L2) and Lasso (L1) regression.

## What I did
- Filled missing values in total_bedrooms using the median
- Made new features (rooms_per_household, bedrooms_per_room, population_per_household, income_x_rooms)
- Checked multicollinearity with a correlation heatmap
- Standardized features and encoded ocean_proximity
- Tuned Ridge and Lasso alpha with GridSearchCV (5-fold)
- Compared models using RMSE, MAE and R2
- Plotted predicted vs actual and residual distribution

## Results
(Yahan apni results table ke numbers likho)

## Limitation
median_house_value is capped at 500,001, so predictions for expensive houses are less accurate.

## How to run
Open regression.ipynb in Google Colab or Jupyter and run all cells.
