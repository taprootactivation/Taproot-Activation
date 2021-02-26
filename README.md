## Taproot is a proposed Bitcoin protocol upgrade that can be deployed as a forward-compatible soft fork. By combining the Schnorr signature scheme with MAST ([Merklized Alternative Script Tree](https://bitcoin.stackexchange.com/questions/99539/what-are-merklized-alternative-script-trees)) and a new scripting language called Tapscript, Taproot will expand Bitcoin’s smart contract flexibility, while offering more privacy by letting users mask complex smart contracts as a regular bitcoin transaction.
More information can be found in this Bitcoin Magazine article by Aaron van Wirdum: [Taproot Is Coming: What It Is, And How It Will Benefit Bitcoin](https://bitcoinmagazine.com/articles/taproot-coming-what-it-and-how-it-will-benefit-bitcoin)

------

A soft fork is a change to the Bitcoin protocol wherein only previously valid blocks/transactions are made invalid. Since old nodes recognize the new blocks as valid, a soft fork is forward-compatible. See more here: [Soft fork bitcoin wiki](https://en.bitcoin.it/wiki/Softfork) 

Soft forks can be activated in several ways. Multiple of the previous soft forks were activated using [BIP9](https://en.bitcoin.it/wiki/BIP_0009), which required a supermajority of hash power to signal support for the upgrade. [BIP8](https://en.bitcoin.it/wiki/BIP_0008) is the successor of BIP9. BIP8 gives the option to activate the upgrade at the end of the signaling period even without a supermajority of miners signaling support. In the listed activation proposals below, the 'true' or 'false' indicates whether a signal period would end in activation. BIP9 worked equivalently to BIP8 without activation at the end.

## Proposal overview

![proposal overview](https://en.bitcoin.it/w/images/en/1/19/Activation-timeline.png)

More in-depth information on [Taproot activation proposals](https://en.bitcoin.it/wiki/Taproot_activation_proposals) can be found in the Bitcoin Wiki.

**The aim of this site is to assist in the activation of the Taproot soft fork. We have reached out to several Bitcoin mining pools to find out if:**

1. If they support the Taproot upgrade
1. If so, which activation method they prefer
1. If they want to insert a coinbase message in a block to announce their preference (even before the actual activation window opens)

Note: TBD = To be decided

------

 Mining Pool |   Taproot?     |  Activation | Coinbase Signal | Proof of Support | [Global Hashrate % (1 month](https://btc.com/stats/pool?pool_mode=month) | LOT = TRUE or FALSE
------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
[Poolin](https://poolin.com) | Yes | BIP9 equivalent, BIP8(false, 1y) | [taproot/bip9](https://explorer.poolin.com/block/0000000000000000000698859d225da3129461173d6a9c07b2849edc9da0a12d) | [Tweet](https://twitter.com/officialpoolin/status/1329021070918230017) | 12.60 %	| LOT = FALSE |
Slush Pool | Yes | BIP8 |  | [Tweet](https://twitter.com/slush_pool/status/1329051461100204032) | 3.37 %	| |
BTC.com | Yes | Modern Soft Fork Activation | TBD | [Github](https://github.com/taprootactivation/Taproot-Activation/issues/10) | 11.16 %	| |
F2Pool | Yes | BIP8(false, 1y) | No | [Pull Request](https://github.com/taprootactivation/Taproot-Activation/pull/4) | 16.46 %	| |
AntPool | Yes | BIP8 | TBD | | 9.75 % | |
Luxor | Yes | BIP9 equivalent | | [Tweet](https://twitter.com/LuxorTechTeam/status/1329537408790978560) | 0.4% | |
SigmaPool | Undecided | | | | 0.20 %	| |
NovaBlock  | Yes | BIP9 equivalent, BIP8(false, 1y) | [taproot/bip9](https://explorer.poolin.com/block/000000000000000000099e89321b5b7942d9b615393965a2c8990dc6c431b745) | [Tweet](https://twitter.com/bitentrepreneur/status/1331570001552297984/likes) | 0.63 % | LOT = FALSE |
ViaBTC   | Yes | | | [Tweet](https://twitter.com/yhaiyang/status/1332402832075411456)| 7.50 %
Binance Pool | Yes | | | | 11.99 %	
Huobi Pool | Yes | TBD | TBD| | 8.63 %	
58COIN&1THash	| Yes | TBD | TBD| | 5.48 %	
SpiderPool	| Yes | TBD | TBD| | 0.52 %	
Lubian.com | **No Answer** | | | | 3.48 %
BTC.TOP | **No Answer** | | | | 1.98 %
OKKONG | **No Answer** |  | | | .34 %
TATMAS Pool | **No Answer** | | | | .56 %
WAYI.CN | **No Answer** | | | | .67 %
OKExPool | **No Answer** | | | | .54 %
Bitcoin.com | **No Answer** | | | | .02 %
SoloCK | **No Answer** |  | | | .02%
Foundry USA | **No Answer** |  | | | .56%
SBI Crypto | **No Answer** |  | | | .79%
unknown | | | | | 2.2 %


**Total hashrate (1 month average) in support of Taproot:** 88.69 % (as of 2/2/2021)

------

Want to be included in the list? Email <alejandro@poolin.com> or create a pull request [here](https://github.com/taprootactivation). 
Media enquiries: please reach out to <alejandro@poolin.com> or contact [@bitentrepreneur](https://twitter.com/bitentrepreneur) on Twitter.

