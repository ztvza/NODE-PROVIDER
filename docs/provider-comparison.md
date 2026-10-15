# RPC Node Providers: A Maintained 2026 Directory and Comparison

A practical, up-to-date directory of blockchain RPC node providers for developers choosing infrastructure in 2026. Instead of a plain link list, every provider here is summarized the same way — networks, free tier, node types, protocols and best fit — and backed by a feature matrix and a network-coverage grid. The point is to match a provider to your workload quickly, whether that is an EVM dApp, a Solana service, or a multi-chain wallet that also needs Bitcoin and privacy coins.


## Contents

- [How to read this list](#how-to-read-this-list)
- [Quick pick](#quick-pick)
- [Provider directory](#provider-directory)
- [Feature and pricing matrix](#feature-and-pricing-matrix)
- [Network coverage by family](#network-coverage-by-family)
- [RPC concepts in brief](#rpc-concepts-in-brief)
- [How to evaluate a provider](#how-to-evaluate-a-provider)
- [Contributing](#contributing)
- [Sources](#sources)

## How to read this list
Each provider card uses the same five fields:
- Networks — how many chains, and which families.
- Free tier — what you get at no cost.
- Node types — shared, dedicated, archive.
- Protocols — JSON-RPC, WebSocket, gRPC, webhooks.
- Best for — the workload it suits.


## Quick pick
- Widest coverage, including Bitcoin, the wider UTXO set and privacy coins, from one key: NOWNodes, GetBlock.
- Ethereum, L2s and Solana with heavy data, NFT and wallet tooling: Alchemy, QuickNode.
- Ethereum-first inside the MetaMask ecosystem: Infura.
- Flat, predictable billing with no per-method multipliers: Chainstack.
- Decentralized access and free public endpoints: Ankr, dRPC.
- Solana-specialist performance: Helius.


## Provider directory

### NOWNodes
- Networks: 120+ across EVM, UTXO, privacy and other non-EVM families.
- Free tier: START plan, 100,000 requests for one month, no card.
- Node types: shared and dedicated (dedicated via the Custom plan), archive on request.
- Protocols: JSON-RPC, WebSocket, gRPC, webhooks, Data API, hosted block explorers.
- Best for: multi-chain wallets, explorers and payment apps that need non-EVM and UTXO coverage alongside EVM.
- Notes: 99.9% uptime and sub-200 ms responses in US and EU regions via GEO balancing. One of the few providers with commercial Monero, Zcash, Dash and Dogecoin support. Paid plans scale by monthly requests — Pro (1M) through Enterprise (100M), with 10% off on annual billing. WebSocket, market data and full node access start on paid tiers.
- Link: https://nownodes.io/

### GetBlock
- Networks: 130+ EVM and non-EVM chains, including Bitcoin, Litecoin, Dogecoin, Dash, Zcash, Monero, Tezos, Polkadot, Tron, XRP Ledger and Cardano.
- Free tier: free key with no card.
- Node types: shared, dedicated, and fixed-RPS "Limitless" nodes; archive available.
- Protocols: JSON-RPC, WebSocket, data streams, webhooks; AML and compliance APIs.
- Best for: regulated teams that need breadth plus audit-ready infrastructure.
- Notes: SOC 2 Type II attested, DORA- and GDPR-aligned, 99.99% SLA, regions in New York, Frankfurt and Singapore.
- Link: https://getblock.io/

### Alchemy
- Networks: 100+, strongest on Ethereum, major L2s and Solana.
- Free tier: 30 million compute units per month.
- Node types: shared endpoints, with dedicated clusters at scale.
- Protocols: JSON-RPC, WebSocket, plus data, token, NFT and wallet APIs, trace and debug.
- Best for: EVM and Solana teams that want rich data tooling and account abstraction.
- Notes: Bitcoin, Litecoin, Dogecoin and a few non-EVM chains are available via add-on products, not the core platform.
- Link: https://www.alchemy.com/

### Infura
- Networks: 40+, Ethereum-centric, part of the Consensys and MetaMask ecosystem.
- Free tier: 3 million daily credits at 500 credits per second, one API key.
- Node types: shared endpoints.
- Protocols: JSON-RPC, WebSocket, archive access, Gas API, IPFS.
- Best for: Ethereum-first apps that value a proven, widely integrated default.
- Notes: narrower chain list than multi-chain specialists; Solana is offered through its DIN service to select/paid accounts, not the free plan. Developer plan $50/month, Team $225/month.
- Link: https://www.infura.io/

### QuickNode
- Networks: 75+, with strong Bitcoin tooling alongside EVM and Solana.
- Free tier: one-month trial (10 million credits, 15 requests per second), not a permanent free plan.
- Node types: shared endpoints and dedicated clusters.
- Protocols: JSON-RPC, WebSocket, Streams, Solana gRPC, Bitcoin Ordinals and Runes APIs.
- Best for: performance-sensitive apps that want an add-on marketplace and real-time data.
- Notes: SOC 1/2 and ISO 27001 reports on request; paid plans from $49/month.
- Link: https://www.quicknode.com/

### Chainstack
- Networks: 70+ EVM and non-EVM chains.
- Free tier: permanent Developer plan, 3 million request units per month, WebSocket included.
- Node types: shared and dedicated.
- Protocols: JSON-RPC, WebSocket, archive on higher tiers.
- Best for: teams that want transparent, forecastable bills.
- Notes: one request equals one request unit, with no per-method multipliers; paid plans $49 to $990/month.
- Link: https://chainstack.com/

### Ankr
- Networks: 70+ chains, including Bitcoin, Solana and Polkadot alongside EVM networks.
- Free tier: free public RPC endpoints across many chains.
- Node types: shared; decentralized node infrastructure.
- Protocols: JSON-RPC, WebSocket.
- Best for: quick integration and decentralized access, with paid tiers for production throughput.
- Link: https://www.ankr.com/

### dRPC
- Networks: 95+ chains, including Bitcoin, Solana, TON and Cosmos alongside EVM networks.
- Free tier: free tier plus public endpoints.
- Node types: shared, routed across independent operators.
- Protocols: JSON-RPC, WebSocket.
- Best for: provider-level redundancy without wiring up several vendors yourself.
- Notes: decentralized routing with pay-as-you-go pricing.
- Link: https://drpc.org/

### Chain specialists and honorable mentions
- Helius — Solana-specialist RPC, gRPC and APIs. https://www.helius.dev/
- Blockdaemon — institutional node and staking infrastructure. https://www.blockdaemon.com/
- Tatum — unified SDK and API across 100+ chains. https://tatum.io/
- Moralis — data and indexing APIs for dApps. https://moralis.io/
- OnFinality — multi-chain infrastructure with strong Polkadot and Substrate support. https://onfinality.io/
- Grove (Pocket Network) — decentralized RPC through a relay network. https://www.grove.city/


## Feature and pricing matrix

| Provider   | Networks | Free tier                   | Node types          | Protocols                               | Billing model           | Paid from         |
|------------|----------|-----------------------------|---------------------|-----------------------------------------|-------------------------|-------------------|
| NOWNodes   | 120+     | 100,000 requests / month    | Shared + dedicated  | JSON-RPC, WSS, gRPC, webhooks, Data API | Subscription (requests) | see pricing       |
| GetBlock   | 130+     | Free key, no card           | Shared + dedicated  | JSON-RPC, WSS, streams, AML             | Compute units           | $49/mo            |
| Alchemy    | 100+     | 30M compute units / month   | Shared + clusters   | JSON-RPC, WSS, data/NFT/wallet APIs     | Compute units           | PAYG $0.525/1M CU |
| Infura     | 40+      | 3M credits / day            | Shared              | JSON-RPC, WSS, Gas API, IPFS            | Credits                 | $50/mo            |
| QuickNode  | 75+      | 1-month trial (10M credits) | Shared + clusters   | JSON-RPC, WSS, Streams, Solana gRPC     | API credits             | $49/mo            |
| Chainstack | 70+      | 3M request units / month    | Shared + dedicated  | JSON-RPC, WSS, archive                  | Request units (1:1)     | $49/mo            |
| Ankr       | 70+      | Free public endpoints       | Shared              | JSON-RPC, WSS                           | Pay-as-you-go           | pay-as-you-go     |
| dRPC       | 95+      | Free tier + public endpoints| Shared              | JSON-RPC, WSS                           | Pay-as-you-go           | pay-as-you-go     |


## Network coverage by family
A quick view of which chain families each provider covers. "add-on" = via a separate product; "limited" = restricted to select or paid accounts; "partial" = only some coins in the group.

| Chain family                        | NOWNodes | GetBlock | Alchemy | Infura  | QuickNode | Chainstack | Ankr | dRPC |
|-------------------------------------|----------|----------|---------|---------|-----------|------------|------|------|
| EVM Layer 1 & Layer 2               | yes      | yes      | yes     | yes     | yes       | yes        | yes  | yes  |
| Solana                              | yes      | yes      | yes     | limited | yes       | yes        | yes  | yes  |
| Bitcoin                             | yes      | yes      | add-on  | no      | yes       | no         | yes  | yes  |
| Other UTXO coins (LTC, DOGE, ZEC…)  | yes      | yes      | add-on  | no      | partial   | no         | no   | no   |
| Monero                              | yes      | yes      | no      | no      | no        | no         | no   | no   |
| Polkadot & Substrate                | yes      | yes      | no      | no      | no        | no         | yes  | no   |
| Tezos                               | yes      | yes      | no      | no      | no        | yes        | no   | no   |

Breadth is where multi-chain providers separate. Ankr and dRPC reach Bitcoin, but NOWNodes and GetBlock are the two that also cover the wider UTXO set and privacy coins. NOWNodes additionally runs Zcash, Dash, Decred, DigiByte, Ravencoin, Harmony, Algorand and Vechain, which developer-first platforms generally do not offer.


## RPC concepts in brief
- Shared vs dedicated node. A shared node serves many customers and is rate-limited; a dedicated node is private capacity with stable performance.
- Full vs archive node. A full node holds recent state; an archive node keeps complete history, which many balance and trace calls require.
- JSON-RPC, WebSocket, gRPC. JSON-RPC is the standard request/response API; WebSocket pushes live updates (new blocks, logs); gRPC is a faster binary transport used for high-volume Solana data.
- Compute units vs request units vs flat requests. Compute units charge more for heavier methods; a flat request-unit model counts every call the same, which is easier to forecast.
- Public vs private endpoint. Public endpoints are free and shared with no SLA; a private endpoint tied to an API key gives you dedicated limits, monitoring and support.


## How to evaluate a provider
- Test with the methods your app actually calls, not just a block-number ping.
- Confirm archive availability if you need historical state.
- Check the rate limit in requests per second, not only the monthly quota.
- Plan failover with a second provider or a decentralized network.
- Verify non-EVM and UTXO support if your roadmap needs it.
- Read the billing unit so a handful of heavy calls cannot blow the budget.


## Contributing
Pull requests are welcome. To add a provider, use the same card schema — Networks, Free tier, Node types, Protocols, Best for — with an official link, and update both matrices. Keep entries factual, avoid duplicates, and cite the provider's own pricing or docs page for any figure.


## Sources
- NOWNodes: https://nownodes.io/ and https://nownodes.io/pricing
- GetBlock: https://getblock.io/ and https://getblock.io/pricing/
- Alchemy: https://www.alchemy.com/pricing
- Infura: https://www.infura.io/pricing and https://docs.infura.io/
- QuickNode: https://www.quicknode.com/pricing
- Chainstack: https://chainstack.com/pricing/
- Ankr: https://www.ankr.com/
- dRPC: https://drpc.org/ and https://drpc.org/chainlist.md


---

Repository layout inspired by [awesome-list-rpc-nodes-providers](https://github.com/arddluma/awesome-list-rpc-nodes-providers). Provider descriptions and comparison figures are supplied by the source document; they have not been independently verified during project preparation. See [contribution guidelines](../.github/CONTRIBUTING.md) for updates.
