# Fintech_Project_2

![] (<https://blockupdate.io/wp-content/uploads/2019/02/price-chart.jpg>)

Introduction:

------------

## Goal

We use machine learning to pick the best technical indicators in order to build trade strategies that exit at the crest and enter in the trough.

## Table-of-Contents

* > [General Information](#General-Information)
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
* > [Usage](#project-status)
* >  [Contact](#contact)

## General Information

Our goal is to develop an effective learning model that can predict proper entry and exist signals in the highly volatile crypto market. The focus is on predicting the technical indicator signals which describes the behavior of the market.

## Customer Profile

 ![Customer](Projects\Fintech_Project_2\Photos\Customer.jpg)

A scalper trading utilizing a minute, hour, or day chart. This person loves using technical indicators but uses too many. They leave no clear direction when to enter or exist a trade.  

## Problems with Retail

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

![] (<https://keep.google.com/u/0/media/v2/1BGd0jzg9OYun-MV_1RnqOQGHMU3RSawG6vqwLa2GzxB0WpW_iPwbXk5ovFlMhg/18izKwj43WjHBrJ1FtkcNc-tx1zJgk4BTF1zKxICgQs8fDdXlBjdz1g4LZASM0B8?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp>)

### Trend

The Trend indicator determines whether an asset is currently overbought or oversold. Many trend following indicators, attempt to create a clear “channel". A simple moving average (SMA) calculates the average of a selected range of prices, usually closing prices, by the number of periods in that range.

Plot
![] <https://keep.google.com/u/0/media/v2/1m_RDurGykPqxmgePcEnvdw_xCQBzDdL9anGy4jY-0hIUMsEnuHnBuY33TrPpYDg/1RpfkNY84ELFuK86uBSdv7J6hVlSnIeK-ZAKfId2RrNSk16-hbgqVeR1OXqBhWMY?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp>

### Volatility

 As their name suggests, measure the volatility of the underlying instrument. We used the Bollinger Bands are composed of three lines. One of the more common calculations uses a 20-day simple moving average (SMA) for the middle band. The upper band is calculated by taking the middle band and adding twice the daily standard deviation to that amount. The lower band is calculated by taking the middle band minus two times the daily standard deviation.

Plot  
![] <https://keep.google.com/u/0/media/v2/16uvhcLW4uIPC3QyPoiw_8Nc4hSVGlHWsZ_SwAKFbiFj77mYOSn1jDfg9vB2uLg/1fp_AHDAagGdGf3r-oAvM5VPk-AUVMV8ubsACwg3NLrRVWJtMtADc6PhaDmTq2x0?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp>

## Scenario

The purpose of our project is to save the retail investor money and time. Our Crypto Surfer Trading Strategy has all three professional trader components making any retail trader a professional in their own right.

 Three things Pros have in Common

* > Patience
* > Toolbox
* > Strategy

## Solution

A trading strategy that combines multiple technical indicators into a single strategy.  

Use indicator classifications associated with, Momentum, Trend, Volume, and Volatility

Use indicators to create a machine learning model that produces buy and sale signals

Create the algorithm based on training data

Program the model to make entry and exist trade decisions without being explicitly programmed to do so.

formulate a trading plan for short and long term traders

## Features

01    |  API BinaceUS

02    |  Cleaning the Data

03    | Finta Library for Technical Analysis  

04    | Visualization  

05    |  Train and Test  

06    | Evaluate the Output

07    | Predictions

## Technical Indicators Feature Importance

Wave Trend Oscillator
Commodity Channel Index  
Rate of Change  
Awesome Oscillator
Relative Strength Index
Moving Average Convergence  
Divergence  
On-balance volume

(0.19236653373573173  wto_1
(0.16400925181915174  cci
(0.09976914179615039  wto_2
(0.09703509680838857  roc
(0.09571612728640447  ao
(0.07251030555076506  rsi
(0.043543500930910396  macd
(0.035880294082826676  macd_signal
(0.017123244894242724 obv
(0.01705180929365827 vzo

## Project Deliverables

* Scoping Document
* PowerPoint: ![] (<<https://docs.google.com/presentation/d/1VSRNFONOSUZY1YxwL1MqjSz356H-E5XEOY-3BjLQeCw/edit?usp=sharing>)
* README.md:
* GitHub Repository:  ![] (<<https://github.com/Drewmyself2code/Fintech_Project_2.git>

## Usage

![] (<<<https://github.com/Drewmyself2code/Fintech_Project_2/blob/main/Development_Code/cryptosurfer.ipynb>

## Accomplishments

We found that the indicators that are similar to price action are more highly correlated.  
Indicators such as WTO, ROC, CCI, are better predictors of signals

## Lessons Learned

Find a way to build a consolidated signal of all indicators
Need to find the right Deep learning model to fit our needs

## Acknowledgements

Thank you to the members of Crypto Surfers, Andrew Fernandez, Emerson Wen, and Jamel Boyer

## Contact

![] (<<<https://camo.githubusercontent.com/fd6a567de738e5bb9feb1114af7edf74832c1c671c7bb6d7079f306210f13512/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f336f6553414c52794834725953334e7438512f67697068792e676966>)

Team Baby Yoda
