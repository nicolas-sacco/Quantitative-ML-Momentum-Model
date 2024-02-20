# Quantitative-ML-Momentum-Model
Quant machine learning momentum model developed in python

#Quantitative ML Momentum Model

##Objective: Capitalize on Equities that Display "Momentum" to the Upside & Downside (Long & Short)

##Steps:

1. Get Data: Clean, normalize, and get SPY data in a form that we can feed into our machine learning model
2. Calculate Relative Strength Index, Z-Score and Exponential Moving Average of the S&P 500
3. Develop Algorithm: Create Entry Indicators to Quantify 'Momentum' for Short and Long Positions
4. Analyze Performance: Evaluate performance of our Algorithm using Diagrams of Historical Performance (i.e. matplotlib)


##Explanation of Model

**Momentum investing** is  based on the idea that securities that have performed well in the past will continue to perform well in the future, and those that have performed poorly will continue to perform poorly.
           

The following Momentum Model capitalizes on the tendency for assets that have exhibited strong performance over a recent period to continue performing well, and vice versa. The Model utilizes the **Relative Strength Index (RSI**), **Z-Score** and **Exponential Moving Average (EMA)** to **quantify the 'momentum' in the specified direction**


**Long Position Criteria**

---
Relative Strength Index (RSI) : RSI <= 45 (OverSold)

Z-Score : 1 < Z-Score < 1.5 (1std deviation from mean)

Exponential Moving Average (EMA) : Current Price > EMA (Recent Bullish Bias)




**Short Position Criteria**

---
Relative Strength Index (RSI) : RSI >= 65 (OverBought)

Z-Score : -1.5 < Z-Score < -1 (-1std deviation from mean)

Exponential Moving Average (EMA) : Current Price < EMA (Recent Bearish Bias)
