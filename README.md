# Bitcoin Trader Performance vs Market Sentiment Analysis
### A Data Analyst Project
This project analyzes how Bitcoin market sentiment impacts trader profitability by merging Fear and Greed Index data with historical trading records. It reveals how fear and greed influence risk behavior and trading performance using real market data.
Bitcoin Market Sentiment vs Trader Performance

## Quick summary
Language: Python 3.8+
Main libs: Streamlit, Pandas, NumPy, Plotly, SciPy
Data files (required at runtime): fear_greed_index.csv, historical_data.csv

## Features
Multi-page Streamlit dashboard with:
Assignment details and instructions
Summary dashboard (metrics, distributions, timeseries)
Advanced analytics (statistical tests and correlations)
Risk analysis (Sharpe, volatility, drawdown)
Deep-dive trade-level views and filters
Interactive Plotly visualizations
Data export for filtered results

## Quick start (Windows / PowerShell)
Open PowerShell and change to the project directory:
cd "c:/Users/amara/Downloads/CRYPTO-MARKET-ANALYSIS-main/CRYPTO-MARKET-ANALYSIS-main"
(Optional but recommended) create and activate a virtual environment:
python -m venv .venv
.\.venv\Scripts\Activate.ps1
Install dependencies:
python -m pip install --upgrade pip
python -m pip install -r requirements.txt

## Data files
Place the following CSV files in the same directory as the Streamlit app (they are included in this repo):

fear_greed_index.csv — daily Fear & Greed index values (timestamp, value, classification, date)
historical_data.csv — trade-level data (Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp IST, Closed PnL, Fee, ...)

## Running tests / quick checks
There is a helper test_app.py that performs basic checks (syntax, presence of pages and components). Run it with:
python test_app.py

## Troubleshooting
ModuleNotFoundError for libraries (e.g. plotly, scipy):

Ensure you installed requirements with python -m pip install -r requirements.txt.
You can install a missing package directly: python -m pip install scipy
CSV not found error:

Confirm fear_greed_index.csv and historical_data.csv exist in the working directory.
The app reads them with pd.read_csv('fear_greed_index.csv') and pd.read_csv('historical_data.csv').

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

### bitcoin-sentiment-trader-analysis/

├── data/

│ ├── merged_data.csv
│ └── sentiment_performance_summary.csv

│
├── notebooks/
│ └── sentiment_trader_analysis.ipynb

│
├── src/
│ └── data processing and analysis scripts

│
├── results/
│ └── sentiment_vs_pnl.png

│
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


## Open the notebook

trader_sentiment_analysis.ipynb

## Contact / Author
Naman Jain 

Email: namancric18@gmail.com@gmail.com

GitHub: https://github.com/Namanjain723

