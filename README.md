# Optimizing-Profitable-Trades-in-Forex-Market-using-ML-and-NN

## Defining Problem Statement
* In a world of Trading, no trader is 100% sure that he will get profited in all trades.
* Optimizing the profitable Trades means given the tradesetup details in trading whether the trader is going to be profitable or not. Just like patient comes to hospital and gets medical report then based on that model predicts him as cancer patient or healthy person. Here, a trade opportunity comes and trader enter details then after sometime he may get profit or loss. Then why optimizing profitable trades means here given trade opportunity details model may predict loss or profit. so, when model predict it's as profitable trade then only i will enter into trade else i avoid the trade.
* Usually In this data, Trader entered all trades near support or resistance lines not at random time and place.
* So, When the trader see an opportunity at resistance or support, he takes a look at technical analysis details (i.e 4H time frame market trend, D timeframe market trend, W timeframe market trend, resistance/support timeframe, candlestick pattern formed,candlestick pattern confirmation, how many times resistance/support got hitted ).
* Followed by it, he also observes technical indicator signals (i.e. major indicators used are CPR,EMA,Parabolic Sar,Bollinger Band,Ichimoku,RSI, Stochastic Oscillator & super trend)
* After all these confirmation he enters the trade. But, he is not sure that he is going to have a profitable trade or not.
* Hence, given the Trade entry detail (technical analysis details, technical indicators details ) we have to find whether the next trade is going to profitable or not .

## DataSet Description
* I collected forex trade entry details of AUDUSD, EURUSD, GBPUSD, NZDUSD, USDCAD, Gold & Bitcoin from January 2025 to present.
* Following are the Dataset column details :
1. Trade Entry Time : Time at which trade was excuted
2. Currency Pair : currency pair in which we entered for trade.
3. 4H Trend : Market movement from past few hours in 4 hour Timeframe
4. D Trend : Market movement from past few days in Day Timeframe
5. W Trend : Market movement from past few weeks in Weeks Timeframe
6. Reversal/Retrace : type of market movement at resistance/support.
7. 4H R_S Price : 4hour timeframe Resistance/suppport price level
8. D R_S Price : Day timeframe Resistance/suppport price level
9. W R_S Price : Week timeframe Resistance/suppport price level
10. R_S tf : timeframe of Resistance/support where we entered trade.
11. R_S : indicating whether it is a resistance line or support line.
12. Candlestick pattern : details of different candlestick patterns of market at trade entry time.
13. Candlestick confirmation : whether candlestick pattern confirmed or not when we are entering the trade.
14. no. of times R/S hitted : how many times market touched that resistance/support line previously.
15. Trade Entry TF : Market Timeframe in which we entered the trade.
16. Buy/Sell or Long/short : Type of Trade entered. In Buy or Long type of trade, we expect market to go up. Whereas in Sell or short type of trade, we expect market to go down.
17. entry : Price at which we enter the trade.
18. exit : price at which we exited the trade.
19. lot size : no. of lot size used for trading. It's just like investment amount.
20. pips difference : market price difference between entry and exit time. Simply, How far market moved.
21. return for 0.01 lotsize : profit/loss amount (in $) we got from trade using 0.01 lotsize.
22. return for 1 lotsize : profit/loss amount we got from trade using 1 lotsize.
23. Profit/SL : indicating entered trade got profit or stoploss(loss).
24. Trade Entry direction : Direction in which trade got excuted. For Buy(long) type trade, trade entry direction will be up. Whereas for Sell(short) type trade , trade entry direction will be down.
25. Market direction : Direction in which market acutually went.
26. CPR type : size of CPR indicator.
27. RSI : rsi indicator value.
28. Stochastic_buyers_signal : Stochastic oscillator indicator buyer's value.
29. Stochastic_sellers_signal : Stochastic oscillator indicator seller's value.
30. EMA 14 : signal given by moving average indicator, whether market go up or down.
31. SAR : signal given by Parabolic SAR indicator, whether market go up or down.
32. Bollinger Band : signal given by Bollinger Band indicator, whether market go up or down.
33. Ichimoku_line : signal given by ichimoku indicator's lines, whether market go up or down.
34. Ichimoku_cloud : signal given by ichimoku indicator's cloud, whether market go up or down.
35. Super Trend : signal given by Super Trend indicator, whether market go up or down.

* **Note : For More details go through the project pdf**
