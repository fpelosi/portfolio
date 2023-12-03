---
layout: post
title: "A Guide to Managing Fees when Dollar-Cost Averaging in Crypto with Coinbase"
date: "2023-12-03"
categories: [personal-finance]
image: https://images.unsplash.com/photo-1621761191319-c6fb62004040?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
excerpt: "I've been investing in cryptocurrencies for many years now, and while I see opportunity, the volatility of the markets and trying to time when to buy was always discouraging to me. One strategy that offers a steady approach is dollar-cost averaging. If you're navigating this journey through platforms like Coinbase, understanding the fee structure is paramount, especially when employing the dollar-cost averaging strategy that involves frequent trades."
carousels:
  - images: 
    - image: /assets/images/LINK_Trade_Coinbase_App_10_edit.png
    - image: /assets/images/LINK_Trade_Coinbase_App_100_edit.png
    - image: /assets/images/LINK_Trade_Coinbase_App_250_edit.png
---

I've been investing in cryptocurrencies for many years now, and while I see opportunity, the volatility of the markets and trying to time when to buy was always discouraging to me. One strategy that offers a steady approach is dollar-cost averaging. If you're navigating this journey through platforms like Coinbase, understanding the fee structure is paramount, especially when employing the dollar-cost averaging strategy that involves frequent trades.

## Comparing Costs: Coinbase App vs. Coinbase Advanced Trade API

Now, let's explore how costs may differ when executing the same trade in the Coinbase app compared to using Coinbase Advanced Trade API. Let's break down the fees using a concrete example. Imagine you're committed to a $10, $100, or $250 weekly or monthly investment in LINK/USD through dollar-cost averaging with Coinbase. Here's a detailed look at how fees might impact your weekly investment.

### Coinbase App
When buying directly on the Coinbase app, the percentage fee varies based on the dollar amount of the trade. Let's look at some real examples below.

- For a $10 trade, you'll pay a fee of $0.99 (9.9%) per transaction.
- For a $100 trade, you'll pay a fee of $2.99 (2.99%) per transaction.
- For a $250 trade, you'll pay a fee of $3.67 (1.468%) per transaction.

Here is a [link](https://help.coinbase.com/en/coinbase/trading-and-funding/pricing-and-fees/fees){:target="_blank"} to the Coinbase app fee documentation. It's rather vague.

### Coinbase Advanced Trade API
Coinbase Advanced, previously known as Coinbase Pro, allows users to make trades using a [Maker/Taker](){:target="_blank"} fee structure. Unless you're trading huge volumes, you'll likely fall into one of these three fee brackets.

| Level | Trading Amount | Maker Fees | Taker Fees |
| --- | --- | --- | --- |
| Advanced 1 | >= $0 | 0.60% | 0.80% |
| Advanced 2 | >= $1K | 0.35% | 0.55% |
| Advanced 3 | >= $10K | 0.25% | 0.40% |

If you'll be dollar-cost averaging, you'll be the Taker in the trade because you want your order to execute immediately at the market price. I am currently in the Advanced 2 bracket. For the same trades, as shown above, below is a breakout of the fees using Coinbase Advanced Trade.

- For a $10 trade, you'll pay a fee of $0.055 (0.55%) per transaction.
- For a $100 trade, you'll pay a fee of $0.550 (0.55%) per transaction.
- For a $250 trade, you'll pay a fee of $1.375 (0.55%) per transaction.

### Comparison
Suppose you're making a $10 weekly investment. In the Coinbase app, the total fees for dollar-cost averaging for one year would be $51.48. That's over five weeks worth of investments paid in fees. On the other hand, using Coinbase Advanced Trade, the total fees for dollar-cost averaging for one year would be $2.86.

## A Problem for Many
At this point, you may be wondering why everyone doesn't use Coinbase Advanced Trade for dollar-cost averging. Simply put, the Coinbase app offers convenience and ease of use, especially for less technical users. The Coinbase app offers out-of-the-box dollar-cost averaging functionality.

If you are going to dollar-cost average using Coinbase Advanced Trade, you will have to use their [API](https://www.coinbase.com/cloud/products/advanced-trade-api). I worked with a friend to get this process set up, and it was worth the time investment.

## Optimizing Your Approach

Regardless of using the Coinbase app or Coinbase Advanced Trade, consider these strategies to optimize your investment approach on both platforms:

- **Consolidate Investments:** When investing on the Coinbase app, aim for larger, less frequent transactions to minimize fees. For example, instead of placing a weekly $20 trade, consider placing a monthly $100 trade. This alone will drop your fee percent from 9.9% to 2.99%. This is a considerable amount over the long term.
- **Strategic Planning:** Calculate and compare fees based on your investment frequency and amount to make informed decisions.
- **Stay Informed:** Regularly check and adapt to any changes in fee structures on your chosen platform.

By understanding the nuances of fees and tailoring your approach, you can make the most out of your dollar-cost averaging strategy.