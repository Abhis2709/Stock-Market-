# Stock-Market-
There are  2 files as shown below:

Tasks:
1. "trades_file.csv" : contains the intraday trades made by a trading system .

time -> time of trade
symbol -> symbol of the instrument in which the trade is made
tradeSize -> quantities traded in the symbol . tradeSize > 0 if instrument is
bought and tradeSize < 0 , if the instrument is sold
tradePrice -> the price at which the trade in the instrument is made


2. "prices_file.csv" : contains 1 min data for the prices of all symbols

time -> time at which the price is recorded
symbol -> symbol of the instrument
price -> last traded price for the instrument



3.The trading system made the trades given in the trade file , and whatever
position was left at 15:25:00 was squared off by the system ( Square off
trades not included in the trades file ) . Square off means exiting the current
position by executing opposite trade with same quantity. So if I have -3
position in symbol A , square off trade will have +3 as trade size, with trade
price as given in prices file. Assume that system is able to square off
positions of all symbols at the 15:25:00 price provided in the prices
file.Calculate the profit/loss made the trading system at the end of the day
using information and files provided.
Report the symbols with max PNL and min PNL .
Use the 2 files to calculate the PNL at each timestamp in the prices files. Use
that to calculate the maximum intraday drawdown . Also draw chart of
intraday PNL ( Time vs PNL ).[prices_file (1) (1).csv](https://github.com/Abhis2709/Stock-Market-/files/10475047/prices_file.1.1.csv)
[trades_file (1) (1).csv](https://github.com/Abhis2709/Stock-Market-/files/10475048/trades_file.1.1.csv)
