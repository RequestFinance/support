---
description: >-
  Understand in detail about how swaps are synced with your ERP and how the
  resulting gains and losses are calculated
---

# How to Account for Cryptocurrency Swaps in Request Accounting

### What is a cryptocurrency swap? <a href="#h_8fa2a13a43" id="h_8fa2a13a43"></a>

A swap converts one token to another within the same wallet, such as converting ETH to WRAPPED ETH. The transaction flows through a swapping contract that facilitates the exchange.

### How does Request Accounting handle swaps? <a href="#h_79e89afba7" id="h_79e89afba7"></a>

Request Accounting treats each swap as two separate asset movements:

* Outflow: Original token leaves your wallet to the swapping contract
* Inflow: New token arrives from the swapping contract to your wallet

### Why does only the outflow sync to my ERP software? <a href="#h_f3baa4501b" id="h_f3baa4501b"></a>

To prevent double counting in QuickBooks or Xero, Request Accounting only syncs the outflow transaction. You must manually assign both debit and credit accounts on this single outflow line to complete the accounting entry.

### How do I categorize a swap transaction? <a href="#h_ad2ab0fe37" id="h_ad2ab0fe37"></a>

Using ETH to WRAPPED ETH as an example:

On the outflow line:

* Credit: ETH account (asset leaving)
* Debit: WRAPPED ETH account (asset acquired)

On the inflow line:

* Use a common categorization that cancels out the entry

### What types of gains and losses occur during swaps? <a href="#h_c87c4b0d6e" id="h_c87c4b0d6e"></a>

1\. Realized Gain/Loss on Original Token This reflects the appreciation or depreciation of your original token since purchase.

_Example_: You bought 1 ETH for $1,000 last year. Today you swap it when it's worth $2,000, creating a $1,000 realized gain.

2\. Swap Slippage Gain/Loss This captures the difference between expected and actual swap values due to market conditions and fees.

_Example_: You swap $2,000 worth of ETH but receive only $1,990 worth of WRAPPED ETH, resulting in a $10 loss.

### Do I need to track both types of gains/losses? <a href="#h_aa2c98daa6" id="h_aa2c98daa6"></a>

Yes, both are important for accurate tax reporting and financial records. The realized gain/loss affects your cost basis calculations for future transactions, while slippage losses may be deductible business expenses depending on your jurisdiction's tax laws.
