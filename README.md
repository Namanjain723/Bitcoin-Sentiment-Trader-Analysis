# Bitcoin Market Sentiment vs Trader Performance
### A Data Analyst Project
This project analyzes how Bitcoin market sentiment impacts trader profitability by merging Fear and Greed Index data with historical trading records. It reveals how fear and greed influence risk behavior and trading performance using real market data.
Bitcoin Market Sentiment vs Trader Performance

A Data Analyst Project

## Project Overview

This project analyzes how Bitcoin market sentiment influences trader profitability by combining the Bitcoin Fear & Greed Index with historical trading data from Hyperliquid. The goal is to identify whether emotional market conditions such as Fear, Neutral, and Greed impact trading outcomes and risk behavior.

By merging sentiment data with real trading performance, this project provides actionable insights into how market psychology affects financial decisions in Web3 and crypto trading environments.

## Datasets Used
1. Bitcoin Fear & Greed Index

This dataset measures overall market sentiment based on:

Volatility

Market momentum

Social media sentiment

Market dominance

Each day is classified into categories such as Fear, Neutral, or Greed.

2. Hyperliquid Trader Data

This dataset contains:

Trade timestamps

Executed trades

Closed profit and loss (PnL)

Trading activity metrics

It reflects real trader behavior in live crypto markets.

## Project Workflow

Data Cleaning
Both datasets were cleaned and formatted to ensure consistent date and numerical values.

Data Integration
The Fear & Greed Index was merged with trader data based on matching dates.

Exploratory Data Analysis (EDA)
Trader profitability and activity were analyzed across different sentiment regimes.

Visualization
Charts were created to compare average and total PnL across Fear, Neutral, and Greed periods.

## Key Insights

Trader performance varies significantly across different market sentiments.

Fear periods show different risk and return behavior compared to Greed periods.

Market sentiment can be a useful signal for improving trading and risk management strategies.

## Repository Structure
bitcoin-sentiment-trader-analysis/
├── data/
│   ├── merged_data.csv
│   └── sentiment_performance_summary.csv
├── notebooks/
│   └── sentiment_trader_analysis.ipynb
├── src/
│   └── (data processing and analysis scripts)
├── results/
│   └── sentiment_vs_pnl.png
├── README.md
└── requirements.txt

## Technologies Used

Python

Pandas

Matplotlib

Jupyter Notebook

## How to Run

Clone the repository

Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook notebooks/sentiment_trader_analysis.ipynb

