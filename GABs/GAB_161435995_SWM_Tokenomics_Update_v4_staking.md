---
Title: Swarm Tokenomics Update v4, Staking
Sponsor: @omgcorn
Created: 22-03-2021
Version: version no. 4.0
Ballot Type: Up/Down
Voting Period: 2 days
Staking Address: Exempt from the staking requirements per SNC-2019.02/Article VII.B.10
Start time: 1614621600 (UTC/GMT Monday, March 22, 2021 6:00:00 PM)
End time: 1615226400 (UTC/GMT Monday, March 24, 2021 6:00:00 PM)	
---

# Proposal to change Swarm Network Tokenomics, v4, Staking

## Description of the proposed Governance Action

Current staking proposal:

Balancer Smart Pool (0.001% swap fees, 50% SWM / 25% LP1 / 25% LP2, SWM Governance will decide going forward on swap fee, weights, tokens)
The IssuanceMintFees and Masternodes Rewards (renamed as Staking Rewards continuing to follow the set schedule) will voluntarily be added to the assets within this pool, such that the asset base increases constantly and the SWM Staking Pool Token holders benefit on an ongoing basis.
LP1 Liquidity Pool (SLP): Balancer Smart Pool at https://pools.balancer.exchange/#/pool/0xbcbaa95dba4c31283bbc4454c6aa137e26eab009/about (0.001% swap fees, 50% SWM, 50% ETH SWM Governance will decide going forward on swap fee, weights, tokens)
LP2 Liquidity Pool (UNI-V2-ETH-SWM): Uniswap Liquidity Pool at https://info.uniswap.org/pair/0xe0b1433e0174b47e8879ee387f1069a0dbf94137 (0.30% swap fees, 50% SWM, 50% ETH, no governance)

Potential issues with this SSP staking model:

A large need area for Swarm is lack of liquidity on the secondary market and therefore as approved rewarding LP staking is the fastest way to solve this problem, the proposed (SSP) solution does incentivize liquidity, but drawbacks have been identified.

In order to deposit all three assets into the SSP (SWM, SLP, UNI LP), there are significantly more transactions required to approve and deposit, versus just staking LP. 

This is gas intensive to create the Balancer SLP LP, Uniswap LP, requiring approvals and deposits to the LP pools and then same for deposit of all three assets to the SSP. It’s technically daunting and costly for anyone trying to make sure they deposit the ideal ratio of all three assets.

The current model dilutes liquidity across two different AMM pools (Balancer, Uniswap). It is more desirable to consolidate liquidity in one pool for better trade experience.

It is not optimal from the perspective of displaying exactly what assets (SWM SLP, UNI LP) holders have since LP can be traded in the SSP, this will constantly change. Additionally, since it’s possible to single asset deposit, this creates imbalance and significant arbitrage opportunities for automated arbitrage bots. This has been evidenced in early deposits to SSP where bots instantly arbitraged stakers Uniswap LP, therefore likely to lose LP (SWM and ETH) from the main pools we are trying to increase, as Swarm gets bought on other markets and pools not accepted in the SSP to arbitrage assets.

If then further adding SWM reward directly to the SSP, this may create even further opportunity for bots and possible further arbitrage of stakers valued LP tokens.


## Purpose and rationale for the Governance Action and its intended outcomes

Move to simple model of deposit Swarm (SWM) to a staking contract P1 (Pool 1) and a secondary pool Deposit Uniswap LP (UNI-V2-ETH-SWM) P2 (Pool 2) to a staking contract (Modified Sushi contract for both to be created). This removes the possibility of loss from arbitrage of staked LP in the current SSP pool while still incentivizing staking and LP staking.

Create a new UI that is simple to use, and clearly allows staker to deposit into either or both pools if they hold both assets. 

Swarm Treasury rewards (prev block rewards) and 80% of SRC20 minting fees are added to the staking contract via the rewards wallet. 20% of all SRC20 minting fees go to the Swarm Treasury wallet to maintain the Swarm treasury and sustain ongoing development of the Swarm Network

This amendment allows very simple display of the APY, staking wallets can clearly and easily see what share of the pool they own and what yield they are earning. Higher rewards for LP staking to grow the secondary market as needed. APY can be adjusted by ballot as deemed necessary

Rewards from SRC20 minting are distributed: 80% to Treasury rewards wallet (used to incentivize staking and liquidity) 
20% to Swarm Treasury (ongoing development)
The Treasury rewards wallet is then distributed 20% P1 & 80% P2.

## Identify the specific uses for which Swarm Treasury funds may be expended to support the Governance Action;
50,000 SWM to: 0xe3D2102f36fE4cDDDC62A3E61d33bbF28086Dc29. This covers staking smart contract development, UI development, snapshot update, and gas for deployment of staking contracts.

## Additional information for Governance Actions requiring the expenditure of Swarm Treasury funds


## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
