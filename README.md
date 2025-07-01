# Spain EPU Time Series Forecasting

This project implements time series forecasting for Spain’s Economic Policy Uncertainty (EPU) index. All analysis and modeling steps are contained in the Jupyter Notebook:  
[main.ipynb](https://github.com/tphathuin1802/spain-epu-time-series-forecasting/blob/main/main.ipynb) :contentReference[oaicite:0]{index=0}

## Table of Contents

- [Introduction](#introduction)  
- [Dataset](#dataset)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  

## Introduction

Economic Policy Uncertainty (EPU) indices quantify uncertainty in economic policy and have been shown to relate to market volatility and investment decisions. In this project, we:

1. Load and preprocess the Spain EPU time series.  
2. Perform exploratory analysis (trend, seasonality, stationarity tests).  
3. Fit and compare forecasting models (e.g., ARIMA, SARIMAX).  
4. Evaluate model performance using metrics like MAPE and RMSE.  
5. Generate out-of-sample forecasts for future periods.  

## Dataset

- **Source:** The Spain EPU index (monthly) is loaded directly within the notebook, either via an API or a CSV file.  
- **Coverage:** Typically spans from the earliest available date (e.g., 1997-01) through the latest published month.  

## Requirements

- Python 3.8+  
- Jupyter Notebook  
- Key libraries:
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `statsmodels`  
  - `scikit-learn`  
  - `pmdarima`  

*(You can install them via `pip install -r requirements.txt`.)*

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/tphathuin1802/spain-epu-time-series-forecasting.git
   cd spain-epu-time-series-forecasting
