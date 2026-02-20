# Trader Behavior vs Market Sentiment Analysis

## Objective

The goal of this project is to analyze how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance on Hyperliquid, and to derive actionable strategy insights.


## Methodology

- Cleaned and aligned trader data with daily sentiment data.
- Created daily trader-level metrics:
- Daily PnL
- Win rate
- Trade count
- Average position size
- Compared performance across sentiment regimes.
- Analyzed behavioral changes during Fear vs Greed periods.
- Built a simple predictive model to forecast next-day profitability.


## Key Insights

- Profitability is higher during Fear compared to Greed.
- Traders increase trade frequency during Greed, but average returns decline.
- Position sizes are highest during Fear, indicating higher risk-taking during volatile markets.
- Average position size (Size USD) is the strongest predictor of next-day profitability.


## Strategy Recommendations

1. Increase allocation during normal Fear phases, but reduce leverage during Extreme Fear to control risk.
2. Reduce trade frequency during Greed periods to avoid overtrading.
3. Apply sentiment-aware risk management based on trader profile.


## Bonus: Predictive Model

A Random Forest model was trained to predict next-day profitability.

Model Accuracy: ~61%

Most Important Feature: Average Position Size (Size USD)

This suggests behavioral risk-taking plays a key role in short-term profitability.


## Repository Structure

- Trader_Sentiment_Analysis.ipynb – Full analysis and modeling
- requirements.txt – Required libraries
- README.md – Project summary



## How to Run

Install dependencies:

pip install -r requirements.txt

Then open and run:

Trader_Sentiment_Analysis.ipynb
