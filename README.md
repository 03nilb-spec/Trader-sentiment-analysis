***Trader Behavior Analysis vs Bitcoin Market Sentiment***:

This project explores the relationship between market sentiment (Fear vs Greed) and trader behavior using real trading data and sentiment scores. It aims to uncover patterns that can help inform smarter trading strategies.

**Datasets Used**:
1. **Fear Greed Index**
   - Columns: `Date`, `Value`, `Classification` (Fear/Greed), `timestamp`
2. **Historical Trader Data**
   - Key Columns: `Account`, `Execution Price`, `Size Tokens`, `Side`, `Direction`, `Closed PnL`, `Crossed`, `Timestamp IST`, etc.
  
**Objectives**:
- Understand how **trader performance (PnL)** varies based on market sentiment.
- Analyze how **trading behavior (Buy/Sell/Long/Short)** shifts on Fear vs Greed days.
- Evaluate whether traders become more **aggressive (Crossed Orders)** depending on sentiment.
- Explore **trade size patterns** across sentiment classifications.

**Key Visual Analysis**:
- **Average PnL on Fear vs Greed days**
- **Side preference (Buy/Sell)** under different sentiment conditions
- **Aggression in trading** (Crossed orders) during Fear vs Greed
- **Trade sizes** comparison on fearful vs greedy market moods
- Optional: Analysis of **Long vs Short** behavior on sentiment days

**Tools and Libraries**
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- Jupyter notebook

**Insights** (Summary)
- Traders tend to earn the highest average profit during Extreme Greed days. In contrast, Neutral days see the lowest average PnL, suggesting indecision in the market. Fear and Greed days show moderate returns, while Extreme Fear days see a sharp dip.
- Trade activity is highest on Fear days for both Buy and Sell sides. Extreme Fear days see the least activity, indicating hesitation or market withdrawal. Other sentiment states like Greed and Neutral show moderate, balanced activity.
- Crossed orders — which indicate aggressive execution — peak on Fear days, showing urgency in execution. Extreme Fear days have the fewest aggressive trades. Extreme Greed, Greed, and Neutral days show moderate aggression levels.
- The largest volume of tokens is traded on Extreme Greed days, suggesting high conviction. Extreme Fear days show the lowest volume. Greed and Neutral days have moderate trade volumes, while Fear days surprisingly show less activity.
- On Fear days, traders predominantly open long positions, anticipating a market rebound. In Extreme Fear and Greed conditions, there's a higher share of short trades, suggesting bearish expectations. Interestingly, Extreme Greed sees fewer long trades — possibly due to profit booking at perceived peaks.

  
