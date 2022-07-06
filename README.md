# Fintech_Project_2

Introduction:

------------

## Goal

We are developing an effective learning model that can predict proper entry and exist signals for short and long term trades in the highly volatile crypto market.

## Trading Strategy

Our trading strategy combines multiple technical indicators into a single strategy. A stragey that makes investment decisions based on future price movements derived primarily from historicl prices. We leverage signals poduced by indicators to determine entry and exit points. These indicators fall into three categories which include:

                    1) Momentum Indicators -  

                    such as the Relative Strength Index (RSI), allow you to determine the direction and strength of a current price trend. As an asset begins to build momentum, opening a new position will become less risky. Looking at Moving Average indicators also help you gauge momentum.

                    2)Trend Indicators -

                    Allow you to determine whether an asset is currently overbought or oversold. Many trend following indicators, such as Bollinger Bands, attempt to create a clear “channel". A clear channel will tell you whether prices are close to breaking out or returning to normal.

                    3)Volume Indicators -

                    Help traders identify the (strong) relationship between price and volume. Increases in trading volume almost always result in an increase in price. However, these events do not always occur at the same time, which is why volume indicators are good for advanced forecasting. The On Balance Volume (OBV) and Money Flow are two of the most useful volume indicators.


                                  #############NOTES####
##Customer Profile:

Short Term Investment Plan
A scalper trading or trader utilizing a min, hr, or day chart. Loves using technical indicators but uses to many leaving no clear director to enter or exist a trade. Our customer is happy reciving %15 APY on thier investment whithin a year. 

##Investment Plan

•Investment $500
•Enter
•Exist
•Crpyto Currency
•Length 1 1/2
•Profit 10 -20
•Risk $500


##Long Term Investment Plan
A trader utilizing the daily chart has more time to think about the different signals and analyses the chart in detail. But what if you want to dollar cost average in or at of your long term investment. 

In



What is your style or strategy, goal, or risk management measures?
If you are new to trading we will create one for you.

Simply put, a trading plan helps by identifying expected outcomes, setting realistic goals, understanding a risk profile, which in turn determines a trading strategy and style. This helps to eliminate emotional pitfalls that might be present when one is trading.

However, formulating a trading plan is just the initial step. What comes next is evaluation. It is important to note that a trader must constantly analyse each and every individual trade undertaken and its following results closely. Was the plan followed, and if not, why? The frequency of evaluation differs from trader to trader. Intraday traders should do a daily review of their trades, while for long-term traders, it might be sufficient to do a weekly review.

Having a trading plan also allows an individual to track whether there have been improvements made. After each analysis of the trader’s performance, they can discover where things went right or wrong. No one can be a perfect trader as losses are part of the game. However, by constantly analysing performance, errors and weaknesses can either be eliminated or reduced, whereas, winning streaks can be further built upon.

0.1000% / 0.1000%
Profit
Cumlative Returns 

classta.trend.CCIIndicator(high: pandas.core.series.Series, low: pandas.core.series.Series, close: pandas.core.series.Series, window: int = 20, constant: float = 0.015, fillna: bool = False)
Commodity Channel Index (CCI)

CCI measures the difference between a security’s price change and its average price change. High positive readings indicate that prices are well above their average, which is a show of strength. Low negative readings indicate that prices are well below their average, which is a show of weakness.

http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:commodity_channel_index_cci

Parameters
high (pandas.Series) – dataset ‘High’ column.

low (pandas.Series) – dataset ‘Low’ column.

close (pandas.Series) – dataset ‘Close’ column.

window (int) – n period.

constant (int) – constant.

fillna (bool) – if True, fill nan values.

cci() → pandas.core.series.Series
Commodity Channel Index (CCI)

Returns
New feature generated.

Return type
pandas.Series

MACD
classta.trend.MACD(close: pandas.core.series.Series, window_slow: int = 26, window_fast: int = 12, window_sign: int = 9, fillna: bool = False)
Moving Average Convergence Divergence (MACD)

Is a trend-following momentum indicator that shows the relationship between two moving averages of prices.

https://school.stockcharts.com/doku.php?id=technical_indicators:moving_average_convergence_divergence_macd

Parameters
close (pandas.Series) – dataset ‘Close’ column.

window_fast (int) – n period short-term.

window_slow (int) – n period long-term.

window_sign (int) – n period to signal.

fillna (bool) – if True, fill nan values.

macd() → pandas.core.series.Series
MACD Line

Returns
New feature generated.

Return type
pandas.Series

macd_diff() → pandas.core.series.Series
MACD Histogram

Returns
New feature generated.

Return type
pandas.Series

macd_signal() → pandas.core.series.Series
Signal Line

Returns
New feature generated.

Return type
pandas.Series

So now we'll calculate the MACD with pandas-ta; it'll give us three columns, one is of the difference between the two EMA's called MACD and one is the EMA of MACD value called as Signal, and the last one is the difference between MACD & Signal called as MACD histogram.

SMA - Simple Moving Average

Parameters
close (pandas.Series) – dataset ‘Close’ column.

window (int) – n period.

fillna (bool) – if True, fill nan values.

sma_indicator() → pandas.core.series.Series
Simple Moving Average (SMA)

Returns
New feature generated.

Return type
pandas.Series

import pandas as pd
from ta.utils import dropna
from ta.volatility import BollingerBands



ta.volatility.bollinger_mavg(close, window=20, fillna=False)
Bollinger Bands (BB)

N-period simple moving average (MA).

https://en.wikipedia.org/wiki/Bollinger_Bands

Parameters
close (pandas.Series) – dataset ‘Close’ column.

window (int) – n period.

fillna (bool) – if True, fill nan values.

Returns
New feature generated.

Return type
pandas.Series





