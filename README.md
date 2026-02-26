# Financial Econometrics: Marriott International Stock Analysis

## Overview
This repository contains an academic project focused on the statistical and econometric analysis of **Marriott International, Inc. (MAR)** stock market data. The dataset spans over 26 years (from January 1999 to December 2024) and is extracted directly using the Yahoo Finance API.

The primary goal of this project is to investigate the behavior of asset returns across different time frequencies (daily, monthly, and annual) and to test for the standard empirical "stylized facts" of financial time series.

## Key Features
* **Data Extraction & Preprocessing:** Automated retrieval of historical stock prices using `yfinance` and computation of logarithmic returns.
* **Descriptive Statistics:** In-depth analysis of distribution properties including mean, volatility, skewness, excess kurtosis, and quantiles.
* **Statistical Testing:** Implementation of the Jarque-Bera and Lilliefors tests for normality assessment.
* **Time Series Analysis:** Investigation of financial stylized facts, such as return stationarity, autocorrelation, and volatility modeling.
* **LaTeX Integration:** Automated generation of LaTeX tables (`summary.tex`, `statistics.tex`) for seamless integration into academic research reports.

## Technologies & Libraries
* **Language:** Python 
* **Data Manipulation:** `pandas`, `numpy`
* **Financial Data:** `yfinance`
* **Econometrics & Statistics:** `scipy`, `statsmodels`, `arch`, `hurst`
* **Data Visualization:** `matplotlib`, `seaborn`

## Repository Structure
* `DECOURCHELLE_GWENDAL_A_assignmentFINEC.ipynb` : The main Jupyter Notebook containing all the code, calculations, and data visualizations.
* `report/` : Directory containing the LaTeX source files and the final generated PDF report.

## Authors
* **Gwendal Decourchelle**
* **Clément Seimpere**
* **Dan Perrier**
