# Creating Index Fund
Equity money management strategies are largely classified as either ‘active’ or ‘passive’. The most common passive strategy is that of “indexing” where the goal is to choose a portfolio that mirrors the movements of the broad market population or a market index. Such a portfolio is called an index fund. For example, the QQQ Index fund tracks the NASDAQ-100 index.
Constructing an index fund that tracks a specific broad market index could be done by simply purchasing all n stocks in the index, with the same weights as in the index. However, this approach is impractical and expensive (rebalancing costs may frequently be incurred, price response to trading). An index fund with m stocks, where m is substantially smaller than the size of the target population, n, seems desirable.
Via this project, we aim to create an Index fund with m stocks to track the NASDAQ-100 index.  
 
 
 
# Solution For the Problem 
 We solved this problem in two stages:
  - Integer Programming: Selection of stocks is an integer programming problem.The objective of the problem is to keep minimum stocks that are best representative of the majority of stocks in the fund. The notion of similarity was calculated using the correlation between the daily returns for each stock.
  - Linear Programing: Once the stocks have been selected, they need to be weighted in the portfolio. The weighing was done with the objective of minimzing the total absolute deviation between the fund returns and the index fund returns.


In addition to that, we also posed this problem as a mixed integer programming and compared the results for both the approaches.  
  
