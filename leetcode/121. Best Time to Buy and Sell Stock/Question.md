# QUESTION 

You are given an array prices where prices[i] is the price of a given stock on the ith day.

### EXAMPLES 

1. Input: prices = [7,1,5,3,6,4]
Output: 5
Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
Note that buying on day 2 and selling on day 1 is not allowed because you must buy before you sell.

2. Input: prices = [7,6,4,3,1]
Output: 0
Explanation: In this case, no transactions are done and the max profit = 0.

### CONSTRAINTS 

- 1 <= prices.length <= 105
- 0 <= prices[i] <= 104