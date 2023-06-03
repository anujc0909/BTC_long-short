# BTC_long-short
Volatility based spot LFT strategy. With adjustable risk factor. Back-test report with commission and charges as per binance and risk free rate 7% as in India.

This report reflects the back testing results of returns over 3.8 years of BTC/USDT data.  

It uses entire capital for trades, no position sizing, no take profit, no stoploss.  

It has primarily 2 versions  :-  
1. High sensitivity (High risk/drawdowns)  
3. Low sensitivity (Low risk/drawdowns)  
                              
Full reports are attached as HTMl files.  

Strategy contains of mailny one indicator with a two extremes. Switching between the two impact the risk appetite by lowering or increasing the sensetivity of the indicator.  

The trading or long/short logic has two components:-   
1.Trend following  
2. Trend reversal    

I have attached the returns report of HIGH sens and LOW sens. both versions using Quantstats library functions.
                                                   
Currently working on automating this strategy 100%, so the rules of tradin gcan be followed and the back-testing rules can be immitated, hoping to replicate its results.  


          
                   
