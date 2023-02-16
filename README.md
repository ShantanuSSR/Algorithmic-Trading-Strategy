# Algorithmic-Trading-Strategy

This is an algorithmic trading strategy that uses a custom technical indicator to generate buy and sell signals for a given financial instrument. The strategy is implemented in Python.


Getting Started
To use this strategy, you will need to have Python 3.7 or higher installed on your system, along with the following libraries:

PyAlgoTrade
Pandas
Matplotlib
Numpy


Indicator
The custom technical indicator used in this strategy is a simple moving average crossover, which generates buy signals when the short-term moving average crosses above the long-term moving average, and sell signals when the short-term moving average crosses below the long-term moving average.


Strategy
The strategy class is responsible for generating buy and sell signals based on the custom technical indicator, and executing trades based on those signals. The strategy uses a fixed position sizing, and does not use stop-loss or take-profit orders. It also contains pointers that indicates where to buy and where to sell.



