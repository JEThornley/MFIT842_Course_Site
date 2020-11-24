---
title: Floor and Limit Order Markets
linktitle: Floor and Limit Order Markets
type: book
date: "2019-05-05T00:00:00+01:00"
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

## Floor and Limit Order Markets

### How does an order book present information?
<p>A limit order book is a record of incoming orders, both to buy and sell shares of stocks. Orders to sell are referred to as offers. Orders to buy are referred to as bids. Below, you will find a guide on how to record order book transactions in Excel.</p>

<strong>Tracking Incoming Orders</strong>
<p>In the limit order books you will be viewing and constructing in this course, bids will be found on the left side, and offers will be found on the right side.
Bids and offers enter the order book at the time the order is made. Therefore, a bid may arrive before an executable offer is available.</p>
<p>Example:</p>
{{< figure library="true" src="introexec.png"  >}}

<strong>Price</strong>
<p>New orders enter the order book in terms of price. The highest priced bids are entered at the top of each column. Thus, bids and offers are in price order top to bottom.</p>
<p>Bids at the top of the bids columns execute against offers at the bottom of the offers columns.</p>
<strong>Time</strong>
<p>You may notice that the order book example above does not have timestamps. In this current view, we must assume that the bid for 200 shares at $9.98 could be from multiple traders. For example, it is possible that the first 100 shares at $9.98 came from Trader A and the second 100 shares at $9.98 came from Trader B.</p>
<p>Generally, order books choose to display this time-sensitive data in different ways. An effective order book coordinates with the software and algorithms you are using and is important to keep up with high-speed trading.  For most purposes, when you are submitting an order that will execute immediately, it is unimportant how many traders are behind a buy or sell order resting in the limit order book. For those traders that submitted the orders it is important to know if you are the first, or second, or third, … to execute. For instance, if there are 5 other traders with orders ahead of you at a certain price, you may decide to submit a new order at a better price, to move to the top of the queue at that new price or even execute against an order on the other side of the order book. </p>
<strong>Top-of-Book Orders</strong>
<p>The highest priced bid is considered the “top-of-book order.” Therefore, in the example above, the top-of-book bid is 9.98. </p>
<p>On the other hand, the lowest priced offer is considered the top-of-book order. Therefore, in the example above, the top-of-book offer is for 10.01.</p>
<p>The top-of-book orders are also called the best prices. </p>

### Video: Floor Markets
{{< video library="true" src="Floormarkets.mp4" controls="yes" >}}

### Video: Limit Order Markets
{{< video library="true" src="Limitordermarkets.mp4" controls="yes" >}}

### Video: Rules of Priority
{{< video library="true" src="Rulesofpriority.mp4" controls="yes" >}}

### Video: Marketable Limit Orders
{{< video library="true" src="Marketablelimitorders.mp4" controls="yes" >}}


### Recommended Readings

* **[Trading Floor - A Guide to Jobs and Work on the Trading Floor](https://corporatefinanceinstitute.com/resources/knowledge/trading-investing/trading-floor/) Corporate Finance Institute. (n.d.). Retrieved July 13, 2020, from  https://corporatefinanceinstitute.com/resources/knowledge/trading-investing/trading-floor/**


