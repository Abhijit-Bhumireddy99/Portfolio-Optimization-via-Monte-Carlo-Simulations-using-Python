# Portfolio-Optimization-via-Monte-Carlo-Simulations-using-Python

# Project Overview:

This project builds a data analysis pipeline in Python to find the best way to allocate capital in a multi-stock portfolio by maximizing risk-adjusted returns (generating maximum return for a given level of risk). It starts with collecting and cleaning 5 years of historical stock data, ensuring accuracy because bad data leads to bad decisions. Performed individual stock analysis using daily returns, market sentiment labels, and technical indicators like simple moving averages, Bollinger Bands, and trading volume. To build a well-balanced portfolio (risk-adjusted return portfolio) the project focuses on diversification by distributing the capital across the multiple stocks with low correlation as possible in a portfolio, and normalizing (scaling) prices for fair comparison.

Note:
+ve correlation simply means — if one asset increases (↑), then other asset will also increase (↑) or if one asset decreases (↓), then other asset will also decrease(↓). Basically, 2 assets (here, stocks) move in the same direction.
-ve correlation simply means — if one asset increases (↑), then other asset will decrease (↓) or if one asset decreases (↓), then other asset will increase (↑).                Basically, 2 assets (here, stocks) move in the opposite direction.
Zero Correlation simply means — there is no linear relation between the 2 assets (here, stocks). Change in one asset does not impact (influence) the other asset.

The core step in this project is using Monte Carlo simulations to generate multiple random portfolio weight combinations instead of relying on guesswork. Each combination is evaluated using the Sharpe Ratio, which measures return earned per unit of risk. By plotting these results, the Efficient Frontier is formed, helping identify the optimal portfolio for a given level of risk.

Finally, the project determines the Golden Weights, which helps to recommend specific capital allocation in each stock in a portfolio that achieved an expected risk-adjusted annual return of around 28%, reinforcing that smart investing focuses on generating maximum returns for a given level of risk, not just aiming for high returns by ignoring risk.
