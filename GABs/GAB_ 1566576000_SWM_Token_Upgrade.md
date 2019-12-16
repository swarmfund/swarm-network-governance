---
Title: Upgrade the SWM token
Sponsor: SWARM Council (voted 23-08-2019, 5 "yes", 0 "no")
Created: 23-08-2019
Version: version no. 1.0
Ballot Type: Up/Down
Voting Period: 6 days
Staking Address: Exempt from the staking requirements per SNC-2019.02/Article VII.B.10 
Start time: 1566630000 (UTC/GMT Saturday, 24 August 2019, 07:00:00)	
End time: 1567112400 (UTC/GMT Thursday, 29 August 2019, 23:00:00)	
---

# Upgrade the SWM token 

This upgrade would involve replacing the current SWM token with the smart contract address 0x9e88613418cf03dca54d6a2cf6ad934a78c7a17a with a new SWM token smart contract (address to be communicated later).

The intent is to make the smart contract lighter, safer, and take advantage of the increased maturity of Ethereum since SWM launched.  Specifically:

 - The current SWM token contract is more complex than typical ERC20 contracts because it contains rich features which are no longer needed, and some that could post future risk to the project.
 - Reducing the weight or “cleaning up” the current SWM token contract, by replacing it with a new ERC20 token contract, will make it easier to integrate into wallets, exchanges, and other financial infrastructure with reduced gas needed for transactions.  With the new SWM token contract, for example, Members may experience fewer issues with respect to withdrawing tokens from exchanges.
 - The new ERC20 contract is fixing the supply of SWM tokens to 100,000,000.  The current SWM token contract was established with the ability to mint additional tokens beyond the currently issued level of 100,000,000.  If this proposal is adopted, there will be no ability under the new token contract to mint new tokens above.  This should provide long term predictability and promote trust in the economic model of the SWARM network.
- The new ERC20 contract will have a KYA (Know your asset) reference hash, so that related information about the project can be linked. 
 - The new ERC20 contract will change the name of the token to simply ‘SWARM’ instead of ‘Swarm Fund Token.’

Further details about the proposed plan and action items can be found here:
https://medium.com/swarmfund/swm-upgrade-156acb29ebe6

## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
