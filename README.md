# Trader-Performance-vs.-Market-Sentiment-Analysis
This repository contains a comprehensive analysis exploring the correlation between Bitcoin Market Sentiment (Fear/Greed Index) and the Performance of Traders on the Hyperliquid decentralized exchange.

The goal of this project is to identify behavioral patterns and develop data-driven trading strategies that adapt to varying market emotional states.

# Key Findings:
Contrarian Edge: Win rates are significantly higher during periods of Extreme Fear (~58%) compared to Extreme Greed (~42%).

Risk Behavior: Average leverage usage increases by 2.5x during bullish sentiment, leading to higher liquidation rates.

Volume vs. Profitability: Trade frequency peaks during "Greed" phases, suggesting that retail FOMO drives volume but not necessarily PnL.

# Tech Stack & Methodology:
Language: Python 3.x

Libraries: pandas (Data manipulation), matplotlib/seaborn (Visualization), numpy (Mathematical modeling).

Process:

Data Cleaning: Synchronizing millisecond timestamps with daily sentiment data.

Feature Engineering: Creating metrics for Win Rate, Sharpe Ratio, and Drawdown.

Segmentation: Clustering traders into 'Rational Contrarians' vs. 'Momentum Chasers'.

# Proposed Strategies
The Greed Cap: Automated leverage restriction (Max 10x) when Sentiment > 75.

Fear-Weighting: 20% increase in position sizing when Sentiment < 25.

# Conclusion:
This assignment demonstrates how sentiment-aware risk management can mitigate drawdowns during market euphoria and capitalize on high-probability opportunities during market panics.
