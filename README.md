# Dopex

Dopex (Decentralized Options Exchange) is a DeFi protocol originally built on Arbitrum that pioneered Single Staking Option Vaults (SSOV) for on-chain options trading. The protocol has evolved into [Stryke](https://www.stryke.xyz), introducing Concentrated Liquidity AMM Options (CLAMM) and cross-chain support via LayerZero and Chainlink CCIP.

## APIs

This profile covers three API surfaces:

- **CLAMM Options Trading API** — option market data, strikes chain, purchase quotes, trade calldata, and history
- **LP Management API** — deposit/withdraw calldata, LP position queries, and transaction history
- **xSYK Staking API** — vested and staked xSYK position queries by account address

Base URL: `https://api.stryke.xyz`

## Resources

- Website: https://www.stryke.xyz
- Documentation: https://docs.stryke.xyz
- Legacy Dopex Docs: https://docs.dopex.io
- GitHub: https://github.com/stryke-xyz
- Discord: https://discord.gg/stryke
- DefiLlama: https://defillama.com/protocol/dopex

## Supporting Files

- [plans/plans.yml](plans/plans.yml) — API access plans and features
- [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml) — rate limit documentation
- [finops/finops.yml](finops/finops.yml) — cost and financial operations guidance
