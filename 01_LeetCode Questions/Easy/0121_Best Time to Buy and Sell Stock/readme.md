<a href="https://leetcode.com/problems/best-time-to-buy-and-sell-stock/"><h1>121. Best Time to Buy and Sell Stock</h1></a>

- <h3>Question</h3>
    You are given an array prices where prices[i] is the price of a given stock on the ith day.

    You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.

    Return the maximum profit you can achieve from this transaction. If you cannot achieve any profit, return 0.
<hr>

- <h3>Examples</h3>
    <div>
    <b>Example 1:</b>

    Input: prices = [7,1,5,3,6,4]<br>
    Output: 5
    Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
    Note that buying on day 2 and selling on day 1 is not allowed because you must buy before you sell.
    </div>
    <br>
    <div>
    <b>Example 2:</b>

    Input: prices = [7,6,4,3,1]<br>
    Output: 0
    Explanation: In this case, no transactions are done and the max profit = 0.
    </div>
    <br>
<hr>

- <h3>Constraints</h3>
    → 1 <= prices.length <= 10^5 <br>
    → 0 <= prices[i] <= 10^4
<hr>