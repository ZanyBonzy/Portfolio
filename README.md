## Introductions 👋

Hi there, welcome to my page. 

I'm ZanyBonzy. A highly skilled and knowledgeable Security Researcher with a proven track record of conducting in-depth research, identifying vulnerabilities, and implementing solutions to enhance smart contract security. With over 80 confirmed high and medium severity vulnerabilities in public & private contests, and countless lows, be rest assured that no codebase is too difficult for me to break, except the ones I don't audit.
Organizations I've worked with include Code4rena, Sherlock Audits, CodeHawks, Pashov Audit Group, Cantina, Secure3, Immunefi etc.

## Stack 👨‍💻

I audit contracts written in solidity or vyper for EVM based chains. I also work on rust based smart contracts for Substrate, Cosmowasm and Solana based systems. For starknet based contracts, I have a good knowledge of cairo.

## Highlights 🏆

1. [Balance doubling bug](https://github.com/code-423n4/2024-03-acala-findings/issues/16) in Acala's ORML rewards library.
  
  > Users can transfer their shares to themselves and effectively double their token balance;

2. Griefing [attack](https://github.com/code-423n4/2024-07-traitforge-findings/issues/227) on users' minting rewards in TraitForge's NFT.
  
  > Seller's airdrop benefits can be maliciously reduced by malicious buyers for little or no cost.

3. Permanent [bricking](https://github.com/code-423n4/2024-05-olas-findings/issues/78) of Olas protocol's VoteWeighting contract.

  > The contract's Curve type slope calculation was not correctly updated when removing a nominee

4. Swapping calculation [breakage](https://github.com/code-423n4/2024-07-basin-findings/issues/17) in Basin's Stable2 contract.
	
 > Token decimal was incorrectly decoded while processing swap data which coul potentially cause overestimation or underestimation of prices. In some cases, dependent functions are denied of servive.

5. Permanent, irreversible [loss](https://solodit.xyz/issues/c-01-fees-will-always-be-sent-to-address0-pashov-audit-group-none-lucidly-june-markdown) of protocol fees in Lucidly's staking contract.
	
 > Fee address was not set in the constructor, and there was no corresponding function to set the address.

6. Pool token cool-off period [bypass](https://solodit.xyz/issues/h-01-cool-off-period-for-deposits-in-swap-pools-can-be-bypassed-pashov-audit-group-none-nabla-markdown) in Nabla's SwapPool contract. 
	
 > Pool tokens minted to users upon deposit could be transferred to another address to instantly redeem.

Would like to view more?  Feel free to check my main contest pages.

- [Code4rena](https://code4rena.com/@ZanyBonzy)
- [Sherlock](https://audits.sherlock.xyz/watson/ZanyBonzy)
- [CodeHawks](https://codehawks.cyfrin.io/profile/clk9uu45r0000js08lnm9zbez)
- [Cantina](https://cantina.xyz/u/ZanyBonzy)

Perharps my pseudoaccount might interest you (mostly for judging);

- [Code4rena](https://code4rena.com/@inh3l)
- [CodeHawks](https://codehawks.cyfrin.io/profile/cluz81f0t0000tt2dk8pq7hzz)

#### Contact me (in order of relevance) ☎️
- Discord: @zanybonzy
- Telegram: @drugoiguy
- [Twitter](http://twitter.com/zanybonzy)
- [Github](https://github.com/zanybonzy)
