Copy code and lauch in python .
make sure you have all the libraries
Stock chart generator
alt text

A tool for generating stock charts from Yahoo! Finance's API.

Installation
Just copy the scg.py script located in the dist folder.

Getting started
You should set three parameters: yahoo symbol, period and interval.

python scg.py MSFT 1y 1d

Valid periods: 1d, 5d, 1mo, 3mo, 6mo, 1y, 2y, 5y, 10y, ytd, max

Valid intervals: [1m, 2m, 5m, 15m, 30m, 60m, 90m, 1h, 4h, 1d, 5d, 1wk, 1mo, 3mo]

python scg.py AAPL 6mo 4h

alt text

Intraday data cannot extend last 60 days.

The yahoo symbol must exists on Yahoo! Finance.

This is wrong:

python scg.py MICROSOFT 9mo 9d

Prerequisites
Python (>= 3.8.5)
yfinance (>= 0.1.70)
License
This project is licenced under the MIT License.
