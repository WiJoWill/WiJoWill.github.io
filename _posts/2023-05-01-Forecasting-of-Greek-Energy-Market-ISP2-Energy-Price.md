---
title:  "Forecasting of Greek Energy Market ISP2 Energy Price"
mathjax: true
layout: post
categories: project
---
#### Keywords: European energy market, price prediction, LSTM, DNN-LSTM, modern RNN, Time-series analysis

### Description:
EnergyLive is a European power market data platform based in Greece. It aims to give investors, executives, and traders 
an overview of electricity market prices, mainly focusing on European electricity market data and analysis. The platform 
offers services including customized alerts, weekly reports with key observations, and bi-monthly reports on forecasts of 
Greek power prices.

The wholesale electricity market in Greece contains three separate markets that operate sequentially, 
which are the day-ahead market(DAM), the intra-day market(CRIDA), and the balancing market(ISP). 
In each of the markets, there are segmented markets depending on the time between now and the time of delivery. 
Our current task is to predict Greek electricity prices in balancing market 2(ISP2) using various algorithms 
such as machine learning and time series, given a range of inputs such as the forecasted load and renewable energy sources(RES) 
generation for this day. The output model can be used to optimize the dispatch of a battery storage plant on a daily basis.

Combining the characterisitics of time series and input factors, we select LSTM and DNN-LSTM architectures to forecast the energy price,
which are represented by eight major energy price and indicators. We mainly simulate the price for upward automatic Frequency Restoration 
Reserve (aFRR), which is a faster-acting reserve capacity that is needed to balance the system when there is a sudden loss of 
generation or demand and the price for downward balancing energy (DBE), which is additional power that is needed to balance the 
system when the supply of electricity exceeds the demand.

This is a sample image of simulation results:

![poster](/assets/LSTM-result.png)

Report: Please mail to me (hw2894@columbia.edu) or through the mail symbol at the right bottom.

