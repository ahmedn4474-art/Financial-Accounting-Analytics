# Financial Accounting Analytics: Forensic Ledger Screening & Cash Liquidity Forecasting

**Author:** Ahmed Noureldin  
**Domain:** Financial Accounting, Corporate Valuation & Treasury Liquidity Management  
**Dataset:** General Ledger & Corporate Financial Statements (100,000 Transactions | Multi-Year Time Series)

---

## 1. Executive Summary & Problem Context

Financial controllers and treasury managers require robust quantitative tools to ensure ledger integrity before monthly close while forecasting liquidity needs across rolling operational cycles.

This project delivers:
1. **Unsupervised ledger screening** for non-standard, after-hours, and high-variance entries.
2. **Time-series cash flow forecasting** to support treasury liquidity planning.

---

## 2. Statistical Stationarity & Liquidity Time Series Modeling

- **Augmented Dickey-Fuller (ADF) Test:** Confirmed unit root stationarity on differenced weekly cash outflow volumes ($ADF = -4.82, p < 0.0001$).
- **Holt-Winters Exponential Smoothing (Triple):** Modeled additive trend and weekly seasonality, generating 8-week forward cash buffer projections with 95% confidence intervals.

---

## 3. Unsupervised Ledger Anomaly Detection

- **Isolation Forest Architecture:** Evaluated 10 multi-dimensional ledger attributes (Amount, Account Class, Processing Lag, User Permission Level).
- **Controller Review Threshold:** Isolated **3% highest-divergence transactions** for pre-close audit, uncovering timing irregularities and out-of-policy journal adjustments.

---

## Repository Structure

```
├── Financial_Fraud_Notebook.ipynb   # Complete analysis & forecasting notebook
├── Financial_Fraud_Notebook.py      # Standalone Python script
├── README.md                        # Documentation
└── README_AR.md                     # Detailed Arabic overview
```
