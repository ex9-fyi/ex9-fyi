Hi! I am interested in EVM security and Defi applications. DM's open! 

---

Beside finding critical and high severity issues, I take pride in providing a thorough anaylsis of the vulnerabilities and mitigations, so the client is supported in finding a long term fix rather quick & dirty workaround. I will use Maker as an example.

## Maker

So Maker wanted to buy back their governance tokens, MKR. **But had challenge in their contract design to balance between 1) making the execution permissionless and 2) avoiding being arbitrage**. If the purchase were permissioned, arbitrages by malicious traders would be impossible.

We statisically quantified the arbitrage risk with 3 months of market price data and [provided 3 detailed mitigations that satisfy their requirement of being permissionless](https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925).

Without going into the detail here, here is their response at the end: **"Nice idea! I think this is certainly a measure to consider we see many sandwich attacks"**.

## Audits

Here are the public reports, and list of the private audits.

* Maker-1: Dollar Cost Average contracts, **1 medium**
  * https://0xmacro.com/library/audits/maker-1
  * Volatility anaylsis and mitigation https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925
  
* Sommelier-3: Cellar contracts, **10MM+ TVL, 3 high, 9 medium**
  * https://0xmacro.com/library/audits/sommelier-3
  
* Sommelier-4: Cellar contracts and Defi protocol integrations, **5 high, 8 medium**
  * https://0xmacro.com/library/audits/sommelier-4
  
* Sommelier-5: Euler integration contracts, **2 high**
  * https://0xmacro.com/library/audits/sommelier-5
  
* Thirdweb-6: Marketplace contracts, **4 critical, 1 high, 1 medium**
  * https://0xmacro.com/library/audits/thirdweb-6

* 0xMacro private audits: TreasureDAO, Frax, Zion (audit and design consultation)

## Design Support

I previously worked on full stack engineering for 2 years, where we valued highly the design and lowering the complexity of the system.  So I would be happy to go into detail on your design, especially around making the system more auditable but satisfying the important requirements. 
