# Audit Portfolio - 0x23r0


- [About 0x23r0](#about-0x23r0)
- [Competitive Audits](#competitive-audits)
- [Gas Optimization Audits 2023](#gas-optimization-audits-2023)
- [Private Security Review](#private-security-review)
- [Bug Bounties](#bug-bounties)

---

# About 0x23r0

I started in Web3 security in February 2023 and have since continued auditing part-time while working full-time as a software engineer, during which I have identified over 100 vulnerabilities across different protocols. Some of my audits are performed under my second alias, "hunter_w3b."

For private audit or consulting requests, please reach out to me via Twitter (@0x23r0), Telegram (@Hashmattabibi), or Discord (0x23r0).

---

# Competitive Audits

| No.| Contest | Description | Platform | Alias | Findings | Rank | Report |
|-----|---------|-------------|----------|-------|----------|------|--------|
|28|[Inverse Finance - Junior Tranche](https://audits.sherlock.xyz/contests/1202) | Junior Tranche insurance mechanism for FiRM's fixed-rate lending protocol and DOLA stablecoin. | Sherlock | 0x23r0 | [1 M](https://github.com/sherlock-audit/2025-11-inverse-finance-junior-tranche-judging/issues/212) | 3rd 🥉 | [Link](https://audits.sherlock.xyz/contests/1202) |
|27|[Summer.fi - governance v2](https://audits.sherlock.xyz/contests/1176) | DeFi platform governance contracts for Summer.fi (ex Oasis.app). | Sherlock | 0x23r0 | [1 M](https://github.com/sherlock-audit/2025-09-summer-fi-governance-v2-judging/issues/581) | Top 7 | [Link](https://audits.sherlock.xyz/contests/1176) |
|26|[Mellow Flexible Vaults](https://audits.sherlock.xyz/contests/964) | Modular vault infrastructure for institutional-grade asset management on EVM chains. | Sherlock | 0x23r0 | [2 H, 4 M](https://audits.sherlock.xyz/contests/964) | Top 10 | [Link](https://audits.sherlock.xyz/contests/964) |
|25|[LEND](https://audits.sherlock.xyz/contests/908) | Cross-chain lending protocol with real yield value extraction. | Sherlock | 0x23r0 | [5 H, 7 M](https://audits.sherlock.xyz/contests/908) | | [Link](https://audits.sherlock.xyz/contests/908) |
|24|[Burve](https://audits.sherlock.xyz/contests/858) | 16-token multi-swap for pegged assets on Berachain with rehypothecation yields. | Sherlock | 0x23r0 | [2 H](https://audits.sherlock.xyz/contests/858) | | [Link](https://audits.sherlock.xyz/contests/858) |
|23|[Forte: Float128 Solidity Library](https://code4rena.com/audits/2025-03-forte-float128-solidity-library) | Signed floating-point library optimized for Solidity. | Code4rena | 0x23r0 | [2 H](https://code4rena.com/audits/2025-04-forte-float128-solidity-library/dashboard) | | [Link](https://code4rena.com/audits/2025-04-forte-float128-solidity-library/dashboard) |
|22|[Symmio, Staking and Vesting](https://audits.sherlock.xyz/contests/838) | Peripheral staking and vesting contracts for Symmio's OTC derivatives governance token. | Sherlock | 0x23r0 | [1 H, 1 M](https://github.com/sherlock-audit/2025-03-symm-io-stacking-judging/issues/209) | Top 4 | [Link](https://audits.sherlock.xyz/contests/838) |
|21|[Regnum Aurum Acquisition Corp](https://codehawks.cyfrin.io/c/2025-02-raac) | Protocol bringing real estate on-chain with DeFi integration. | Codehawks | 0x23r0 | [26 H, 31 M, 12 L](https://codehawks.cyfrin.io/c/2025-02-raac/results?t=report) | 🥇 1st | [Link](https://codehawks.cyfrin.io/c/2025-02-raac/results?t=report) |
|20|[Liquid Ron](https://code4rena.com/audits/2025-01-liquid-ron) | Liquid staking for RON tokens with automated staking actions. | Code4rena | 0x23r0 | [1 H, 1 M](https://code4rena.com/reports/2025-01-liquid-ron) | Top 10 | [Link](https://code4rena.com/reports/2025-01-liquid-ron) |
|19|[IQ AI](https://code4rena.com/audits/2025-01-iq-ai) | Tokenized AI agents for DeFi and beyond. | Code4rena | 0x23r0 | [1 M](https://code4rena.com/reports/2025-01-iq-ai) | | [Link](https://code4rena.com/reports/2025-01-iq-ai) |
|18|[Zaros](https://codehawks.cyfrin.io/c/2025-01-zaros-part-2) | Perpetuals DEX powered by Boosted (Re)Staking Vaults on Arbitrum. | Codehawks | 0x23r0 | [1 H, 1 L](https://codehawks.cyfrin.io/c/2025-01-zaros-part-2/results?t=report) | | [Link](https://codehawks.cyfrin.io/c/2025-01-zaros-part-2/results?t=report) |
|17|[Plaza Finance](https://audits.sherlock.xyz/contests/682) | Public marketplace for bonds and leverage on Base. | Sherlock | 0x23r0 | [4 H, 5 M](https://audits.sherlock.xyz/contests/682) | Top 10 | [Link](https://audits.sherlock.xyz/contests/682) |
|16|[Autonomint Colored Dollar V1](https://audits.sherlock.xyz/contests/569) | Delta-neutral stablecoin backed by crypto with decentralized credit default swaps. | Sherlock | 0x23r0 | [4 H, 5 M](https://audits.sherlock.xyz/contests/569) | | [Link](https://audits.sherlock.xyz/contests/569) |
|15|[vVv Launchpad](https://audits.sherlock.xyz/contests/647) | Contracts for seed & launchpad investments and token distribution. | Sherlock | Hunter_w3b | [1 H](https://audits.sherlock.xyz/contests/647) | 🥇 1st | [Link](https://audits.sherlock.xyz/contests/647) |
|14|[Covalent - EWM Light Client](https://audits.sherlock.xyz/contests/618) | Light client contracts for Ethereum Wayback Machine data availability. | Sherlock | Hunter_w3b | [1 M](https://audits.sherlock.xyz/contests/618) | 🥈 2nd | [Link](https://audits.sherlock.xyz/contests/618) |
|13|[AXION](https://audits.sherlock.xyz/contests/552) | DeFi stablecoin with collateral deployed in on-chain liquidity pools. | Sherlock | Hunter_w3b | [1 M](https://audits.sherlock.xyz/contests/552) | Top 10 | [Link](https://audits.sherlock.xyz/contests/552) |
|12|[Liquid Staking](https://codehawks.cyfrin.io/c/2024-09-stakelink/) | Liquid delegated staking platform for Chainlink Staking. | Codehawks | Hunter_w3b | [1 M](https://codehawks.cyfrin.io/c/2024-09-stakelink/results?t=report) | | [Link](https://codehawks.cyfrin.io/c/2024-09-stakelink/results?t=report) |
|11|[Cork Protocol](https://audits.sherlock.xyz/contests/506) | Protocol for pricing, hedging, and trading risk. | Sherlock | Hunter_w3b | [1 H, 1 M](https://audits.sherlock.xyz/contests/506) | Top 10 | [Link](https://audits.sherlock.xyz/contests/506) |
|10|[Tadle](https://codehawks.cyfrin.io/c/2024-08-tadle) | Decentralized pre-market infrastructure bridging primary and secondary financial markets. | Codehawks | Hunter_w3b | [2 H, 2 L](https://codehawks.cyfrin.io/c/2024-08-tadle) | | [Link](https://codehawks.cyfrin.io/c/2024-08-tadle) |
|9|[MagicSea](https://audits.sherlock.xyz/contests/437) | DEX on IOTA EVM — MasterChef, rewarder, staking, and voting contracts. | Sherlock | Hunter_w3b | [1 M](https://audits.sherlock.xyz/contests/437) | | [Link](https://audits.sherlock.xyz/contests/437) |
|8|[Thorchain](https://code4rena.com/audits/2024-06-thorchain) | Major cross-chain DEX supporting Bitcoin, Ethereum, and multiple UTXO/EVM chains. | Code4rena | Hunter_w3b | [1 M](https://code4rena.com/reports/2024-06-thorchain) | Top 10 | [Link](https://code4rena.com/reports/2024-06-thorchain) |
|7|[Tokensoft Distributor](https://audits.sherlock.xyz/contests/285) | Per-address functionality added to token distribution contracts. | Sherlock | Hunter_w3b | [1 M](https://audits.sherlock.xyz/contests/285) | 🥈 2nd | [Link](https://audits.sherlock.xyz/contests/285) |
|6|[Sophon Farming Contracts](https://audits.sherlock.xyz/contests/376) | Airdrop staking contracts for Sophon's $SOPH token on ZkSync. | Sherlock | Hunter_w3b | [1 H](https://audits.sherlock.xyz/contests/376) | 3rd 🥉 | [Link](https://audits.sherlock.xyz/contests/376) |
|5|[Renzo](https://code4rena.com/audits/2024-04-renzo) | EigenLayer restaking protocol abstracting staking complexity for end users. | Code4rena | Hunter_w3b | [1 H, 2 M](https://code4rena.com/reports/2024-04-renzo) | | [Link](https://code4rena.com/reports/2024-04-renzo) |
|4|[Revert Lend](https://code4rena.com/audits/2024-03-revert-lend) | Lending protocol designed for Uniswap v3 liquidity providers. | Code4rena | Hunter_w3b | [1 M](https://code4rena.com/reports/2024-03-revert-lend) | | [Link](https://code4rena.com/reports/2024-03-revert-lend) |
|3|[Covalent](https://audits.sherlock.xyz/contests/127) | Ethereum Wayback Machine for historical data availability on the Covalent Network. | Sherlock | Hunter_w3b | [1 M](https://audits.sherlock.xyz/contests/127) | Top 10 | [Link](https://audits.sherlock.xyz/contests/127) |
|2|[Steadefi](https://codehawks.cyfrin.io/c/2023-10-SteadeFi) | DeFi protocol for sustainable real yields with automated position management. | Codehawks | Hunter_w3b | [1 M](https://codehawks.cyfrin.io/c/2023-10-SteadeFi/results?t=report) | | [Link](https://codehawks.cyfrin.io/c/2023-10-SteadeFi/results?t=report) |
|1|[Rubicon v2](https://code4rena.com/audits/2023-04-rubicon-v2) | On-chain order book protocol for Ethereum built on L2s. | Code4rena | Hunter_w3b | [1 M](https://code4rena.com/reports/2023-04-rubicon) | | [Link](https://code4rena.com/reports/2023-04-rubicon) |





---

# Gas Optimization Audits 2023

| No. | Contest                                                                                                        | Date       | Platform  | Alias      | Report                                                     |
|-----| -------------------------------------------------------------------------------------------------------------- | ---------- | --------- | ---------- | ---------------------------------------------------------- |
| 1| [Ethos Reserve audit](https://github.com/code-423n4/2023-02-ethos)                                             | 2023.03.08 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-02-ethos#gas-optimizations)        |
| 2| [Wenwin audit](https://github.com/code-423n4/2023-03-wenwin)                                                   | 2023.03.10 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-03-wenwin#gas-optimizations)       |
| 3| [Neo Tokyo audit](https://github.com/code-423n4/2023-03-neotokyo)                                              | 2023.03.16 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-03-neotokyo#gas-optimizations)     |
| 4| [Caviar Private Pools](https://github.com/code-423n4/2023-04-caviar)                                           | 2023.04.14 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-04-caviar#gas-optimizations)       |
| 5| [Frankencoin](https://github.com/code-423n4/2023-04-frankencoin)                                               | 2023.04.20 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-04-frankencoin#gas-optimizations)  |
| 6| [Ajna Protocol](https://github.com/code-423n4/2023-05-ajna)                                                    | 2023.05.12 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-05-ajna#gas-optimizations)         |
| 7| [Lybra Finance](https://github.com/code-423n4/2023-06-lybra)                                                   | 2023.07.04 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-06-lybra#gas-optimizations)        |
| 8| [Maia DAO Ecosystem](https://github.com/code-423n4/2023-05-maia)                                               | 2023.07.06 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-05-maia#gas-optimizations)         |
| 9| [PoolTogether](https://github.com/code-423n4/2023-07-pooltogether)                                             | 2023.07.15 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-07-pooltogether#gas-optimizations) |
| 10| [LUKSO](https://github.com/code-423n4/2023-06-lukso)                                                           | 2023.07.15 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-06-lukso#gas-optimizations)        |
| 11| [Amphora Protocol](https://github.com/code-423n4/2023-07-amphora)                                              | 2023.07.27 | Code4rena | Hunter_w3b | [Link](https://github.com/code-423n4/2023-07-amphora)      |
| 12| [Tapioca DAO](https://github.com/code-423n4/2023-07-tapioca)                                                   | 2023.08.05 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-07-tapioc#gas-optimizationsa)      |
| 13| [Tangible Caviar ](https://github.com/code-423n4/2023-08-tangible)                                             | 2023.08.06 | Code4rena | Hunter_w3b | [Link](https://github.com/code-423n4/2023-08-)             |
| 14| [Ondo Finance](https://github.com/code-423n4/2023-09-ondo)                                                     | 2023.09.08 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-09-ondo#gas-optimizations)         |
|15 | [Canto Liquidity Mining Protocol](https://github.com/code-423n4/2023-10-canto)                                 | 2023.10.07 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-10-canto#gas-optimizations)        |
|16| [Maia DAO - Ulysses](https://github.com/code-423n4/2023-09-maia)                                               | 2023.10.07 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-09-maia#gas-optimizations)         |
|17 | [Brahma](https://github.com/code-423n4/2023-10-brahma)                                                         | 2023.10.21 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-10-brahma#gas-optimizations)       |
|18 | [zkSync Era](https://github.com/code-423n4/2023-10-zksync)                                                     | 2023.10.24 | Code4rena | Hunter_w3b | [Private]()                                                |
|19 | [Ethena Labs](https://github.com/code-423n4/2023-10-ethena)                                                    | 2023.10.31 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-10-ethena#gas-optimizations)       |
|20 | [Badger eBTC Audit + Certora Formal Verification Competition](https://github.com/code-423n4/2023-10-badger)    | 2023.11.15 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-10-badger#gas-optimizations)       |
| 21| [Kelp DAO rsETH](https://github.com/code-423n4/2023-11-kelp)                                                   | 2023.11.16 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-11-kelp#gas-optimizations)         |
|22 | [Canto Application Specific Dollars and Bonding Curves for 1155s](https://github.com/code-423n4/2023-11-canto) | 2023.11.18 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-11-canto#gas-optimizations)        |
| 23| [Olas](https://github.com/code-423n4/2023-12-autonolas)                                                        | 2024.01.09 | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2023-12-autonolas#gas-optimizations)    |
| 24| [reNFT](https://github.com/code-423n4/2024-01-renft)                                                           | 2024.01.19 | Code4rena | Hunter_w3b | [Link](https://github.com/code-423n4/2024-01-renft)        |
| 25|  [Curves](https://code4rena.com/audits/2024-01-curves)|2024.01.17  | Code4rena | Hunter_w3b | [Link](https://code4rena.com/reports/2024-01-curves#gas-optimizations)|
| 27| [Opus](https://code4rena.com/audits/2024-01-opus)  | 2024.01.10  |Code4rena | Hunter_w3b| [Link](https://code4rena.com/reports/2024-01-opus#audit-analysis)
| 28|[Salty.IO](https://code4rena.com/audits/2024-01-saltyio)   | 2024.01.17  | Code4rena |Hunter_w3b| [Link](https://code4rena.com/audits/2024-01-saltyio)
| 29| [Decent](https://code4rena.com/audits/2024-01-decent)  | 2024.1.20 | Code4rena |Hunter_w3b | [Link](https://code4rena.com/reports/2024-01-decent#gas-optimizations)
| 30| [AI Arena](https://code4rena.com/audits/2024-02-ai-arena)   |  2024.2.10 | Code4rena |Hunter_w3b | [Link](https://code4rena.com/audits/2024-02-ai-arena#gas-optimizations)
| 31|  [PoolTogether](https://code4rena.com/audits/2024-03-pooltogether) | 2024.3.5 | Code4rena |Hunter_w3b | [Link](https://code4rena.com/reports/2024-03-pooltogether#gas-optimizations)
| 32|  [Taiko](https://code4rena.com/audits/2024-03-taiko) | 2024.3.7 | Code4rena |Hunter_w3b | [Link](https://code4rena.com/reports/2024-03-taiko#gas-optimizations)
| 33|  [Smart Wallet](https://code4rena.com/audits/2024-03-smart-wallet) |2024.3.15  | Code4rena |Hunter_w3b | [Link](https://code4rena.com/reports/2024-03-coinbase#gas-optimizations)

---

# Private Security Review

| Protocol | Description | Provider |Findings |Report|
| -------- | ----------- | ------ |------ |------ |
| [Chiliz Chain System Contracts](https://audits.sherlock.xyz/contests/550)     |Chiliz Chain is the world’s leading sports-focused blockchain, with an ecosystem embraced by 70+ elite sports teams. An EVM compatible POSA layer 1 blockchain based on a fork of BSC chain.         |   Sherlock |Private|Private|
|[Covalent - EWM Light Client](https://audits.sherlock.xyz/contests/618)|Covalent is a modular data infrastructure layer that’s dedicated to solving long-term data availability on Ethereum. The Covalent Network’s Ethereum Wayback Machine (EWM) ensures secure, decentralized access to Ethereum’s transaction data after it’s purged. This contest focuses on auditing the contracts for the EWM Light Client, a product designed to ensure data availability in the EWM.|Sherlock|Private|Private|
|[Rezerve Money](https://audits.sherlock.xyz/contests/1134)|Rezerve Money (RZR) is a decentralized treasury accumulation protocol with one mission: accumulate 1 million ETH—powered entirely by community and DeFi.|Sherlock| Private |Private |
|[Privacy Cash](https://audits.sherlock.xyz/contests/1160)|Privacy Cash is a compliant privacy pool on Solana. The contest is on auditing the ZK circuit, Solana programs and key crypto/encryption primitives used in the product, to ensure the protocol logic is sound. |Sherlock|Private|Private|
---

# Bug Bounties

| Program | Description | Severity | Writeups |
| ------- | ----------- | -------- | -------- |
| Soon..    |         |      |      |



