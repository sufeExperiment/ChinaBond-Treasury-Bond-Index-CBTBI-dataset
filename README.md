# ChinaBond-Treasury-Bond-Index-CBTBI-dataset

The CBTBI dataset is a collection of Interest Bond Indices of China, which consists of indices with different durations.

When the environment of the macroeconomy changes, the trading prices of the indices may vary with different volatility patterns over time, which provides us a good testbed for the RL algorithms.

To form the datasets for RL tasks, we choose the data of one-year, three-year, five-year, seven-year, and ten-year duration from CBTBI, ranging from January 4, 2007 to August 12, 2020, in total 3,404 days.

The close price of a bond index includes its price value and the coupon value. 

The yield of a bond consists of its own price change and the return rate of coupon. 

Affected by the yield curve and credit spread, the volatility curve of the bond index varies with its duration.
