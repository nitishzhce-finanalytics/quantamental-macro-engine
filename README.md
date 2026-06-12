# quantamental-macro-engine
A quantitative macro research project analyzing the relationship between Indian macroeconomic conditions and sectoral equity returns using econometric and machine learning techniques.

## Objective

This project aims to:

* Identify macroeconomic drivers of Indian equity sector performance
* Detect market regimes using unsupervised learning techniques
* Forecast sector returns under different macro environments
* Derive portfolio allocation implications across economic cycles

---

## Research Questions

* How do inflation, interest rates, liquidity, FX movements, and yield spreads affect sector returns?
* Can macro variables explain regime shifts in Indian equity markets?
* Which sectors outperform during different monetary and economic environments?
* Do machine learning clustering techniques identify economically meaningful market states?

---

## Methodology

### Econometric Models

* OLS Regression
* ARIMA
* GARCH Volatility Modeling
* Stationarity & Cointegration Testing

### Machine Learning Techniques

* PCA (Dimensionality Reduction)
* K-Means Clustering (Regime Detection)
* Random Forest-Based Return Forecasting

### Statistical Diagnostics

* Multicollinearity Analysis
* Heteroskedasticity Testing
* Residual Diagnostics
* Feature Importance Analysis

---

## Data Sources

### Macroeconomic Data

* RBI DBIE
* MOSPI
* FRED
* OECD
* IMF

### Market Data

* NSE Sectoral Indices
* Yahoo Finance

---

## Repository Structure

```text
macro-regime-forecaster/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│   ├── data_collection/
│   ├── preprocessing/
│   ├── econometric_models/
│   ├── ml_models/
│   └── visualization/
│
├── reports/
├── requirements.txt
└── README.md
```

---

## Key Concepts Covered

* Business Cycles
* Monetary Transmission
* Market Regimes
* Volatility Clustering
* Factor Sensitivity
* Time Series Forecasting

---

## Planned Extensions

* Hidden Markov Models (HMM)
* Dynamic Factor Models
* Regime-Switching Portfolio Allocation
* XGBoost-based Forecasting
* Interactive Dashboard Deployment

---

## Preliminary Findings

- Banking and IT sectors showed higher sensitivity to interest-rate regimes
- Volatility clustering intensified during tightening cycles
- PCA-based regime separation aligned broadly with RBI monetary cycles

---

## Disclaimer

This project is built for educational and research purposes and should not be interpreted as investment advice.
