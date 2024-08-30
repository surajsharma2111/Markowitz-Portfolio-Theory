# Marowitz Portfolio Project

## Overview

This project involves analyzing a portfolio of stocks from the Nifty 50 index and evaluating its performance. The analysis includes calculating key metrics such as CAGR (Compound Annual Growth Rate), volatility, Sharpe ratio, Efficient Frontier, risk-adjusted return, drawdown, and Sortino ratio. The goal is to assess the portfolio's performance compared to a benchmark (Nifty 50 index) and provide insights into its risk-return characteristics.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)

## Introduction

The Marowitz Portfolio Project aims to optimize a portfolio of stocks from the Nifty 50 index using modern portfolio theory and risk management techniques. The project involves the following steps:

- Data preprocessing: Cleaning, handling missing values, and preparing the data for analysis.
- Calculating metrics: Computing CAGR, volatility, Sharpe ratio, and other key performance indicators for each stock.
- Efficient Frontier: Generating a scatter plot of portfolio returns versus volatility and identifying the optimal portfolios.
- Portfolio performance: Comparing the portfolio's total return, volatility, risk-adjusted metrics, drawdown, and Sortino ratio against a benchmark (Nifty 50 index).

## Data

The project uses historical stock price data of the Nifty 50 index constituents. The data is sourced from Yahoo Finance using the `pandas_datareader` library. The stock data includes closing prices over a specified time period.

## Methodology

1. **CAGR Calculation:** Calculate the Compound Annual Growth Rate (CAGR) for each stock over a specified number of years.

2. **Volatility and Sharpe Ratio:** Compute the volatility (standard deviation) and Sharpe ratio for each stock using historical price data. The Sharpe ratio measures the risk-adjusted return of a portfolio.

3. **Efficient Frontier:** Generate random portfolios with varying weights for the selected stocks. Calculate portfolio returns, volatilities, and Sharpe ratios for each portfolio. Plot the Efficient Frontier to identify optimal portfolios.

4. **Portfolio Performance Metrics:** Evaluate the portfolio's performance by calculating total return, volatility, drawdown, Sortino ratio, and other risk-adjusted metrics.

## Results

The project yields the following insights:

- Efficient Frontier: A scatter plot of portfolio returns versus volatility highlights the optimal portfolios along the curve.
- Portfolio Performance: Comparison of the portfolio's total return, volatility, drawdown, and Sortino ratio against the benchmark (Nifty 50 index).

## Conclusion

The Marowitz Portfolio Project provides a comprehensive analysis of a portfolio of Nifty 50 stocks, including risk-return characteristics and performance metrics. The project demonstrates the application of modern portfolio theory and risk management techniques to create and assess a diversified portfolio.
