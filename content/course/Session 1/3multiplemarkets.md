---
title: Multiple Markets
linktitle: Multiple Markets
type: book
date: "2019-05-05T00:00:00+01:00"

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## Multiple Markets

<p>So far, we have looked at how individual orders operate within one market. However, multiple markets exist for trading the same asset. These multiple markets lead to what is called “fragmented markets." Each market operates with slightly different order priorities and rules of trading, consequently, making trade more complicated. Orders that may execute first in one market may not execute at all in another market. Understanding these rules of execution priority and making decisions about which market is the best for a given order is an important part of trading in fragmented markets. The next video will illustrate how multiple markets have an effect on calculating execution prices.
</p>
 
### Video: Introduction to Multiple Markets
{{< video library="true" src="Introtomultiplemarkets.mp4" controls="yes" >}}

### Calculating Execution Prices
<p>What does it mean to calculate the execution price?
</p>

<p>Throughout the rest of this course, you will sometimes be asked to “calculate the execution price” of a bid or offer. This means that you should delete any transacting bids and offers from the order book and then list any order that transacts in the sequence in which they execute. You should include how many shares and at what price. See the example below.</p>
<p>Example:</p>
{{< figure library="true" src="execprice1.png"  >}}

<p>This example has some orders that would transact and therefore, it is not an authentic view of an order book because those transactable orders would immediately execute and be deleted from the order book. </p>
<b>For example:</b>
<p>“The bid for 200 shares at $5.18 would immediately transact with the offer for 100 shares at $5.07. That offer would be completely fulfilled and would immediately disappear. There would be 100 shares of the bid at $5.18 remaining.</p>
<p>Then, the remaining 100 shares of the bid for 200 shares at $5.18 that did not previously transact would  execute against the next top-of-book offer for 150 shares at $5.12.”
</p>
<p>The resulting order book after the transaction would look like this:</p>
{{< figure library="true" src="execprice2.png"  >}}