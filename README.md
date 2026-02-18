# Market Sentiment vs Trader Behavior: A Regime-Based Analysis of Hyperliquid Performance

## Objective
This project analyzes how Bitcoin Fear/Greed market sentiment influences trader behavior and profitability on Hyperliquid.

## Methodology
- Loaded and cleaned both datasets
- Converted timestamps to daily level
- Merged sentiment with trade data
- Created metrics: PnL, win rate, leverage, trade frequency
- Segmented traders (high vs low leverage, frequent vs infrequent)

## Key Insights
1. Fear regimes show higher trade frequency but lower profitability.
2. High leverage amplifies losses during Fear conditions.
3. Greed regimes show improved win rates and stronger performance.

## Strategy Recommendations
1. Reduce leverage during Fear periods.
2. Avoid overtrading in volatile regimes.
3. Increase systematic participation during Greed sentiment.

## How to Run
Install required packages:
pip install pandas numpy matplotlib seaborn scikit-learn

Run the notebook:
hyperliquid_sentiment_analysis.ipynb
