## Introductions 👋

Hi there, welcome to my page. 

I'm ZanyBonzy. A highly skilled and knowledgeable Security Researcher with a proven track record of conducting in-depth research, identifying vulnerabilities, and implementing solutions to enhance smart contract security. With over 80 confirmed high and medium severity vulnerabilities in public & private contests, and countless lows, be rest assured that no codebase is too difficult for me to break, except the ones I don't audit.
Organizations I've worked with include Code4rena, Sherlock Audits, CodeHawks, Pashov Audit Group, Cantina, Secure3, Immunefi etc.

## Stack 👨‍💻

I audit contracts written in solidity or vyper for EVM based chains. I also work on rust based smart contracts for Substrate, Cosmowasm and Solana based systems. For starknet based contracts, I have a good knowledge of cairo.

## Bug Highlights 🏆

1. [Balance doubling bug](https://github.com/code-423n4/2024-03-acala-findings/issues/16) in Acala's ORML rewards library.
  
  > Users could transfer their shares to themselves and effectively double their balance;

2. Griefing [attack](https://github.com/code-423n4/2024-07-traitforge-findings/issues/227) on users' minting rewards in TraitForge's NFT.
  
  > Seller's airdrop benefits could be maliciously reduced by malicious buyers for little or no cost.

3. Permanent [bricking](https://github.com/code-423n4/2024-05-olas-findings/issues/78) of Olas's VoteWeighting contract.

  > The contract's Curve type slope calculation was not correctly updated when removing a nominee

4. Swapping calculation [breakage](https://github.com/code-423n4/2024-07-basin-findings/issues/17) in Basin's Stable2 contract.
	
 > Token decimal was incorrectly decoded while processing swap data which coul potentially cause overestimation or underestimation of prices. In some cases, dependent functions are denied of servive.

5. Permanent, irreversible [loss](https://github.com/pashov/audits/blob/master/team/md/Lucidly-security-review-June.md#c-01-fees-will-always-be-sent-to-address0) of protocol fees in Lucidly's staking contract.
	
 > Fee address was not set in the constructor, and there was no corresponding function to set the address.

6. Pool token cool-off period [bypass](https://github.com/pashov/audits/blob/master/team/md/Nabla-security-review.md#h-01-cool-off-period-for-deposits-in-swap-pools-can-be-bypassed) in Nabla's SwapPool contract. 
	
 > Pool tokens minted to users upon deposit could be transferred to another address to instantly redeem.

7. Reward distribution [dilution](https://github.com/code-423n4/2024-02-althea-liquid-infrastructure-findings/issues/61) due to flawed distribution model.

 > Disapproved users' tokens are factored into rewards calculation, unfairly reducing that of other users.

8. ETH [lost](
https://cantina.xyz/code/ac757733-81a4-43c7-8f49-17c5b135cdff/findings/540) during migration of Curvance's FeeAccumulator contract.

 > The contract had no way of retrieving ETH, neither were ETH transfered to the new implementation during migration.

9. Permanent [DOS](https://github.com/code-423n4/2024-04-noya-findings/issues/961) of withdrawals by a poisonous address

 > Withdrawals were processed in a batches in a loop, so a malicious user could create a withdrawal request with an address that is blocked from receiving the underlying token. As far as the token can't be sent to the address, the withdrawal process will always fail, locking up funds. 
 


Would like to view more?  Feel free to check my main contest pages.

- [Code4rena](https://code4rena.com/@ZanyBonzy)
- [Sherlock](https://audits.sherlock.xyz/watson/ZanyBonzy)
- [CodeHawks](https://profiles.cyfrin.io/u/zanybonzy)
- [Cantina](https://cantina.xyz/u/ZanyBonzy)

Perharps my pseudoaccount might interest you (mostly for judging);

- [Code4rena](https://code4rena.com/@inh3l)
- [CodeHawks](https://profiles.cyfrin.io/u/inh3l) 

#### Contact me (in order of relevance) ☎️
- Discord: @zanybonzy
- Telegram: @drugoiguy
- Email: ZanyBonzy@proton.me
- [Twitter](http://twitter.com/zanybonzy)
- [Github](https://github.com/zanybonzy)
