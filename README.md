# Fintech_Project_2

![BlockUpdate](<https://blockupdate.io/wp-content/uploads/2019/02/price-chart.jpg>)

Introduction:

## Crypto_Sufers

We use machine learning to pick the best technical indicators in order to build trade strategies that exit at the crest and enter in the trough

--------
![Crypto_Sufers](https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Photos/Screenshot%2010.jpg)

## Table-of-Contents

* > [Goal](#Goal)
* > [Customer Profile](#Customer-Profile)
* > [Problems with Retail](#Problems-with-Retail)
* > [Technical Indicators](#Technical-Indicators)
* >  [Scenario](#features)
* >  [Three things Pros have in Common](#Three-things-Pros-have-in-Common)
* >  [Scenario](#Scenario)
* >  [Solution](#Solution)
* > [Features](#Features)
* > [Technical Indicators Feature Importance](#Technical-Indicators-Feature-Importance)
* > [Project Deliverables](#Project-Deliverables)
* > [Features](#Features)
* > [Usage](#Usage)
* >  [Contact](#contact)

## Goal

Our goal is to develop an effective learning model that can predict proper entry and exist signals in the highly volatile crypto market. The focus is on predicting the technical indicator signals which describes the behavior of the market.

## Customer Profile

 ![Customer](https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Photos/Customer.jpg)

A scalper trading utilizing a minute, hour, or day chart. This person loves using technical indicators but uses too many. They leave no clear direction when to enter or exist a trade.  

### Problems with Retail

* > Time spent analyzing charts
* > Panic trading
* > False signals
* > Fraud
* > Market Manipulation
* > Inconsistent trading
* > Confused by indicators

## Technical Indicators

### Momentum

Momentum indicators return a selling signal when prices start to move strongly higher, and a buying signal when prices start to move strongly lower. We used the Moving Average Convergence/Divergence Index indicator to measure momentum.

MACD
Is a trend-following momentum indicator that shows the relationship between two moving averages of prices.The MACD is calculated using two exponential moving averages (EMA) - short term and long term. An exponential moving average of MACD is used as a signal line to indicate the upward or downward momentum. An exponential moving average is nothing but simply a moving average that gives more weightage to the recent data.

plt.show
![MACD!](https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Photos/MACD.jpg)

### Trend

The Trend indicator determines whether an asset is currently overbought or oversold. Many trend following indicators, attempt to create a clear “channel". A simple moving average (SMA) calculates the average of a selected range of prices, usually closing prices, by the number of periods in that range.

plt.show
![SMA](https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Photos/SMA.jpg)

### Volatility

 As their name suggests, measure the volatility of the underlying instrument. We used the Bollinger Bands are composed of three lines. One of the more common calculations uses a 20-day simple moving average (SMA) for the middle band. The upper band is calculated by taking the middle band and adding twice the daily standard deviation to that amount. The lower band is calculated by taking the middle band minus two times the daily standard deviation.

bitcoin_trend_cstkplt  
![BB](https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Photos/BB.jpg)

### Scenario

The purpose of our project is to save the retail investor money and time. Our Crypto Surfer Trading Strategy has all three professional trader components making any retail trader a professional in their own right.

 Three things Pros have in Common

* > Patience
* > Toolbox
* > Strategy

### Solution

A trading strategy that combines multiple technical indicators into a single strategy.  

Use indicator classifications associated with, Momentum, Trend, Volume, and Volatility

Use indicators to create a machine learning model that produces buy and sale signals

Create the algorithm based on training data

Program the model to make entry and exist trade decisions without being explicitly programmed to do so.

formulate a trading plan for short and long term traders

## Features

* >   |  API BinaceUS

* >   |  Cleaning the Data

* >    | Finta Library for Technical Analysis

* >  | Visualization

* >    |  Train and Test

* >   | Evaluate the Output

* >    | Predictions

## Technical Indicators Feature Importance

| Technical Indicators                            | Feature Importance      |  
| :---:                                            |      ----:                   |
| Wave Trend Oscillator1                         |    0.19236653373573173 |
|Commodity Channel Index  | 0.16400925181915174 |
|Rate of Change| 0.09703509680838857 |
|Awesome Oscillator| 0.09571612728640447 |
|Relative Strength Index | 0.07251030555076506 |
|Moving Average Convergence | 0.043543500930910396 |
|Divergence                                       |   0.017123244894242724 |
|On-balance volume | 0.01705180929365827 |

### Project Deliverables

* > Scoping Document
* > [PowerPoint] <https://github.com/Drewmyself2code/Fintech_Project_2/blob/bccd568bb0fd940b08ebb0cef6d0c612ff112112/PowerPoint/Copy%20Surfer.pdf>
* > README.md:
* > GitHub Repository:  <https://github.com/Drewmyself2code/Fintech_Project_2.git>

### Usage

 <https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Development_Code/cryptosurfer.ipynb>>

### Accomplishments

We found that the indicators that are similar to price action are more highly correlated.  
Indicators such as WTO, ROC, CCI, are better predictors of signals

#### Plotting Buy Sale Signals

![Buy & Sale Signals!](https://github.com/Drewmyself2code/Fintech_Project_2/blob/f2c08478ddc57ede75fd347bb2c3e21500dbe305/Photos/BuyAndSaleSignals.jpg)

### Lessons Learned

Find a way to build a consolidated signal of all indicators
Need to find the right Deep learning model to fit our needs. We also plotted buy and sale signals.

### Acknowledgements

Thank you to the members of Crypto Surfers, Andrew Fernandez, Emerson Wen, and Jamel Boyer

### Contact

![Investors? Possibly You?](https://github.com/Drewmyself2code/Fintech_Project_2/blob/f2c08478ddc57ede75fd347bb2c3e21500dbe305/Photos/investors.gif)

Team Baby Yoda
