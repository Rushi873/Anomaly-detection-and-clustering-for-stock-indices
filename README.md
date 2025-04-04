# Anomaly Detection and Clustering for Stock Indices

## Overview
This project focuses on analyzing the NIFTY50 and IBOVESPA indices by collecting and transforming daily time series data from **January 2000 to June 2024**. The dataset was processed to ensure stationarity for effective analysis, utilizing various mathematical tools for anomaly detection and clustering.

## Project Structure

### 1. **Data Collection and Preprocessing**
- Collected **24.5 years** of historical data for NIFTY50 and IBOVESPA.
- Decomposed time series data into **trend, seasonality, and stationary components**.
- Ensured stationarity using **Augmented Dickey-Fuller (ADF) test**.
- Handled missing data and anomalies through preprocessing techniques.

### 2. **Anomaly Detection**
- Detected anomalies in both stationary and non-stationary stock patterns.
- Applied **statistical and mathematical models** to identify irregular movements in stock indices.
- Used various techniques (available in the respective folders) to detect significant outliers and market shifts.

### 3. **Comparative Analysis of IBOVESPA and NIFTY50**
- Performed an **in-depth analysis** for both indices separately.
- Conducted **comparative studies** using correlation metrics to identify dependencies.
- Evaluated stationary and non-stationary characteristics for both indices.

### 4. **Trading Strategy Development**
- Identified **peaks and troughs** from stationary data.
- Devised a **signal-based trading strategy** using extracted patterns.
- Evaluated performance using:
  - **Sharpe Ratio**
  - **Sortino Ratio**
  - **Profit Factor**
  - **Maximum Drawdown**

### 5. **Predictive Modeling and Statistical Analysis**
- Applied **Cointegration and Granger causality tests** to explore predictive relationships.
- Developed a **multivariate forecasting model** using **Vector Autoregression (VAR)** and **Impulse Response Function (IRF)**.
- Analyzed cross-indicator impacts using statistical tests such as **t-tests** and **cross-correlation**.

## Repository Structure
```
├── Analysis
│   ├── Comparison_stationary.ipynb
│   ├── comparison_non-stationary.ipynb
│   ├── Data_manipulation.ipynb
│   ├── Google_trends.ipynb
│   ├── IBOVESPA.ipynb
│   ├── NIFTY.ipynb
│   ├── Performance_comparison.ipynb
│   ├── missing_data_log.csv
│   ├── nifty_social_media_trends_monthly.csv
│   ├── nifty_social_media_volatility_keywords_full.csv
│
├── Data Collection
├── Deep Learning Model
├── Statistic Model
├── Unsupervised Model
│
├── .gitignore
├── README.md
```

## Internship Contribution
**Universidade Federal de Goiás, Data Science Intern** *(June 2024 - Present)*
- Developed and executed anomaly detection models for stock indices.
- Conducted comparative research between IBOVESPA and NIFTY50.
- Designed a trading strategy utilizing historical peak-trough patterns.
- Applied econometric models to analyze market trends and relationships.

## Acknowledgment
This project was conducted as part of my **Data Science internship at Universidade Federal de Goiás**, under the guidance of **Professor Marcos**.

For further details, refer to the Jupyter notebooks provided in the repository.
