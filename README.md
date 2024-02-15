# REVOLUTIONIZING-WALMART-SALES-FORECASTING-A-TIME-SERIES-ANALYSIS-APPROACH-

This project aims to forecast weekly sales for Walmart stores using two different time series forecasting techniques: "SARIMAX" and "PROPHET". The dataset used in this project contains historical weekly sales data for 45 Walmart stores.

# Techniques Used:

## SARIMAX Model:

1. Utilized SARIMAX model with (1,0,1) order and (1,0,1,52) seasonal order to forecast weekly sales for each store.
2. Evaluated the model's performance using Mean Absolute Scaled Error (MASE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R^2) score.
3. Visualized the forecasted sales alongside the actual data for each store.

## Prophet Model:

1. Implemented Facebook's Prophet forecasting model, which handles seasonality and holiday effects automatically.
2. Trained separate Prophet models for each store to forecast weekly sales.
3. Evaluated the model's performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R^2) score.
4. Visualized the historical sales data, forecasted sales, and uncertainty intervals for each store.

# Files Included:

1. README.md: Detailed information about the project, including setup instructions and usage guidelines.
2. EDA_PART_1.ipynb: Jupyter Notebook containing detailed exploratory analysis of the data.
3. SARIMAX_PART_2.ipynb: Jupyter Notebook containing SARIMAX model implementation and visualization.
4. Prophet_PART_3.ipynb: Jupyter Notebook containing Prophet model implementation and visualization.
5. Walmart.csv: The dataset containing historical weekly sales data for Walmart stores.
6. Revolutionising_walmart_sale.ipynp: Jupyter Notebook containing full project.
