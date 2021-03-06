## Range Breakout Trading Algorithm
This trading algorithm uses a breakout of a consolidation in prices as the basis for making trades.
Such a period of consolidation can be found throughout the day, whether it is a certain trading session or slow periods during the day. One can find such periods through volume analysis as well.

The aim of this algorithm is to create a template algorithm, designed not to be an out-of-the-box profit churner, but rather to provide a framework for the user to mould to a specific strategy.

Here is the basic algorithm:

![Algorithm for range trading](https://github.com/osghaffar/osghaffar.github.io/blob/master/images/breakout-algo.png "Algorithm for range trading")


Here is the algorithm in action, with a profitable trade taken after a breakout. The blue marker represents the entry (just beyond the range set) and the yellow marker represents the profit successfully taken:

![Breakout trade](https://github.com/osghaffar/osghaffar.github.io/blob/master/images/breakout-trade.png "Breakout trade")

Areas of possible improvement/further research:
- adjusting the profit/loss levels based on optimized backtests
- creating a threshold beyond just the high and the low (the market often retests a high/low, this doesn't necessarily result in a breakout)
- adding additional volume analysis to help predict a breakout
