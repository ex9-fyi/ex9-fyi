Hi! I currently work as an EVM auditor and developer. Happy to connect and my DM's open on [Twitter](https://twitter.com/exponential__).

# Experiences

## 2022-Presetn, EVM dapp auditing

### Summary

* Audited for Maker, Sommelier, TreasureDAO, Vyper and other reputable teams.
* Worked with 0xmacro.com and independently.

### Selected audits

* Maker-1: Dollar Cost Average contracts, **1 medium**
  * https://0xmacro.com/library/audits/maker-1
  * Volatility anaylsis and mitigation https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925
 
* Vyper compiler audit ([public issues](https://github.com/vyperlang/vyper/issues?q=is%3Aissue+is%3Aclosed+author%3Aexp7l))
   
* Sommelier-3: Cellar contracts, **10MM+ TVL, 3 high, 9 medium**
  * https://0xmacro.com/library/audits/sommelier-3
  
* Sommelier-4: Cellar contracts and Defi protocol integrations, **5 high, 8 medium**
  * https://0xmacro.com/library/audits/sommelier-4
  
* Sommelier-5: Euler integration contracts, **2 high**
  * https://0xmacro.com/library/audits/sommelier-5
  
* Thirdweb-6: Marketplace contracts, **4 critical, 1 high, 1 medium**
  * https://0xmacro.com/library/audits/thirdweb-6
 
* Based Market Trade to Earn
  * https://github.com/exp7l/docs/blob/main/based-market-trade-to-earn.pdf

* 0xMacro private audits:
  * TreasureDAO ([MagicSwap](https://treasuredao.substack.com/p/magicswap-the-first-amm-with-universal))
  * Frax
  * Zion (audit and design consultation)

## 2022-Present, free and open source contributions



### 1. Contributions to [Dark.fi](https://dark.fi/)

#### a. Zkrunner

* To accelerate Darkfi ZK script developer's iteration speed, Darkfi needed a tool to generate a ZK proof's public inputs based on witnesses, and a way to quickly prove and verify with a Darkfi ZK circuit.
* I contributed the Python bindings ([1](https://github.com/darkrenaissance/darkfi/pull/178/files),[2](https://github.com/darkrenaissance/darkfi/pull/179/files#diff-d5cf2236d11e91914a46216982f099c86adcc6e426647a4a07580414c9aa6f99)) for Darkfi's SDK
  * With others' contributions, it led to [this demo](https://github.com/darkrenaissance/darkfi/pull/178/files).

#### b. Runtime parameters for Darkfi ZK circuit

* This is a proof of concept to take Etheruem Foundation Privacy Exploration and Scaling Group's [work on their Halo2 fork](https://github.com/privacy-scaling-explorations/halo2/pull/168) to [apply to Darkfi's Halo2 fork](https://github.com/parazyd/halo2/pull/2).
* The idea is to allow Darkfi ZK circuit developer to accept additional arguments at runtime to configure their circuit.
 
### 2. Emap, a minimal onchain name service

* A fork of [DappHub's Dmap](https://github.com/dapphub/dmap/tree/master/core) which is optimized to be as minimal as possible in implementation.
* It is a name service that supports forward name resolution (going from name to resources) and backward name resolution (going from resources to name) **in less than 200 lines of code** in order to maximize auditability and security.

## 2019-2022, Software engineer, Amazon

- Led and shipped automation for legal info collection and investigation
resulted in $2MM saving in operational cost per year.
- Led and shipped search keyword recommendations, for amazon.com detail
page. Showed $10+MM per year profitability lift in pilot.

