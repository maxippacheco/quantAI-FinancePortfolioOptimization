# QuantAI-FinancePortfolioOptimization

**QuantAI** is a Python-based project that combines financial modeling, portfolio optimization, and unsupervised learning techniques to derive actionable insights for investment strategies.

## Features

- **Volatility Metrics**: Calculates Garman-Klass volatility to assess stock price fluctuations.
- **Unsupervised Learning**: Applies clustering algorithms to identify patterns and group similar assets.
- **Rolling Factor Betas**: Estimates factor exposures using the Fama-French 5-factor model.
- **Return Analysis**: Models monthly returns over different time horizons for stock performance evaluation.
- **Data Aggregation**: Focuses on the top 150 most liquid stocks for monthly aggregation and analysis.
- **Portfolio Optimization**: Utilizes `PyPortfolioOpt` to optimize portfolio construction and maximize returns.

## Technologies Used

- **Python** (pandas, numpy, matplotlib, statsmodels, scikit-learn)
- **Financial Data**: Yahoo Finance, Fama-French Data
- **Portfolio Optimization**: PyPortfolioOpt

## Usage

1. **Data Collection**: Fetched financial data using `pandas_datareader` or `yfinance`.
2. **Feature Engineering**: Computed technical indicators like volatility, returns, and factor betas.
3. **Unsupervised Learning**: Applied clustering techniques to group similar stocks.
4. **Optimization**: Used `PyPortfolioOpt` to find the optimal asset allocation for a portfolio.
5. **Visualization**: Plot the results to visualize stock performance, returns, and portfolio composition.
