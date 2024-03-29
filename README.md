# Columbia_Fintech_Module5

# Project Title

This program analyzes and presents a financial plan. The financial planner sources real time data using API and SDK calls. Once the data is sourced, then it simulates
the futuristic returns based on volatility present in the historical data. The program the summarizes the data and presents the data in visual format.

---

## Technologies

This project is written in python. The required libraries are as follows
pathlib ver 2.3.6, sys version 20160418, %matplotlib inline, os, requests, json, pandas, dotenv, alpaca_trade_api, MCForecastTools


---

## Usage

This project sources historical data to calculate historical volatility and simulates future based on historical volatility

## Analysis Report
 
One would expect that heavily weighing portfolio to stocks does bring in higher volatility. 
However, annualizing the standard deviation i.e. 30_year_std / sqrt(30) and 10_year_std / sqrt(10) respectively reveals that stocks_heavy_portfolio has lower standard deviation and lower annual mean.
For stock heavy portfolio, annualized standardardization is 1.07 and annualized mean is 0.55
For bond heavy portfolio, annualized standardardization is 7.44 and annualized mean is 1.7

Based on above observation, I will recommend bond heavy portfolio. 

Now based on 95% confidence observation, the stock heavy portfolio for 10 years will become approx. $900k, whereas bond heavy portfolio invested for 30 years will become approx. $9.8mn. 
The difference is almost 10x. 
Based on mean observations, the stock heavy portfolio for 10 years will become approx. $367k, whereas bond heavy portfolio invested for 30 years will become approx. $3.4mn. 
The difference is almost 9x.
Once again, based on above observations, I will not recommend to retire after 10 years assuming you invest in stock heavy portfolio.

However, if one assumes that $367k is enough to retire on average, then the answer is yes. The union members can retire by investing in stock heavy portfolio for 10 years.

