# Freqtrade Technical Analysis Trading Strategies

In this repository, five trading strategies sourced from the open source trading environment Freqtrade are to be found.
The five strategies are: 
- BBandsRSI
- DoubleEMACrossoverWithTrend
- EMAPriceCrossoverWithThreshold
- MACDCrossoverWithTrend
- SuperTrend

# Data
The data files used for backtesting the strategies are also included in this respository, containing historical price data on the BTC/USDT pair sourced from the Binance API. They include data of the following timeframes:
- 30 minutes
- 1 hour
- 4 hours
- 1 day

# Configuration
The config.json file includes all general configurations made in hte Freqtrade trading environment.
Further information on how to install the Freqtrade environment can be found on their website: 
https://www.freqtrade.io/en/stable/

# Results
The best backtesting results were achieved using the EMAPriceCrossoverWithThreshold on a one hour trimeframe, achieving a 17% profit. The strategy plot can be found under freqtrade-plot-BTC_USDT-1h.html

For questions, reach out to: thabsburg.ieu2019@student.ie.edu
