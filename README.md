# Algo Trading Project
Algo strategy execution with backtest displayed on line price chart with estimated returns. Allows user to adjust candlestick trade timeframe and TP/StopLoss for varying results. New feautures added as needed. Run on jupyterlab.

--- 

## Technologies

This project leverages Python 3.7 and Jupyter Lab with the following packages:

* [Pandas] (https://github.com/pandas-dev/pandas) - To create and manipulate dataframes
* [Numpy] (https://github.com/numpy/numpy) - To calculate and add indicators to dataframes
* [YFinance] (https://github.com/ranaroussi/yfinance) - To pull market data for analysis
* [Tradingview-TA] (https://github.com/brian-the-dev/python-tradingview-ta) - For market sentiment & recommendations from Tradingview
* [MPLFinance] (https://github.com/matplotlib/mplfinance) - Used to create candlestick chart & display indicators 
* [HVPlot] (https://github.com/holoviz/hvplot) - Used to backtest algo strategy and display on hvplot as buy and sell signals

(Import code blocks included in application)

--- 

## Installation Guide

Before running the application, first install the following dependencies 

```python
  pip install pandas
  pip install numpy
  pip install yfinance
  pip install tradingview_ta
  pip install --upgrade mplfinance
  pip install hvplot
  
```

---

## Examples

Upon running the inital code for yfinance data, you will asked to input a stock ticker for data.

![Yfinance Data Prompt](Images/Yfinance_Data.PNG)

Input in the following format 

![Yfinance Data Prompt Complete](Images/Yfinance_Data2.PNG)

--- 

The following code will display a candlestick chart with 8/13/21 EMA's, ADX, and Volume. Must run all code blocks beforehand for this to display properly.

![Candlestick Created](Images/Candlestick_Display.PNG)


--- 

After running the implement_ema_strategy function, running the following code will prompt you with a Take Profit % and Stop Loss %. Set these according to your preferences to backtest your algo against historical data. 

![Candlestick Created](Images/tp_stoploss.PNG)

---



## Usage


#Contributors


#

