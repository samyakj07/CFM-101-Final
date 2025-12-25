# 📈 CFM 101 Robo-Advising Challenge — Market Meet Strategy (Portfolio Optimization)

**Team Number:** 09  
**Team Members:** Aryan Singh, Jack Smith, Samyak Jain  
**Strategy Chosen:** **Market Meet**

## 🧠 Overview

In this project, it builds a portfolio fufilling the market-meet strategy by:
- filtering a list of tickers based on specific requirements
- enforcing liquidity + market-cap constraints per assignment instructions
- removing high-volatility stocks
- selecting stocks that correlate with the benchmark to the highest degree
- converting final weights into shares while accounting for FX + fees in order to build a strong portfolio

The benchmark is created as an **equally-weighted average** of daily returns from:
- **S&P 500 (`^GSPC`)**
- **TSX Composite (`^GSPTSE`)**

## Key Outputs
- Filtered ticker DataFrame
- Benchmark sector targets (TSX + S&P sector weights)
- Volatility filtering (by sector)
- Stock selection by benchmark correlation
- Final portfolio weights (sector caps + stock caps)
- Final CSV output: Stocks_Group_09.csv

## Libraries Used
- IPython.display  
- pandas  
- numpy  
- numpy-financial  
- yfinance  
- matplotlib  
- random  
- datetime
