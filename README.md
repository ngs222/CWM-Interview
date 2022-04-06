# Noah Sutherland CWM Interview
### Purpose
I was recently given a project to complete by Circle Wealth Management during my interview process for a Summer internship position. The project was as follows: 
Using the programming language of your choice (I chose Python), please complete the analysis outlined. 
For the following tickers, SPY, XLV, TLT, BIL, DBC, and MUB, download price information from yahoo finance and calculate the following for the past 5 years:
- Monthly returns for each ticker
- Average monthly and annualized returns for each ticker
- Standard deviation/volatility (monthly and annualized) for each ticker
- Correlations between each ticker
- Worst month and best month for each ticker

Output this information to a human-readable format (excel, text, pdf, etc.). Using this information, write a brief (<1 page) memo on which ticker or tickers (if multiple tickers include % allocations for each) would be the best to use for a) an individual whose objective is maximum growth and isn't worried about volatility, and b) an individual whose objectives are lower volatility and capital preservation. 

### Installations/Packages
- import pandas as pd 
- import numpy as np 
- import seaborn as sns 
- from statsmodels.formula.api import ols as sm_ols
- import yfinance as yf
- from yahoofinancials import YahooFinancials