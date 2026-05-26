# Macroeconomic-Forecasting-and-Risk-Monitoring-Dashboard-Evidence-from-FRED-MD
# Macroeconomic Forecasting and Risk Monitoring Dashboard

A reproducible Python project for macroeconomic forecasting and risk monitoring using FRED-MD style macroeconomic data. The project converts the original Jupyter notebook into a clean Git-ready structure with reusable source code, scripts, tests, documentation, generated outputs, and an optional Streamlit dashboard.

## Project overview

This project develops a macroeconomic monitoring framework using key monthly indicators from the FRED-MD database. It applies classical time-series and econometric techniques to forecast business-cycle movements and construct a composite macroeconomic risk index.

The project is designed for academic research, reproducible analysis, and applied macroeconomic risk monitoring. It can be used by students, researchers, policy analysts, banking analysts, and anyone interested in macroeconomic forecasting with Python.

## Main features

- FRED-MD style data processing pipeline
- Macroeconomic data transformation functions
- Augmented Dickey-Fuller stationarity testing
- ARIMA forecasting models
- Holt-Winters exponential smoothing models
- Vector Autoregression model
- Principal Component Analysis for dimensionality reduction
- Composite macroeconomic risk index
- Forecast evaluation tables
- Dashboard-style visualizations
- Optional Streamlit web dashboard
- Smoke test for checking the project pipeline

## Research objective

The main objective of this project is to build a reproducible macroeconomic forecasting and risk monitoring dashboard using monthly macroeconomic indicators. The framework focuses on three goals:

1. Transform and prepare macroeconomic time-series data for econometric modelling.
2. Compare forecasting models such as ARIMA, Holt-Winters, and VAR.
3. Construct a composite risk index that summarizes macroeconomic stress into an interpretable monitoring signal.

## Econometric methods used

### 1. Data transformations

The project follows FRED-MD style transformation logic to make macroeconomic series suitable for time-series modelling. Depending on the series, transformations may include first differences, log transformations, log differences, or second log differences.

### 2. Stationarity testing

Augmented Dickey-Fuller tests are used to check whether transformed macroeconomic variables are stationary. This is important before fitting ARIMA and VAR models.

### 3. ARIMA forecasting

ARIMA models are used for univariate time-series forecasting. They capture autoregressive patterns, differencing behavior, and moving-average effects in individual macroeconomic indicators.

### 4. Holt-Winters exponential smoothing

Holt-Winters damped-trend exponential smoothing is used as an alternative forecasting method. It is useful for modelling level and trend dynamics in time-series data.

### 5. Vector Autoregression

VAR models are used to capture relationships between multiple macroeconomic variables. This allows the project to study dynamic interactions between indicators such as industrial production, unemployment, inflation, and interest rates.

### 6. Principal Component Analysis

PCA is used to reduce the dimensionality of the macroeconomic panel. It helps identify common macroeconomic factors that explain variation across several indicators.

### 7. Composite risk index

The project constructs a composite macroeconomic risk index by combining several normalized risk components. This produces a simple risk-monitoring signal that can be interpreted as low, medium, or high macroeconomic risk.

