# Risk-Based Quantitative Modeling & ML Risk Forecasting

This project develops an end-to-end risk modeling framework that integrates
traditional portfolio risk metrics, statistical backtesting, and machine
learning–based downside risk forecasting.

## Objectives
- Measure portfolio risk using volatility, drawdowns, VaR, and CVaR
- Backtest Value-at-Risk using the Kupiec Unconditional Coverage Test
- Forecast high-risk market days using machine learning
- Apply time-series–aware validation to avoid look-ahead bias

## Data
- Daily ETF data (GLD, QQQ, SPY, TLT)
- Source: Stooq (free market data)

## Methodology
1. Portfolio construction (equal-weight)
2. Risk metrics: volatility, drawdown, VaR, CVaR
3. VaR backtesting using Kupiec test
4. Feature engineering for risk prediction
5. ML classification (Logistic Regression)
6. TimeSeries cross-validation

## Tools & Technologies
- Python, Pandas, NumPy
- Matplotlib
- SciPy
- Scikit-learn

## Outputs
- Equity curve and drawdown plots
- Rolling volatility & VaR diagnostics
- ML-based probability forecasts for high-risk days

## How to Run
```bash
pip install -r requirements.txt
