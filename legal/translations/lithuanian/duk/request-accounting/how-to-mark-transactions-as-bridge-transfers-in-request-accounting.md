---
description: >-
  While Request Accounting automatically tracks your crypto transactions,
  properly recognizing bridge transfers requires special attention. Our new
  feature allows you to mark transactions as bridge tran
---

# How to Mark Transactions as Bridge Transfers in Request Accounting

### What Are Bridge Transfers? <a href="#h_01043425f0" id="h_01043425f0"></a>

Bridge transfers are transfers that happen across multiple blockchain networks, allowing users to move tokens or assets between different chains (e.g., from Solana to Ethereum, or Ethereum to Polygon). This interoperability is key to using Web3 to its fullest potential.

### Why Recognizing Bridge Transfers Matters for Accounting <a href="#h_06faede727" id="h_06faede727"></a>

Previously, Request Accounting treated bridge transfers as separate transactions:

* The outflow from one chain was treated as a standalone outflow
* The inflow to another chain was treated as a standalone inflow

This approach calculated realized gains/losses on the outflow.\
​

With the new implementation, linked bridge transfers are properly recognized as internal transfers, preventing incorrect accounting calculations by not calculating realized gains/losses for these movements.

### How to Mark Transactions as Bridge Transfers <a href="#h_3c62146655" id="h_3c62146655"></a>

The bridge transfer marking feature is only available for outflow transactions:

1. Identify the outflow transaction you want to mark as a bridge transfer
2. Click the three dots icon next to the transaction
3.  Select "Mark as Bridge"

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510067954/c609875f9ad5faad9e68e052ec32/image.png?expires=1751479200\&signature=d24133a41ac9343880b94dadd8e0b70d5918d59c6ed942fe1b300d171ecdcc87\&req=dSUmFsl4mohaXfMW3nq%2Bgb4NyMsC4m6R6AO1GYbvZM1ZI9UZ7NRygxBoXxFg%0A1a6RCTrdr66lpoQiOy%2F9kz3WdmE%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510067954/c609875f9ad5faad9e68e052ec32/image.png?expires=1751479200\&signature=d24133a41ac9343880b94dadd8e0b70d5918d59c6ed942fe1b300d171ecdcc87\&req=dSUmFsl4mohaXfMW3nq%2Bgb4NyMsC4m6R6AO1GYbvZM1ZI9UZ7NRygxBoXxFg%0A1a6RCTrdr66lpoQiOy%2F9kz3WdmE%3D%0A)
4. In the popup that appears:
   * Verify the origin transaction details (including hash and fiat details)
   * Select the destination network where funds were bridged to
   * The system will automatically search for matching inflow transactions
   * If no transaction is found automatically, manually paste the transaction hash
5.  Confirm the match between the outflow and inflow transactions

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510068713/ead9cc50dcf0131bc4c9f228f93f/image.png?expires=1751479200\&signature=2c71bbc7fcea61d4ce5358d4c4d0056dd8bf7e9c5b04927b8f177777b0ef83ea\&req=dSUmFsl4lYZeWvMW3nq%2Bgb67ScJYS9MKKruLtIEWKq2GvzmGOH3YhWFA4SX7%0A6tdsrjXzmwbkKwFboCWN81GQfk0%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510068713/ead9cc50dcf0131bc4c9f228f93f/image.png?expires=1751479200\&signature=2c71bbc7fcea61d4ce5358d4c4d0056dd8bf7e9c5b04927b8f177777b0ef83ea\&req=dSUmFsl4lYZeWvMW3nq%2Bgb67ScJYS9MKKruLtIEWKq2GvzmGOH3YhWFA4SX7%0A6tdsrjXzmwbkKwFboCWN81GQfk0%3D%0A)
6. Link the transactions

Important Notes:

* Once transactions are marked as bridge transfers, they're treated as internal transfers in the accounting system
* This ensures accurate financial reporting without inappropriate gain/loss calculations

Coming soon: Automatic recognition of bridge transfers to eliminate manual linking.
