# Tech Market Scores

## Overview
This project performs exploratory data analysis and risk assessment on major technology sector stocks using Python. It analyzes historical market data to study price trends, returns, volatility, correlations, and downside risk, and uses simulation techniques to model future price behavior.

## Objective
- Analyze historical performance of leading technology stocks  
- Evaluate return behavior, volatility, and inter-stock relationships  
- Quantify investment risk using statistical and simulation-based methods  
- Apply time-series analysis concepts to real-world financial data  

## Dataset
- Source: Yahoo Finance (via pandas-datareader)  
- Stocks: AAPL, GOOGL, MSFT, AMZN  
- Time period: 1 year (~250 trading days per stock)  
- Features: Open, High, Low, Close, Adjusted Close, Volume  

## Key Analysis
- Price and volume trend analysis  
- Daily returns and distribution analysis  
- Moving averages (10, 20, 50-day)  
- Correlation analysis of stock returns  
- Risk-return comparison (expected return vs volatility)  
- Value at Risk (VaR) at 95% and 99% confidence levels  
- Monte Carlo simulation (10,000 runs, 365-day horizon)

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- pandas-datareader  
- Jupyter Notebook  

## Key Insights
- Tech stocks show positive correlations, with varying strengths across pairs.  
- Moving averages smooth short-term fluctuations and reveal broader trends.  
- Risk-return trade-offs differ across stocks based on volatility levels.  
- Monte Carlo simulations indicate relative stability for large-cap tech stocks under modeled conditions.

## How to Run
1. Clone the repository  
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn pandas-datareader
3. Open the notebook in Jupyter or VS Code  
4. Run cells sequentially from top to bottom  

## Learning Outcomes
- Hands-on experience with financial time-series data  
- Practical application of EDA, statistical analysis, and simulation  
- Improved understanding of market risk metrics and predictive modeling  

## Future Improvements
- Extend analysis to multi-year data  
- Add technical indicators (RSI, MACD)  
- Apply machine learning models for prediction  
- Explore portfolio optimization techniques  
