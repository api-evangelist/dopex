# Dopex

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
