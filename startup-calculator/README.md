# Finance Forecasting Model
This script forecasts your future finances based on current cash position, growth rate, revenue, and costs.

Using pandas, it tries to answer two questions:

1. The most conservative scenario: if you fail to grow at all from this point, when you will run out of money and die? 
2. If you continue to grow at your current rate, when you will run out of money and die?

"Running out of money" is actually defined as having less than 25,000 in the bank, as this is presumed to be the minimum amount to wind down the company in a suitable fashion. 

It also uses Altair to plot [Default alive / Default dead](http://paulgraham.com/aord.html): the growth rate you will need to achieve to never die. This plot is inspired by a [similar one](http://growth.tlb.org/#) by Trevor Blackwell.

