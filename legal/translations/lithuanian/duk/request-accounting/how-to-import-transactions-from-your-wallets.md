---
description: Learn how to connect your crypto wallets to Request Accounting
---

# How to import transactions from your wallets

Request Accounting allows you to connect both your crypto wallets and exchange accounts to track your transactions. This guide will walk you through the process of connecting your crypto wallets.

To connect your crypto wallets to Request Accounting, follow these steps:

1. Navigate to the [Wallets](https://accounting.request.finance/tracking) menu
2. Click on Add New Wallet
3. Enter your Wallet Address and Wallet Name (optional). We'll automatically recognize all active chains for the concerned wallet:
4.  Click on Import Wallet and wait until Request Accounting imports all your wallet data accurately. Once done, the processing status changes to Completed.

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1478478162/40e3ce1a50c941787862d33a9ad5/image.png?expires=1751479200\&signature=44a58d731721d79fcfb6ef23ae6752e8c1fed472ffbc7ffafaba203910c7f533\&req=dSQgHs15lYBZW%2FMW3nq%2BgZErAy%2Bl9xqJ55lQtNcTrA5WphIn8SSsEZinEK0%2F%0AThG7hZN7u2V%2FUODY2nk2yQpo2TU%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1478478162/40e3ce1a50c941787862d33a9ad5/image.png?expires=1751479200\&signature=44a58d731721d79fcfb6ef23ae6752e8c1fed472ffbc7ffafaba203910c7f533\&req=dSQgHs15lYBZW%2FMW3nq%2BgZErAy%2Bl9xqJ55lQtNcTrA5WphIn8SSsEZinEK0%2F%0AThG7hZN7u2V%2FUODY2nk2yQpo2TU%3D%0A)

Do you also use an exchange? Learn how to import transactions from Coinbase, Binance, and other exchanges [here](https://help.accounting.request.finance/en/articles/10363916-how-to-import-transactions-from-your-exchanges).

### Bulk Wallet Import <a href="#h_c85e5d187d" id="h_c85e5d187d"></a>

If you have multiple wallets to connect, you can upload them in bulk using a CSV file.

1. Navigate to the [Wallets](https://accounting.request.finance/tracking) menu
2.  Click on Import CSV

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1478488407/ca5a1c9dc1ff4acdc6c0a52aa8e1/image.png?expires=1751479200\&signature=970bce0a52ee6552c005a9417ca09a08b22952d666c5ed7c97f0d509d1a8ffb9\&req=dSQgHs12lYVfXvMW3nq%2BgTAQ1HRgzlwDh3zzsjE382ahScRnhyooaUBc%2F43g%0AkrVs1IHzF5l%2FGOJToy18zj%2F33nI%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1478488407/ca5a1c9dc1ff4acdc6c0a52aa8e1/image.png?expires=1751479200\&signature=970bce0a52ee6552c005a9417ca09a08b22952d666c5ed7c97f0d509d1a8ffb9\&req=dSQgHs12lYVfXvMW3nq%2BgTAQ1HRgzlwDh3zzsjE382ahScRnhyooaUBc%2F43g%0AkrVs1IHzF5l%2FGOJToy18zj%2F33nI%3D%0A)
3. Download our [template](https://accounting-staging.request.finance/templates/wallet_upload_template.csv) and follow the guidelines mentioned below. Request Accounting will import all the wallet addresses included in the CSV. Duplicates will be ignored.

#### CSV File Format Guidelines <a href="#h_7975a754c8" id="h_7975a754c8"></a>

| Field Name | Description                               |
| ---------- | ----------------------------------------- |
| Name       | The name you want to assign to the wallet |
| Address    | The wallet's public address               |
| Chain      | The blockchain network(s) for the wallet  |

| Supported Networks | Sample Wallet Address                                                                                   |
| ------------------ | ------------------------------------------------------------------------------------------------------- |
| Ethereum           | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Polygon            | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Optimism           | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Solana             | EDMrdg3BQMR7rV7mFAT9d7s18hYQYBnZffqmeejVyqTT                                                            |
| Binance            | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Arbitrum           | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Aptos              | 0x376a55fed6af595e73fbbc8df98f3ff864be7ec7f231d34c8877ac406c6f3069                                      |
| Avalanche          | 0x15f888485c53bf5c5C1eA567E7b489102382075f                                                              |
| Base               | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| Bitcoin            | bc1q834uh3rc4jfh66pn926yn948x6xpgm2fhq2rnd                                                              |
| BCH                | qre24q38ghy6k3pegpyvtxahu8q8hqmxmqqn28z85p                                                              |
| Cardano            | addr1qycnnp74xjeegxlhpkks6s03dnlmslcyjvuj5wsx7wmlu9dqx2gjcseqwna4w90kg9kye9z4tawf92e66va3guzf0m7svx09r6 |
| Casper             | 014c296e225e121312122a019d38771e65cfceb7ca9c6998556580ea5ceb0b422c                                      |
| Cosmos             | cosmos1x9emewggduxdrkl5e0c8wd8h45rw6894x4kk8n                                                           |
| Ecredits           | 0x6E8298B4e8cda343c267e633f6a85e7fC1295b2b                                                              |
| Fantom             | 0xD5b6408FB85dA01ee6beAA3aB4Fb2993371EdE77                                                              |
| Gnosis chain       | 0x12E2B6c70c4bc56027Ef7E8eCd050008af7237a4                                                              |
| ICP                | ad8005ed1e0c21cdbb1a0208b9719d944aaecb5f13b4318189ca448f46c4b957                                        |
| Injective          | inj18vqwnf2uufw2k3sv43c7eskup7k5k33uat5lpj                                                              |
| Litecoin           | ltc1qyqxttxapzr5jlw48wlwpvvp590ujttkds8j4p5                                                             |
| Moonriver          | 0x35FcB4870a6489B9E367ded027e9E99a10397619                                                              |
| Osmosis            | osmo1c9ye54e3pzwm3e0zpdlel6pnavrj9qqvwhqw4z                                                             |
| Ronin              | 0x90ead0e8d5f5bf5658a2e6db04535679df0f8e43                                                              |
| Provenance         | pb1crecuxdshhqzj90ystksv02mmccqtqyhw4vp6a                                                               |
| Stellar            | GAHFXHIGRUDWPXCUVRX4UB4RI3VCIWODINB743XFRR27H5EBNH73BBNI                                                |
| Tezos              | tz1RCRagJ7DXuXirqmoaPpdekNX7o94oSke3                                                                    |
| Tron               | TLfeRw8aKuBK9eXKAzk7cAhrThhYbdkPiT                                                                      |
| Vara               | kGh8rKzpfZpmH7oDp7Zk1Qd3jnFeVpUtDUUgEe6xtAWC8tkJ3                                                       |
| Ripple             | rBTwLga3i2gz3doX6Gva3MgEV8ZCD8jjah                                                                      |
