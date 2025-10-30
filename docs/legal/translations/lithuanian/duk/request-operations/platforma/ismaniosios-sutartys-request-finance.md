---
description: Išmaniųjų sutarčių, naudojamų mokėjimams per "Request Finance", sąrašas
---

# Išmaniosios sutartys "Request Finance"

Išmaniosios sutartys užtikrina "Request" mokėjimų programos veikimą. Jos didina efektyvumą palaikydamos automatinį suderinimą, grupinius mokėjimus (kelių operacijų tvarkymą vienu procesu) ir mokėjimus su valiutos konvertavimu (pavyzdžiui, sąskaitos JAV doleriais apmokėjimas kriptovaliuta), taip sumažindamos laiko sąnaudas ir klaidų riziką. Visos išmaniosios sutartys yra viešai prieinamos "GitHub" [čia.](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts)

Toliau pateiktas sąrašas nėra išsamus [visų "Request" palaikomų tinklų](https://help.request.finance/en/articles/8650043-supported-currencies-and-networks#h_b27c6064d6) sąrašas, nes kai kurie tinklai ar veiksmai veikia be išmaniųjų sutarčių.

Jei pastebėjote skirtumą tarp mokėjimo adreso savo piniginėje ir mokėjimo adreso, nurodyto mokamoje vietoje, pasinaudokite toliau pateikta lentele, kad patvirtintumėte teisingą adresą.

Niekada nesiųskite lėšų tiesiogiai išmaniosioms sutartims, nes jos bus prarastos. Išmaniąsias sutartis naudokite tik per "Request Finance" (app.request.finance).

## Tradicine valiuta išreikštų mokėtinų ERC-20 žetonų mokėjimas <a href="#h_eaec46181f" id="h_eaec46181f"></a>

Toliau pateiktos sutartys naudojamos mokant tradicine valiuta išreikštą mokėtiną sumą ERC20 žetonu (pvz., apmokant USD nominalo sąskaitą USDC).

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0xA5186dec7dC1ec85B42A3cd2Dc8289e248530B07 |
| Avalanche    | 0xA5186dec7dC1ec85B42A3cd2Dc8289e248530B07 |
| Bazinis      | 0x8296D56321cf207925a7804E5A8E3F579838e6Ad |
| BNB grandinė | 0xbbd9c5D112343A4Aa2bc194245760CaeeaF118Be |
| Celo         | 0xf0f49873C50765239F6f9534Ba13c4fe16eD5f2E |
| Core         | _Naudoja ERC20FeeProxy_                    |
| Ethereum     | 0xe72Ecea44b6d8B2b3cf5171214D9730E86213cA2 |
| Fantom       | 0xf0f49873C50765239F6f9534Ba13c4fe16eD5f2E |
| Saugiklis    | _Naudoja ERC20FeeProxy_                    |
| GnosisChain  | 0xf0f49873C50765239F6f9534Ba13c4fe16eD5f2E |
| Moonbeam     | 0x1550A8C4F4E5afC67Ea07e8ac590fdcAdB4bBfb1 |
| Optimizmas   | 0x1550A8C4F4E5afC67Ea07e8ac590fdcAdB4bBfb1 |
| Poligonas    | 0xf0f49873C50765239F6f9534Ba13c4fe16eD5f2E |
| Sonic        | 0xe43fd55Da253628Ed7Cad5ab198664F5B3659DA9 |
| zkSync Era   | _Naudoja ERC20FeeProxy_                    |

GitHub nuoroda: [ERC20ConversionProxy](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/Erc20ConversionProxy)

## ERC20 žetonu išreikštų mokėtinų sumų mokėjimas ERC20 žetonu <a href="#h_66609bda28" id="h_66609bda28"></a>

Toliau pateiktos sutartys naudojamos mokant ERC20 žetonu denominuotą mokėtiną sumą ERC20 žetonu (pvz., mokant USDC denominuotą vekselį USDC).

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Avalanche    | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Bazinis      | 0x1892196E80C4c17ea5100Da765Ab48c1fE2Fb814 |
| BNB grandinė | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Celo         | 0x2171a0dc12a9E5b1659feF2BB20E54c84Fa7dB0C |
| Core         | 0x399F5EE127ce7432E4921a61b8CF52b0af52cbfE |
| Ethereum     | 0x370DE27fdb7D1Ff1e1BaA7D11c5820a324Cf623C |
| Fantom       | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Saugiklis    | 0xee07ef5B414955188d2A9fF50bdCE784A49031Fc |
| GnosisChain  | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Moonbeam     | 0x399F5EE127ce7432E4921a61b8CF52b0af52cbfE |
| Optimizmas   | 0x399F5EE127ce7432E4921a61b8CF52b0af52cbfE |
| Poligonas    | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Sonic        | 0x1892196E80C4c17ea5100Da765Ab48c1fE2Fb814 |
| zkSync Era   | 0x6e28Cc56C2E64c9250f39Cb134686C87dB196532 |

GitHub nuoroda: [ERC20FeeProxy](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/ERC20FeeProxy)

## Tradicine valiuta denominuotos mokėtinos sumos mokėjimas vietine valiuta <a href="#h_b0afec0b76" id="h_b0afec0b76"></a>

Toliau pateiktos sutartys naudojamos mokant tradicine valiuta išreikštą mokėtiną sumą vietine valiuta (pvz., mokant ETH ETH išreikštą sąskaitą Ethereum).

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Avalanche    | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Bazinis      | 0xEdfD8386d5DE52072B4Ad8dC69BBD0bB89f9A1fb |
| BNB grandinė | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Celo         | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Core         | _Naudoja ERC20FeeProxy_                    |
| Ethereum     | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Fantom       | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Saugiklis    | _Naudoja ERC20FeeProxy_                    |
| GnosisChain  | _Naudoja ERC20FeeProxy_                    |
| Moonbeam     | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Optimizmas   | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Poligonas    | 0x7Ebf48a26253810629C191b56C3212Fd0D211c26 |
| Sonic        | 0x3E3B04e1bF170522a5c5DDE628C4d365c0342239 |
| zkSync Era   | _Naudoja ERC20FeeProxy_                    |

GitHub nuoroda: [EthConversionProxy](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/EthConversionProxy)

## Gimtąja valiuta išreikšto mokėtino mokėjimo vietine valiuta mokėjimas <a href="#h_0e8e6f8411" id="h_0e8e6f8411"></a>

Toliau pateiktos sutartys naudojamos mokant gimtąja valiuta denominuotą mokėtiną sumą gimtąja valiuta (pvz., mokant ETH denominuotą sąskaitą ETH Ethereum).

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Avalanche    | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Bazinis      | 0xd9C3889eB8DA6ce449bfFE3cd194d08A436e96f2 |
| BNB grandinė | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Celo         | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Core         | 0xe11BF2fDA23bF0A98365e1A4c04A87C9339e8687 |
| Ethereum     | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Fantom       | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Saugiklis    | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| GnosisChain  | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| Moonbeam     | 0xe11BF2fDA23bF0A98365e1A4c04A87C9339e8687 |
| Optimizmas   | 0xe11BF2fDA23bF0A98365e1A4c04A87C9339e8687 |
| Sonic        | 0xd9C3889eB8DA6ce449bfFE3cd194d08A436e96f2 |
| Poligonas    | 0xfCFBcfc4f5A421089e3Df45455F7f4985FE2D6a8 |
| zkSync Era   | 0xE9A708db0D30409e39810C44cA240fd15cdA9b1a |

GitHub nuoroda: [EthereumFeeProxy](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/EthereumFeeProxy)

## Grupinių mokėjimų atlikimas <a href="#h_4eae7baad1" id="h_4eae7baad1"></a>

Toliau pateiktos sutartys naudojamos grupiniams mokėjimams (kelių mokėjimų atlikimui vienu kartu).

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Avalanche    | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Bazinis      | 0x1aF3f22685AcdDc788B3730ed415912d8f654420 |
| BNB grandinė | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Celo         | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Core         | 0x02561967c48e87cfB079763F3BEf6424A5A166A7 |
| Ethereum     | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Fantom       | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Saugiklis    | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| GnosisChain  | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Moonbeam     | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Optimizmas   | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Poligonas    | 0x3cF63891928B8CeebB81C95426600a18cd59C03f |
| Sonic        | 0x02561967c48e87cfB079763F3BEf6424A5A166A7 |
| Tron         | TX3TwEQYhqaEB6765KH7gP4y7MdRnzp28V         |
| zkSync Era   | 0x0C41700ee1B363DB2ebC1a985f65cAf6eC4b1023 |

GitHub nuoroda: [BatchConversionPayments](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/BatchConversionPayments)

## Kriptografinių mokėjimų į tradicine valiuta mokėjimus atlikimas <a href="#h_63492a82e2" id="h_63492a82e2"></a>

Atliekant [Crypto-to-Fiat mokėjimą](https://help.request.finance/en/articles/9550480-crypto-to-fiat-overview) naudojamos toliau nurodytos sutartys. [Čia](https://help.request.finance/en/articles/8607154-supported-currencies-and-payment-routes-for-crypto-to-fiat#h_e0ae685874) išvardyti visi tinklai ir valiutos, palaikomi Crypto-to-Fiat.

| Tinklas      | Išmaniosios sutarties adresas              |
| ------------ | ------------------------------------------ |
| Arbitrum One | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Ethereum     | 0x370DE27fdb7D1Ff1e1BaA7D11c5820a324Cf623C |
| Poligonas    | 0x0DfbEe143b42B41eFC5A6F87bFD1fFC78c2f0aC9 |
| Solana       | -                                          |
| Tron         | -                                          |

GitHub nuoroda: [ERC20FeeProxy](https://github.com/RequestNetwork/requestNetwork/tree/master/packages/smart-contracts/src/lib/artifacts/ERC20FeeProxy)
