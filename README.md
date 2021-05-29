# Challenge7
etf_analyzer
An analysis of a hypothetical FinTech ETF consisting of $GDOT (Green Dot Corporation), $GS (Goldman Sachs), $PYPL (Paypal), and $SQ (Square).

Usage
This project begins with an analysis of PYPL using a SQL query and a Pandas dataframe, then concludes by graphing the price history with hvplot. The analysis can be completed for any of the stocks included in the portfolio by changing the ticker listed in the code. Next, the code consists of an analysis of all the stocks combined into an ETF. To accomplish this, the stocks are grouped together using another SQL query, then converted into a dataframe. Once the data is in a dataframe, the code calculates average daily returns, average annual returns, and cumulative return, then graphs the cumulative return.

Technologies
The code is written in Python/SQL using jupyter notebook and uses SQLite, Pandas, Numpy, Hvplot, and SQLAlchemy.