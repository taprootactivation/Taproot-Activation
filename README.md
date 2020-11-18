## Taproot is a proposed Bitcoin protocol upgrade that can be deployed as a forward-compatible soft fork. By combining the Schnorr signature algorithm with MAST (Merklized Abstract Syntax Trees) and a new scripting language called Tapscript, Taproot will expand Bitcoin’s smart contract flexibility, while offering more privacy by letting users mask complex smart contracts as a regular bitcoin transaction.
More in depth information can be found in this Bitcoin Magazine article by Aaron van Wirdum [Taproot Is Coming: What It Is, And How It Will Benefit Bitcoin](https://bitcoinmagazine.com/articles/taproot-coming-what-it-and-how-it-will-benefit-bitcoin)
 
  ------
 
A soft fork is a change to the Bitcoin protocol wherein only previously valid blocks/transactions are made invalid. Since old nodes will recognize the new blocks as valid, a soft fork is forward-compatible. See more here: [Soft fork bitcoin wiki](https://en.bitcoin.it/wiki/Softfork) 

Soft forks can be activated in several ways. Several of the previous soft forks have been activated using [BIP 9](https://en.bitcoin.it/wiki/BIP_0009), which requires a (super)majority of miners (by hash power) to signal support for the upgrade. A proposed alternative is [BIP 8](https://en.bitcoin.it/wiki/BIP_0008), which could activate the upgrade after some time even without a (super)majority of miners signaling support.

## Proposal overview

![proposal overview](https://en.bitcoin.it/w/images/en/1/19/Activation-timeline.png)

More in-depth information on [Taproot activation proposals](https://en.bitcoin.it/wiki/Taproot_activation_proposals) can be found in the Bitcion Wiki.
 
**The aim of this site is to assist in the activation of the Taproot soft fork. We have reached out to several Bitcoin mining pools to find out if:**
 
1. If they support the Taproot upgrade
1. If so, which activation method they prefer
1. If they want to insert a coinbase message in a block to announce their preference (even before the actual activation window opens)

------
 
 Mining Pool |   Taproot?     |  Activation | Coinbase Signal
------------ | ------------- | ------------- | ------------- |
Poolin | Yes | BIP9 equivalent, BIP8(false, 1y) | https://explorer.poolin.com/block/0000000000000000000698859d225da3129461173d6a9c07b2849edc9da0a12d | 
Slush Pool | Yes | BIP8 |  |
BTC.com | Yes | Modern Soft Fork Activation | TBD |
 | | | 
 | | | 
 | | |
 | | | 

Want to be included in the list? Email alejandro@poolin.com or create a pull request [here](https://github.com/taprootactivation). 
Media enquires alejandro@poolin.com
