<span style="color:blue"> **[UPDATE: SPEEDY TRIAL ADDED TO BITCOIN CORE, CLICK FOR ACTIVATION PARAMETERS](https://github.com/bitcoin/bitcoin/pull/21686)** </span>.


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

------

<span style="color:blue"> **[UPDATE: SPEEDY TRIAL ADDED TO BITCOIN CORE, CLICK FOR ACTIVATION PARAMETERS](https://github.com/bitcoin/bitcoin/pull/21686)** </span>.


------


**UPDATE: Under Speedy Trial, miners would have three months to signal support for Taproot after its code is shipped through Bitcoin Core, Bitcoin’s primary software version. If 90% of the blocks in a given time frame are not Taproot-supporting, then that means miners don’t support the upgrade and activation fails. If the threshold is reached, then activation takes place after a six-month “locked-in” period."** More info [here](https://www.coindesk.com/speedy-trial-taproot-activation-bitcoin-safety-net-uasf)

Note: TBD = To be decided

------

 Mining Pool |   Taproot?    | SPEEDY TRIAL SIGNAL | [Global Hashrate % (1 month](https://btc.com/stats/pool?pool_mode=month) |
------------ | ------------- | ------------- | ------------- |
[Poolin](https://poolin.com) | Yes | | 13.33 %	|  |
Slush Pool | Yes | 🟩 | | 2.82 %		|
BTC.com | Yes  | |  | 9.58 %		|
F2Pool | Yes | 🟩 |  | 17.02 %	|  |
AntPool | Yes | TBD | | 14.44 %	| 
Luxor | Yes | |  | 0.4% | 
SigmaPool | Undecided | | | 0.39 %	| 
NovaBlock  | Yes |  |  | 0.57 % | 
ViaBTC   | Yes | | | 7.4 %
Binance Pool | Yes | | | 10.55 %	
Huobi Pool | Yes |  TBD| | 7.44 %
58COIN&1THash	| Yes |  TBD| | 5.5 %	
SpiderPool	| Yes | TBD| | 0.53 %	
Lubian.com | **No Answer** | | |  3 %
BTC.TOP | **No Answer** | | |  1.93 %	
OKKONG | **No Answer** |  | |  .24 %
TATMAS Pool | **No Answer** | | | .64 %
WAYI.CN | **No Answer** | | |  0.34 %	
OKExPool | **No Answer** | | |  0.85 %	
Bitcoin.com | **No Answer** | | |  .02 %
SoloCK | **No Answer** |  | |  .02%
Foundry USA | Yes | 🟩 | | 2.85 %	
SBI Crypto | **No Answer** | | |  0.56 %	
Rawpool | | | | 0.60 %	
ArkPool | | | | 0.43 %	
unknown | | | | 2.25 %	


**Total hashrate (1 month average) in support of Taproot:** 89.07 % (as of 2nd of March, 2021)

------

Want to be included in the list? Email <alejandro@poolin.com> or create a pull request [here](https://github.com/taprootactivation). 
Media enquiries: please reach out to <alejandro@poolin.com> or contact [@bitentrepreneur](https://twitter.com/bitentrepreneur) on Twitter.

