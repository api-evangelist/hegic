# Hegic

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

Hegic is an on-chain peer-to-pool options trading protocol deployed on Arbitrum, enabling users to trade ETH and WBTC call and put options with AMM mechanics and on-chain settlement in USDC. Liquidity providers fund shared pools and earn premiums from options buyers.

## APIs

This repository catalogs the public APIs available for querying Hegic protocol data:

1. **DefiLlama Hegic Protocol API** - Free REST API for TVL, fees, revenue, and options volume
2. **Arbiscan Token API** - Block explorer API for HEGIC token data on Arbitrum One
3. **Hegic Options Subgraph API** - GraphQL API via The Graph Protocol for options positions and historical data
4. **Hegic Smart Contracts (Arbitrum)** - Direct JSON-RPC access to core protocol contracts

## Key Contract Addresses

- HEGIC Token (Arbitrum): `0x431402e8b9de9aa016c743880e04e517074d8cec`
- HEGIC Token (Ethereum): `0x584bC13c7D411c00c01A62e8019472dE68768430`

## Links

- Website: https://www.hegic.co/
- App: https://www.hegic.co/app
- GitHub: https://github.com/hegic
- Analytics (Dune): https://dune.com/Juan_X/hegic-herge
- DefiLlama: https://defillama.com/protocol/hegic
- Governance Forum: https://gov.hegic.co/
- Blog: https://medium.com/hegic
- Twitter: https://twitter.com/HegicOptions

## APIs.json

The `apis.yml` file in this repository is an APIs.json 0.19 specification cataloging Hegic's available APIs and data access points.
