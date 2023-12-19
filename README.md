Hi! I currently work as an EVM auditor and developer.

# Developement experiences

* Emap, a minimal onchain name service: https://github.com/exp7l/emap
* Contributions to [Dark.fi](https://dark.fi/):
    * Taken from PSE's Halo2 fork to make `configure` take "dynamic parameters" https://github.com/parazyd/halo2/pull/2
    ```
        fn configure_with_params(
            meta: &mut ConstraintSystem<pallas::Base>,
            params: Self::Params,
        ) -> Self::Config {...}
    ```
    * other [pull requests](https://github.com/darkrenaissance/darkfi/pulls?q=author%3Afreeranged3v+)
* Prior backend dev experience at FAANG

# Audit Portfolio

* Found vulnerabilities and developed exploits for defi apps, including high severity vulnerabilities for a system with $10+MM value locked.
* Audited for Maker, Sommelier, TreasureDAO, Vyper and other reputable teams.
* Worked with 0xmacro.com and independently.

## Some Selected Audits

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
