Working on https://twitter.com/ether_log

# Experiences

## 2022-Present, smart contract security engineer

* Audited for Maker, Sommelier, TreasureDAO, Vyper and other reputable teams.

### Selected audits

#### 1. [Maker](https://makerdao.com/en/)

* Audited their Kiln contracts, which are used to buy back Maker's MKR tokens and burn.
* Vulnerabilities found by team and I: 1 medium, 1 low, 2 quality, 2 informational.
* Provided both [audit report](https://0xmacro.com/library/audits/maker-1) and [statisitical assumption check report](https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925).
  
#### 2. [Sommelier](https://www.sommelier.finance/) (their EVM contracts)

* Defi protocol in the Cosmos ecosystem: they offer vaults where a strageist rebalances the vault's portfolio after the strategist's trades are validated in the Sommelier blockchain and by their Ethereum contracts' rules.
* Currently has $60MM TVL.
* Report and vulnerabilities found by team and I:
  * [Cellar contracts; 3 high, 9 medium, 4 low](https://0xmacro.com/library/audits/sommelier-3).
  * [Cellar contracts and defi protocol integrations; 5 high, 8 medium, 2 low](https://0xmacro.com/library/audits/sommelier-4).
  * [Euler integration contracts; 2 high](https://0xmacro.com/library/audits/sommelier-5).

#### 3. [Thirdweb](https://thirdweb.com/)

* [Marketplace contracts report by team and I; 4 critical, 1 high, 1 medium](https://0xmacro.com/library/audits/thirdweb-6).

#### 4. Others:
  * [TreasureDAO](https://treasure.lol/) ([MagicSwap](https://treasuredao.substack.com/p/magicswap-the-first-amm-with-universal)).
  * [Frax](https://frax.finance/).
  * Zion (audit and design consultation).
  * [Vyper compiler](https://docs.vyperlang.org/en/stable/)
      * Acknowledged by Vyper team, [redundant Keccak256 implementations](https://github.com/vyperlang/vyper/issues/3649).
      * Misc: https://github.com/vyperlang/vyper/issues?q=is%3Aissue+is%3Aclosed+author%3Aexp7l
  * [Based Market](https://www.based.markets/)'s Trade to Earn program
      * [Solo audit; 1 ciritcal and 2 medium](https://github.com/exp7l/docs/blob/main/based-market-trade-to-earn.pdf).

## 2022-Present, free and open source contributions

### 1. Contributions to [Dark.fi](https://dark.fi/)

#### a. Zkrunner

* To accelerate Darkfi ZK script developer's iteration speed, Darkfi needed a tool to generate a ZK proof's public inputs based on input witnesses, and a way to quickly prove and verify with a Darkfi ZK circuit.
* I contributed the Python bindings ([1](https://github.com/darkrenaissance/darkfi/pull/178),[2](https://github.com/darkrenaissance/darkfi/pull/179)) for Darkfi's SDK
  * With others' contributions, it led to [this demo on Twitter](https://twitter.com/parazyd/status/1690776743756402688).

#### b. Proof of concept to enable runtime parameters

* This is a proof of concept to take Etheruem Foundation's Privacy Exploration and Scaling Group's [work on their Halo2 fork](https://github.com/privacy-scaling-explorations/halo2/pull/168) to [apply to Darkfi's Halo2 fork](https://github.com/parazyd/halo2/pull/2).
* The purpose is to allow Darkfi ZK circuit developer to accept additional arguments at runtime to configure their circuit.
 
### 2. Emap, minimal name service on EVM

* It is a name service that supports forward name resolution (going from name to resources) and backward name resolution (going from resources to name) **in less than 200 lines of code** in order to maximize auditability and security.
* A fork of [DappHub's Dmap](https://github.com/dapphub/dmap) which is optimized to be as minimal as possible in implementation.

## 2019-2022, Software engineer, Amazon

- Led and shipped automation for legal info collection and investigation resulted in $2MM saving in operational cost per year.
- Led and shipped search keyword recommendations, for amazon.com detail page. Showed $10MM+ per year profitability lift in pilot.

