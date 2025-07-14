# Forecasting Average Wages in Russian Regions (2025–2026)

This project aims to predict the average annual wages across Russian regions for the years 2025 and 2026 using LSTM neural networks trained on historical data from Rosstat (2013–2024).

## Project Overview

Using time series modeling with LSTM networks, this notebook performs:

- Data cleaning and preprocessing from Rosstat Excel files
- Feature encoding and normalization
- Model construction and training (Keras model)
- Evaluation using MAE and MSE
- Forecast generation for 2025–2026
- Visualization of trends and salary distribution by region
- Comparison of model outputs with real-world statistics

## Repository Structure

| File | Description |
|------|-------------|
| [`wages.xlsx`](./wages.xlsx) | Raw historical wage data from Rosstat (2013–2024), used as the base dataset |
| [`wages_predict.ipynb`](./wages_predict.ipynb) | Jupyter notebook with full code for data preparation, modeling, evaluation, and forecasting |
| [`predicted_wages.xlsx`](./predicted_wages.xlsx) | Final table with forecasted wages for all regions in 2025 and 2026, including intervals based on MAE |

## Data Sources

- [Rosstat – Labor and Salaries](https://rosstat.gov.ru/labor_market_employment_salaries)

## Author

Polina Doronicheva,  
3rd year, HSE Faculty of Computer Science  
Project supervisor: Viktor Popov

