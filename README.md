# Pairs Trading Strategy: AAPL vs KO

## Overview
This project implements a pairs trading strategy using 15 years of monthly data.

## Objective
To test whether the spread between AAPL and KO is mean-reverting and can be exploited to generate trading profits.

## Methodology
- Log-price spread construction
- Autocorrelation analysis (ACF)
- Out-of-sample trading strategy
- Econometric testing (OLS regression)
- Performance evaluation with transaction costs

## Results
The spread is not mean-reverting and shows strong persistence.
The strategy generates no meaningful variation in positions.
As a result, the strategy is not reliable.

## Tools
Python, pandas, numpy, statsmodels, matplotlib
