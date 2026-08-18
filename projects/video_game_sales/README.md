# Predicting Global Video Game Sales

This project uses historical video game sales data to test whether global sales can be reasonably estimated from non-sales game attributes such as platform, genre, publisher, and release year. Regional sales fields are intentionally excluded because they directly reconstruct global sales and would create data leakage.

Several regression approaches are compared using RMSE, MAE, R-squared, cross-validation, and sensitivity analysis. The final interpretation treats the model as a historical pattern-recognition tool rather than a precise forecasting system for individual releases.

## Main Notebook

- `Video_Game_Sales_Prediction.ipynb`
