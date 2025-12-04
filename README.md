# Market-Research
Methods for analyzing market data to detect anomalies and correlations. Analysis of market volatility and liquidity.

-----------------------------------------------------

File "Volatility analysis.IPYNB"

Using historical data, calculate the daily volatility for each day in April.
Plot the volatility chart, identify anomalies, and explain them.

* **Trading pair:** BTC/USDT
* **Exchange:** Binance
* **Observation window:** 01.04.2025 – 30.04.2025
* **Data:** close_price of 15-second candles

The data was downloaded from Binance in 1s candles format. To do the analisys files were merged to 15s candles shape and then the volatility was calculated and plotted.

-----------------------------------------------------

File "Correlation with BTC"

Using historical data, select the top 10 coins most strongly correlated with BTC.
Correlation is calculated using the close_price of 15-second candles.

* **Trading pair (reference asset):** BTC/USDT
* **Exchange:** Binance
* **Observation window:** 01.04.2025 – 10.04.2025
* **Data:** close_price of 15-second candles

The data was downloaded from Binance using public API in 1s candles format. To do the analisys files were merged to 15s candles shape and then correlation was calculated and visualised using the heatmap.

-----------------------------------------------------



