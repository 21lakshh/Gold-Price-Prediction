# Gold Price Prediction using Machine Learning

## Overview

This project aims to build a machine learning model to predict gold prices based on historical data and various economic indicators. Accurate gold price predictions can assist investors, financial analysts, and policymakers in understanding market trends and making informed decisions.

## Dataset

The dataset consists of multiple economic indicators that influence gold prices, including:

- **Date** – Timestamp of the recorded data
- **SPX** – S&P 500 Index
- **GLD** – Gold ETF Prices
- **USO** – Crude Oil Prices
- **SLV** – Silver ETF Prices
- **EUR/USD** – Exchange Rate of Euro to US Dollar

## Approach

### 1. Exploratory Data Analysis (EDA)
- Visualized correlations between features using a heatmap.
- Analyzed the distribution of gold prices over time.

### 2. Data Preprocessing
- Checked for and confirmed no missing values in the dataset.
- No categorical features required encoding.

### 3. Model Selection
- Implemented **Random Forest Regressor** for prediction.
- Hyperparameter tuning for optimal performance.

### 4. Model Evaluation
- Evaluated model accuracy using:
  - **Mean Absolute Error (MAE)**
  - **R² Score**
    
## Results & Insights

- The **Random Forest Regressor** provided a reliable prediction of gold prices.
- The **feature correlation analysis** highlighted the strongest indicators influencing gold prices.
- Investors and analysts can leverage this model to anticipate price fluctuations.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the **MIT License**.
