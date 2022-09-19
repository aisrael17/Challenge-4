# Challenge-4

## Technologies
For this project, I used Python3 and the following external libraries:
* pandas
* Path (from pathlib)
* numpy

## Data
For this project, a data set of fund NAVs for the following funds was provided from Oct. 1, 2014 to Sep. 11, 2020:
* Berkshire Hathaway
* Paulson & Co.
* Soros
* Tiger Global

Additionally, S&P 500 levels were provided over the same period. 

## Project Description

First, I imported the data into a Jupyter Notebook using pandas. Then, I calculated the cumulative returns of each fund and compared it to the returns of the S&P 500. Next, I analyzed the volatility of the returns of each fund. Then, I looked at the risk-return profile of each fund by calculating each fund's Sharpe Ratio and 60-day rolling beta. 