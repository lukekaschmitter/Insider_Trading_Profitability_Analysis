# Insider_Trading_Profitability_Analysis
An analysis of 52,771 SEC-reported insider transactions from January–November 2023, examining whether publicly available data can reliably predict the profitability of legal insider trades.

Data Sources
OpenInsider.com (SEC EDGAR transaction data)
AAII weekly consumer sentiment surveys
Yahoo Finance via yfinance API

Methods
OLS multiple linear regression with recursive feature elimination (RFE) across numerical, sector, and state variables.

Key Findings
Maximum R² of 0.023 — no independent variable reliably predicted trade profitability
Insider sales clustered heavily at the start of 2023, predominantly in technology
Consumer cyclical posted the highest median percentage profit; real estate posted the highest median dollar profit
Financial services led purchase volume; technology led sale volume

Full paper available in repo.
