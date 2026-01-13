Overview
This project implements an end-to-end machine learning trading system that combines
probabilistic directional predictions with ATR-based risk management and multi-candle trade execution.

The objective is not to maximize returns, but to demonstrate a realistic and unbiased
machine learning trading pipeline.

Methodology
1. Feature engineering using technical indicators (RSI, ATR, MACD, Bollinger Bands)
2. Binary classification for next-bar price direction
3. Time-series train-test split to avoid data leakage
4. Probability-based signal filtering
5. Long and short trade execution
6. ATR-based stop-loss and take-profit
7. Fixed fractional position sizing (1% risk per trade)
8. Multi-candle trade holding with maximum holding period
9. Strategy evaluation using equity curve, drawdown, and Sharpe ratio

Results
- Win Rate: ~38%
- Risk–Reward Ratio: 1:1.5
- Strategy Expectancy: Near breakeven
- Drawdown: Controlled through position sizing

The results highlight that machine learning provides a weak directional edge, and
profitability depends largely on execution and risk management.

Key Learnings
- Accuracy alone does not guarantee profitability
- Risk management plays a larger role than prediction
- Multi-bar execution is essential for realistic backtesting
- Machine learning models must be combined with rule-based constraints

 Disclaimer
This project is for educational and research purposes only.
It does not constitute financial advice.
