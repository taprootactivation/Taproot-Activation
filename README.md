## Taproot is a proposed Bitcoin protocol upgrade that can be deployed as a backwards-compatibe soft fork. By combining the Schnorr signature algorithm with MAST (Merkelized Abstract Syntax Trees) and a new scripting language called Tapscript, Taproot will expand Bitcoin’s smart contract flexibility, while offering more privacy by letting users mask complex smart contracts as a regular bitcoin transaction.
More in depth information can be found in this article [Taproot Is Coming: What It Is, And How It Will Benefit Bitcoin](https://bitcoinmagazine.com/articles/taproot-coming-what-it-and-how-it-will-benefit-bitcoin)
 
 A softfork is a change to the bitcoin protocol wherein only previously valid blocks/transactions are made invalid. Since old nodes will recognize the new blocks as valid, a softfork is backward-compatible. See more here: https://en.bitcoin.it/wiki/Softfork
 
 ------
 
**Bitcoin Improvement Proposal activation methods for Taproots upgrade:**

Soft forks can be activated in several ways. Several of the previous soft forks have been activated using BIP 9 (Bitcoin Improvement Proposal 9), which requires a (super)majority of miners (by hash power) to signal support for the upgrade. A proposed alternative is BIP 8, which could activate the upgrade after some time even without a (super)majority of miners signaling support. There are also ideas to combine BIP 9-style activation with BIP 8-style activation.

Soft forks can be activated in several ways. Several of the previous soft forks have been activated using BIP 9 (Bitcoin Improvement Proposal 9), which requires a (super)majority of miners (by hash power) to signal support for the upgrade. A proposed alternative is BIP 8, which could activate the upgrade after some time even without a (super)majority of miners signaling support. There are also ideas to combine BIP 9-style activation with BIP 8-style activation.

In short:
  
1. **BIP 9 (and BIP 8 without forced activation):** The upgrade will activate if and when 95% of hash power signals support for the upgrade. If after a year this threshold hasn't been reached, the upgrade expires. Both the 95% treshold and the one-year expiry parameters could be set differently.

1. **BIP 8 (with forced activation):** The upgrade will activate if and when 95% of hash power signals support for the upgrade. If after a year this threshold hasn't been reached, the upgrade activates regardless, and blocks that don't follow the new rules will be rejected. Both the 95% treshold and the one-year expiry parameters could be set differently.

There are also ideas to combine different proposals. For example, try BIP 9 first, if it expires, try again with BIP 8 (with forced activation). More in depth information on Taproot activation can be found in this Bitcoin Magazine article by Aaron van Wirdum: BIP 8, BIP 9 Or Modern Soft Fork Activation: How Bitcoin Could Upgrade Next

 
**The aim of this site is to assist in the activation of the Taproot soft fork. We have reached out to several Bitcoin mining pools to find out if:**
 
1. If they support the Taproot upgrade
1. If so, which activation method they prefer
1. What threshold hash power percentage should be met to activate the upgrade
1. How long it should take before activation either expires or is enforced
1. If they want to insert a coinbase message in their blocks to announce their preference (even before the actual activation window opens)

------
 
 Mining Pool |   Taproot?     |  Activation   | Threshold    | Expiry | Coinbase Signal
------------ | ------------- | ------------- | ------------- | ------------- | -------------
Poolin | Yes | BIP9 | 95% | 1 year | 1 |
Slush Pool | Yes | BIP8 | 90% | 1 year | 
 | | |
 | | | 
 | | | 
 | | |
 | | | 

Want to be included in the list? Email alejandro@poolin.com or create a pull request [here](https://github.com/taprootactivation).
