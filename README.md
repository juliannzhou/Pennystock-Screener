# Pennystock-Screener

This is a screener that scans for stocks based on market cap, public float, last price, pre-market volume, last volume, and float rotations. The screener also recognizes historical resistance level and compares the current price with the level using historical end-of-day data. Additionally, the program exports scanned data in csv files for statistics tracking(see cache for samples). It is designed to select stocks that satisfy the conditions for daytrading patterns popularized by trader Timothy Sykes, Steven Dux, and Tim Grittani. The patterns I am currently working on are gap-up short(shorting into morning spikes), bounce short(shorting into historical resistance), and first red day(shorting into a morning panic of a stock that has been green for the previous three days).

The criteria for the patterns are based on Steven Dux's Duxinator and Tim Grittani's Trading Ticker. I am currently working on a graphical user interface for the screener and I intend to integrate it into a larger project that connects with a brokerage account for algorithmic trading.

![Web 1920 – 1-3](https://user-images.githubusercontent.com/65748924/123631112-f7b4d380-d848-11eb-9d4b-3fa574301979.png)

![Web 1920 – 2](https://user-images.githubusercontent.com/65748924/123742921-09e15100-d8df-11eb-8bd3-18a83b7c9018.png)

![Web 1920 – 4 pre-flip](https://user-images.githubusercontent.com/65748924/123800363-ce18ac80-d91b-11eb-8751-fe097919f4f0.png)
