# Auditing @ 0xmacro.com

Great team, good people. Clients: Maker, Sommelier, TreasureDAO, Vyper and others

**1. [Maker](https://makerdao.com/en/)**

* Audited the first version of Smart Burn Engine
* [Audit report](https://0xmacro.com/library/audits/maker-1) and [statisitical assumption check report](https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925)
  
**2. [Sommelier](https://www.sommelier.finance/)**

* $60MM TVL at one point
* [Cellar contracts; 3 high, 9 medium, 4 low](https://0xmacro.com/library/audits/sommelier-3).
* [Cellar contracts and defi protocol integrations; 5 high, 8 medium, 2 low](https://0xmacro.com/library/audits/sommelier-4).
* [Euler integration contracts; 2 high](https://0xmacro.com/library/audits/sommelier-5).

**3. [Thirdweb](https://thirdweb.com/)**

* [4 critical, 1 high, 1 medium](https://0xmacro.com/library/audits/thirdweb-6).

## Open source

**[Dark.fi](https://dark.fi/)**; Hardcore peeps

**Zkrunner**
* To accelerate Darkfi ZK script developer's iteration speed, Darkfi needed a tool to generate a ZK proof's public inputs based on input witnesses, and a way to quickly prove and verify with a Darkfi ZK circuit.
* I contributed the Python bindings ([1](https://github.com/darkrenaissance/darkfi/pull/178),[2](https://github.com/darkrenaissance/darkfi/pull/179)) for Darkfi's SDK
  * With others' contributions, it led to [this demo on Twitter](https://twitter.com/parazyd/status/1690776743756402688).

**Halo2 hack**
* POC This is a proof of concept to take Etheruem Foundation's Privacy Exploration and Scaling Group's [work on their Halo2 fork](https://github.com/privacy-scaling-explorations/halo2/pull/168) to [apply to Darkfi's Halo2 fork](https://github.com/parazyd/halo2/pull/2).
* The purpose is to allow Darkfi ZK circuit developer to accept additional arguments at runtime to configure their circuit.
 
**Emap, minimal name service**
* It is a name service that supports forward name resolution (going from name to resources) and backward name resolution (going from resources to name) **in less than 200 lines of code** in order to maximize auditability and security.
* A fork of [DappHub's Dmap](https://github.com/dapphub/dmap) which is optimized to be as minimal as possible in implementation.

## Clojure backend dev

It's great. You should try it.

