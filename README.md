# Algorithmic-Trading-Bot

This project was done as part of ELEC4546 Investing and Trading for Engineering Students.

An algorithmic trading bot was developed to trade major currency pairs on the Forex market using technical indicators.
 
The first phase of this project involved creating functions for various commonly used technical indicators such as MACD, ADX, Bollinger Bands, ATR, SMA, etc.
 
Following this, 2 trading strategies were created: ADX-MACD and SMA-Stochastic
 
The most optimal input parameters for the indicators were selected by performing a back test on historical Eur-USD data with several combinations and choosing the one that  yielded the highest Sharpe ratio.

A paper trading account was created on the OANDA platform and a connection was established using the API

Whenever a trade signal is generated, the bot automatically sends orders to OANDA 

By editing the main() function, the script can be programmed to run for a desired time and at desired intervals. 
 
