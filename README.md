# Trader-Behavior-Market-Sentiment-Analysis


## Overview
This project analyzes the relationship between trader performance and Bitcoin market sentiment using historical trading data and the Fear & Greed Index.

## Datasets
- Historical Trader Data (Hyperliquid)
- Bitcoin Fear & Greed Index

## Methodology
- Cleaned and standardized trade and sentiment datasets
- Aligned timestamps using UTC normalization
- Merged daily sentiment with trade-level data
- Analyzed PnL distribution, win rates, and trading activity across sentiment regimes

## Key Findings
- Fear and Neutral sentiment phases exhibit better average trader performance
- Extreme Greed leads to increased trading activity but poorer risk-adjusted returns
- Sentiment-driven overconfidence negatively impacts profitability

## How to Run
1. Clone the repository
2. Install dependencies:
pip install -r requirements.txt

markdown
Copy code
3. Open the notebook:
notebooks/trader_sentiment_analysis.ipynb

markdown
Copy code

## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
📦 requirements.txt
nginx
Copy code
pandas
numpy
matplotlib
seaborn
