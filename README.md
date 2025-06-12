# Predicting Photovoltaic Power from Solar Irradiance using Supervised Machine Learning Models

This repository contains my full research project as part of the **RISE Scholars Program** at **George Mason University's College of Science**. The study investigates, models, and forecasts photovoltaic (PV) solar power generation using real-world 5-minute and 30-minute interval data from a solar energy system.
  
**Affiliation:** George Mason University - Department of Computational and Data Sciences

---

## Objective

With climate change accelerating the global shift toward renewable energy, accurate prediction and forecasting of solar power output is crucial for optimizing grid stability and energy efficiency.

This project focuses on:
- Cleaning and transforming real-world solar energy production data
- Performing detailed exploratory data analysis (EDA)
- Building predictive regression models for near-term solar output
- Designing and evaluating time series forecasting models (ARIMA, Prophet)

---

## Repository Structure

| File | Description |
|-------------|-------------|
| `RAW_PV_POWER.csv` | Raw PV solar power data collected at various time intervals |
| `FINAL_PV_POWER_5_MINS.csv` | Cleaned and processed 5-minute interval dataset |
| `FINAL_PV_POWER_30_MINS.csv` | Cleaned and processed 30-minute interval dataset |
| `Dataset_Cleaning.ipynb` | Jupyter Notebook for data loading, cleaning, and preprocessing |
| `EDA_Visualization.ipynb` | In-depth exploratory analysis with visualizations |
| `Predicitive_Regression_Models.ipynb` | Linear, polynomial, and regularized regression modeling for prediction |
| `Time_Series_Forecasting.ipynb` | ARIMA and Prophet models for forecasting solar energy output |
| `RISE_Research_Poster.pdf` | Final academic poster summarizing methodology, results, and future work |

---

## Methods Used

- **Data Cleaning & Transformation:** `pandas`, `datetime`, NA handling, feature engineering
- **EDA & Visualization:** `matplotlib`, `seaborn`, trend identification, seasonality exploration
- **Regression Modeling:** Linear, Ridge, Lasso Regression using `scikit-learn`
- **Time Series Forecasting:** `ARIMA` (with AIC/BIC optimization) and `Prophet` modeling
- **Evaluation Metrics:** MAE, RMSE, R², Residual Analysis, Confidence Intervals

---

## Key Findings

- Strong daily and seasonal patterns in PV power generation identified via EDA
- Ridge Regression outperformed basic linear models in predicting output from environmental conditions
- Prophet and ARIMA models showed promising forecasting accuracy with multistep ahead predictions
- Forecasting performance varied significantly across different time granularities (5-min vs 30-min)

---
