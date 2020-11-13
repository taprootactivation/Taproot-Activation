## Taproot expands Bitcoin’s smart contract flexibility, while offering more privacy. By combining both MAST (Merkelized Abstract Syntax Tree) & Schnorr, Taproot is able to mask a complex smart contract as a regular bitcoin transaction.
More in depth information can be found in this article by Aaron Van Wirdum [Taproot Is Coming: What It Is, And How It Will Benefit Bitcoin](https://bitcoinmagazine.com/articles/taproot-coming-what-it-and-how-it-will-benefit-bitcoin)
 
 A softfork is a change to the bitcoin protocol wherein only previously valid blocks/transactions are made invalid. Since old nodes will recognize the new blocks as valid, a softfork is backward-compatible. See more here: https://en.bitcoin.it/wiki/Softfork
 
 ------
 
**There are several different Bitcoin Improvement  activation methods for Taproots upgrade, they are:**
  
1. **BIP 9 (and BIP 8 without forced activation):** The upgrade will activate if and when 95% of hash power signals support for the upgrade. If after a year this threshold hasn't been reached, the upgrade expires. Both the 95% treshold and the one-year expiry parameters could be set differently.

1. **BIP 8 (with forced activation):** The upgrade will activate if and when 95% of hash power signals support for the upgrade. If after a year this threshold hasn't been reached, the upgrade activates regardless, and blocks that don't follow the new rules will be rejected. Both the 95% treshold and the one-year expiry parameters could be set differently.

There are also ideas to combine different proposals. For example, try BIP 9 first, if it expires, try again with BIP 8 (with forced activation).
 
**The aim of this site is to assist in the activation of the Taproot soft fork. We have reached out to several Bitcoin mining pools to find out if:**
 
1. Would like to activate Taproot
1. Which activation method they prefer
1. What threshold percentage should be met
1. Expiry date
1. Coinbase signal

------
 
 Mining Pool |   Taproot?     |  Activation   | Threshold    | Expiry | Coinbase Singal
------------ | ------------- | ------------- | ------------- | ------------- | -------------
Poolin | Yes | BIP9 | 95% | 1 year | link
 | | | 
 | | |
 | | | 
 | | | 
 | | |
 | | | 

Want to be included in the list? Email alejandro@poolin.com or create a pull request [here](https://github.com/taprootactivation).
