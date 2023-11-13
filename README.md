* Themes I believe to be under-explored in blockchain contracts:
  * Security by simplification through DSLs ([example from the STEPS](https://tinlizzie.org/VPRIPapers/tr2012001_steps.pdf))
  * Security by isolation ([example from QubesOS](https://t.co/DuWNrTnv76))
 * I am currently working in private audits, contests and bounties, with the goal of turning learning into tools that make contracts more secure. DM's open

# Audit Portfolio

Beside finding critical and high severity issues, I take pride in thorough anaylsis of the vulnerabilities and mitigations, so you're supported in finding a long term fix rather quick & dirty workaround. I will use Maker as an example.

So Maker wanted to buy back their governance tokens, MKR. **But had challenge in their contract design to balance between 1) making the execution permissionless and 2) avoiding being arbitrage**. If the purchase were permissioned, arbitrages by malicious traders would be impossible. We statisically quantified the arbitrage risk with 3 months of market price data and [provided 3 detailed mitigations that satisfy their requirement of being permissionless](https://0xmacro.notion.site/MakerDAO-1-TWAP-Lag-and-Arbitrage-Loss-5ee753d73d4f49dda61c4d566e99f925). I'm confident we added value, here is their response at the end: **"Nice idea! I think this is certainly a measure to consider we see many sandwich attacks"**.

## Audits

Some selected audits:

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

* Based Market Trade to Earn

* Vyper compiler audit ([public issues](https://github.com/vyperlang/vyper/issues?q=is%3Aissue+is%3Aclosed+author%3Aexp7l))

## Design Support & Prior Experience

I previously worked on backend in a FAANG. Our team higly valued design and managing complexity. I'd be happy to provide consultation on your design especially around auditability front. 
