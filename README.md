# Awesome Tempo

A categorized directory of the Tempo payments-blockchain ecosystem, curated by [TempoAtlas](https://tempoatlas.net). Project descriptions and links are included below so you can explore the ecosystem without leaving this README for another directory.

**Coverage:** all 139 entries in the [TempoAtlas ecosystem directory](https://tempoatlas.net/ecosystem), captured on **14 September 2026**. This includes projects, protocol components, tokens, infrastructure, companies, investors and people—not 139 independently verified live integrations.

**Independent:** not affiliated with Tempo, Stripe or Paradigm. Inclusion is not an endorsement, security audit or investment advice.

## How to read this list

- Descriptions, categories and status labels are adapted from the source directory. They are a snapshot, not a fresh verification of every integration or affiliation.
- `active` describes the directory entry; it does **not** necessarily mean that its Tempo integration is live. Other reported states include `mainnet`, `beta` and `announced`. Check the project’s own documentation before using a service.
- Project names link directly to the official website, documentation, repository or public profile supplied by the source. If no such URL was supplied, the entry remains unlinked rather than using a guessed address.
- Some categories include related infrastructure or organizations rather than standalone apps. For example, “Stablecoins and tokens” includes issuers and non-stablecoin assets such as cbBTC.

## Contents

- [Protocol and core](#protocol-and-core)
- [Stablecoins and tokens](#stablecoins-and-tokens)
- [DeFi](#defi)
- [Payments and fintech](#payments-and-fintech)
- [On- and off-ramps](#on--and-off-ramps)
- [Wallets and custody](#wallets-and-custody)
- [RPC and node infrastructure](#rpc-and-node-infrastructure)
- [Explorers and verification](#explorers-and-verification)
- [Indexers and data](#indexers-and-data)
- [Bridges and interoperability](#bridges-and-interoperability)
- [Oracles](#oracles)
- [Developer tools](#developer-tools)
- [Compliance and risk](#compliance-and-risk)
- [Companies and partners](#companies-and-partners)
- [Investors](#investors)
- [Validator infrastructure](#validator-infrastructure)
- [People](#people)
- [Network and developer resources](#network-and-developer-resources)
- [Sources and updates](#sources-and-updates)
- [Contributing](#contributing)

## Protocol and core

7 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Machine Payments Protocol (MPP)](https://stripe.com/blog/machine-payments-protocol) | An open standard for machine and AI-agent payments, co-authored by Stripe and Tempo. | `mainnet` |
| [Reth](https://reth.rs/) | The Rust EVM execution client Tempo runs on. | `mainnet` |
| **Simplex BFT** | Tempo's Byzantine fault-tolerant consensus, implemented by Commonware. Official URL not supplied. | `mainnet` |
| [Stablecoin DEX](https://docs.tempo.xyz/) | Tempo's enshrined, orderbook-based exchange for same-asset stablecoin swaps. | `mainnet` |
| [Tempo](https://tempo.xyz/) | The payments-first Layer 1 blockchain, incubated by Stripe and Paradigm. [Docs](https://docs.tempo.xyz/) · [App](https://wallet.tempo.xyz/) · [GitHub](https://github.com/tempoxyz). | `mainnet` |
| [Tempo Zones](https://docs.tempo.xyz/) | Private execution environments connected to Tempo Mainnet. | `beta` |
| [TIP-20](https://docs.tempo.xyz/) | Tempo's payment-oriented token standard, an ERC-20 superset for stablecoins. | `mainnet` |

## Stablecoins and tokens

10 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Agora](https://agora.finance/) | AUSD, an enterprise-first US-dollar stablecoin. | `active` |
| [AllUnity](https://allunity.com/) | EURAU, a BaFin-regulated euro stablecoin. | `announced` |
| [Brale](https://brale.xyz/) | Stablecoin issuance-as-a-service. | `active` |
| [Cap](https://cap.app/) | A digital dollar and financial-guarantee market. | `active` |
| **cbBTC** | Coinbase wrapped BTC, bridged to Tempo via Chainlink CCIP. Official URL not supplied. | `mainnet` |
| **DLUSD** | Deel's dollar-backed stablecoin for contractor balances, with Tempo as exclusive chain partner. Official URL not supplied. | `mainnet` |
| [Frax](https://frax.finance/) | frxUSD stablecoin infrastructure; an early TIP-20 adopter. | `active` |
| [pathUSD](https://docs.tempo.xyz/quickstart/predeployed-contracts) | Tempo's first deployed and predeployed stablecoin. | `mainnet` |
| [USDC](https://circle.com/usdc) | Circle's US-dollar stablecoin, supported on Tempo. | `active` |
| **USDT0** | Native USDT on Tempo via Kraken. Official URL not supplied. | `mainnet` |

## DeFi

2 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Morpho](https://morpho.org/) | Lending and borrowing protocol listed in the Tempo DeFi ecosystem. | `mainnet` |
| [Uniswap](https://uniswap.org/) | On-chain decentralized exchange listed in the Tempo ecosystem. | `active` |

## Payments and fintech

15 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Agant](https://agant.com/) | Institutional money access infrastructure. | `active` |
| [Bridge](https://bridge.xyz/) | Stablecoin orchestration infrastructure, acquired by Stripe. | `active` |
| [Conduit Pay](https://conduit.financial/) | Unified fiat and stablecoin payment API. | `active` |
| [Crossmint](https://crossmint.com/) | Wallets, stablecoins, and agentic-commerce APIs. | `active` |
| [Daimo](https://daimo.com/) | Stablecoin payments app and pay protocol. | `active` |
| [Due](https://due.network/) | Stablecoin and local-rail API in 80+ countries. | `active` |
| [Lean](https://leantech.me/) | Fintech infrastructure for the UAE and KSA. | `active` |
| [Manteca](https://manteca.dev/) | All-in-one API: payments, crypto, FX, brokerage. | `active` |
| [MeshPay](https://meshpay.io/) | Accept crypto from any wallet, settle in stablecoins. | `active` |
| [OpenFX](https://openfx.com/) | Real-time 24/7 FX liquidity. | `active` |
| [Splits](https://splits.org/) | Treasury, revenue, and expense management. | `active` |
| [Sponge](https://sponge.money/) | Infrastructure for AI agents to hold and spend money. | `active` |
| [Thunes](https://thunes.com/) | Cross-border payments across 130+ countries. | `active` |
| [Toku](https://toku.com/) | Connects payroll platforms to stablecoin rails. | `active` |
| [Ubyx](https://ubyx.xyz/) | Par-value redemption of stablecoins and tokenized deposits. | `active` |

## On- and off-ramps

10 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| **Avenia** | Stablecoin on/off-ramp infrastructure. [Official ecosystem listing](https://tempo.xyz/ecosystem); project URL not supplied. | `active` |
| [Banxa](https://banxa.com/) | Compliant fiat on/off-ramp. | `active` |
| [Blockradar](https://blockradar.co/) | Wallet and ramp infrastructure for builders. | `active` |
| [Coinflow](https://coinflow.cash/) | Payments and payouts for apps. | `active` |
| [Cybrid](https://cybrid.xyz/) | Embedded crypto and stablecoin banking API. | `active` |
| [El Dorado](https://eldorado.io/) | Emerging-market financial access. | `active` |
| [Fonbnk](https://fonbnk.com/) | Africa-focused stablecoin on-ramp. | `active` |
| [Mesh](https://meshconnect.com/) | Connectivity for crypto accounts and payments. | `active` |
| [Transak](https://transak.com/) | Fiat-to-crypto on-ramp infrastructure. | `active` |
| [Yellow Card](https://yellowcard.io/) | Pan-African crypto payments and on-ramp. | `active` |

## Wallets and custody

15 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [BitGo](https://bitgo.com/) | Regulated institutional custody and infrastructure. | `active` |
| [DFNS](https://dfns.co/) | Wallet-as-a-service with policy controls. | `active` |
| [Dynamic](https://dynamic.xyz/) | Embedded wallets and auth for apps. | `active` |
| [Fireblocks](https://fireblocks.com/) | Institutional digital-asset custody and operations. | `active` |
| [MetaMask](https://metamask.io/) | Self-custody wallet for EVM networks. | `active` |
| [OKX Wallet](https://okx.com/web3) | Exchange-grade self-custody wallet across many chains. | `active` |
| [Para](https://getpara.com/) | Embedded MPC wallets across apps. | `active` |
| [Phantom](https://phantom.app/) | Multichain consumer wallet, now spanning EVM chains. | `active` |
| [Privy](https://privy.io/) | Embedded wallets and onboarding; acquired by Stripe. | `active` |
| [Rabby Wallet](https://rabby.io/) | Power-user EVM wallet with pre-transaction risk checks. | `active` |
| [Safe](https://safe.global/) | The standard smart-account (multisig) for EVM treasuries. | `active` |
| [Turnkey](https://turnkey.com/) | Secure key management as an API. | `active` |
| [Utila](https://utila.io/) | Operational wallet platform for businesses. | `active` |
| [Zerion](https://zerion.io/) | Wallet and portfolio app with its own data API. | `active` |
| [ZeroDev](https://zerodev.app/) | Account-abstraction toolkit and smart-account infrastructure. | `active` |

## RPC and node infrastructure

6 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Alchemy](https://alchemy.com/) | Developer platform and RPC for EVM chains. | `active` |
| [Blockdaemon](https://blockdaemon.com/) | Node, staking, and wallet infrastructure. | `active` |
| [Chainstack](https://chainstack.com/) | SOC 2-certified RPC and node services. | `active` |
| [Conduit](https://conduit.xyz/) | Rollup and node infrastructure provider. | `active` |
| [dRPC](https://drpc.org/) | Decentralized RPC with smart routing. | `active` |
| [QuickNode](https://quicknode.com/) | Global RPC and node infrastructure. | `active` |

## Explorers and verification

1 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Tempo Explorer](https://explore.tempo.xyz/) | Tempo's official block explorer. | `mainnet` |

## Indexers and data

7 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Allium](https://allium.so/) | Enterprise blockchain data and analytics. | `active` |
| [Artemis](https://artemis.xyz/) | Cross-chain fundamental metrics. | `active` |
| [Dune](https://dune.com/) | SQL-queryable on-chain analytics and dashboards. | `active` |
| [Goldsky](https://goldsky.com/) | Real-time indexing and data streaming. | `active` |
| [SonarX](https://sonarx.com/) | Blockchain data for analysts and institutions. | `active` |
| [SQD](https://sqd.dev/) | Decentralized data lake and indexing (Subsquid). | `active` |
| [TIDX](https://github.com/tempoxyz/tidx) | Tempo's own hybrid Postgres + ClickHouse indexer. | `active` |

## Bridges and interoperability

7 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Across](https://across.to/) | Fast, capital-efficient cross-chain bridging. | `active` |
| [Bungee](https://bungee.exchange/) | Bridge aggregation by Socket. | `active` |
| [LayerZero](https://layerzero.network/) | Omnichain messaging; rolling out TIP-20 support. | `active` |
| [LI.FI](https://li.fi/) | Cross-chain bridge and DEX aggregation. | `active` |
| [Relay](https://relay.link/) | Instant, low-cost cross-chain execution. | `active` |
| [Rhino.fi](https://rhino.fi/) | Multichain bridging and DeFi access. | `active` |
| [Squid](https://squidrouter.com/) | Cross-chain swaps and liquidity routing. | `active` |

## Oracles

3 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Chainlink](https://chain.link/) | Oracles and CCIP cross-chain interoperability. | `active` |
| [Chronicle](https://chroniclelabs.org/) | Verifiable oracles with origins at MakerDAO. | `active` |
| [RedStone](https://redstone.finance/) | Modular oracles powering Tempo's DeFi layer. | `active` |

## Developer tools

4 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [0x](https://0x.org/) | Institutional DEX and swap aggregation. | `active` |
| [Commonware](https://commonware.xyz/) | The BFT infrastructure powering Tempo's consensus. | `active` |
| [Tempo Foundry](https://github.com/tempoxyz/tempo-foundry) | A Foundry fork with Tempo payment features. | `active` |
| [Tenderly](https://tenderly.co/) | Debugging, simulation, and node infrastructure. | `active` |

## Compliance and risk

8 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Blockaid](https://blockaid.io/) | On-chain security and transaction screening. | `active` |
| [Chainalysis](https://chainalysis.com/) | Blockchain analytics and compliance. | `active` |
| [Elliptic](https://elliptic.co/) | Crypto risk and compliance screening. | `active` |
| [Hypernative](https://hypernative.io/) | Real-time Web3 threat prevention. | `active` |
| [Range](https://range.org/) | Security and compliance for cross-chain. | `active` |
| [Sardine](https://sardine.ai/) | Fraud prevention and instant settlement. | `active` |
| [TRES](https://tres.finance/) | Crypto accounting and treasury data. | `active` |
| [TRM Labs](https://trmlabs.com/) | Blockchain intelligence for risk and compliance. | `active` |

## Companies and partners

33 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Anthropic](https://anthropic.com/) | AI lab and Tempo design partner. | `active` |
| **ARQ** | Payments partner in the Tempo ecosystem. Official URL not supplied. | `active` |
| [Brex](https://brex.com/) | Corporate cards and spend; Tempo partner. | `active` |
| **Coastal** | Banking partner in the Tempo ecosystem. Official URL not supplied. | `active` |
| [Coupang](https://coupang.com/) | Korean commerce giant and Tempo design partner. | `active` |
| [Deel](https://deel.com/) | Global payroll platform; issuer of DLUSD and a Tempo payments partner. | `active` |
| [Deutsche Bank](https://db.com/) | Global bank and Tempo design partner. | `active` |
| [DoorDash](https://doordash.com/) | Marketplace bringing stablecoin payouts to gig workers. | `active` |
| **Felix** | Remittance app using stablecoin rails. Official URL not supplied. | `active` |
| [Flutterwave](https://flutterwave.com/) | African payments giant using Tempo as a settlement layer. | `active` |
| [Gusto](https://gusto.com/) | Payroll and benefits; Tempo partner. | `active` |
| [Kalshi](https://kalshi.com/) | Regulated prediction market; Tempo partner. | `active` |
| **Karta** | Payments product in the Tempo ecosystem. Official URL not supplied. | `active` |
| [Klarna](https://klarna.com/) | Global BNPL and payments; Tempo partner. | `active` |
| [Kraken](https://kraken.com/) | Exchange offering native USDT0 and USDC.e on Tempo. | `active` |
| [Lead Bank](https://lead.bank/) | Chartered bank and Tempo design partner. | `active` |
| [Mastercard](https://mastercard.com/) | Global card network settling stablecoins on Tempo. | `active` |
| [Mercury](https://mercury.com/) | Startup banking and a Tempo design partner. | `active` |
| [MoneyGram](https://moneygram.com/) | Global remittance operator and Tempo's first remittance validator. | `active` |
| [Nubank](https://nubank.com.br/) | LatAm digital bank and Tempo design partner. | `active` |
| [OKX](https://okx.com/) | Global exchange and Web3 platform in the Tempo ecosystem. | `active` |
| [OpenAI](https://openai.com/) | AI lab and Tempo design partner. | `active` |
| [Payoneer](https://payoneer.com/) | Cross-border payouts; Tempo partner. | `active` |
| [Persona](https://withpersona.com/) | Identity verification; Tempo partner. | `active` |
| [Ramp](https://ramp.com/) | Corporate finance automation; Tempo partner. | `active` |
| [RedotPay](https://redotpay.com/) | Crypto card and payments app listed as an MPP participant. | `active` |
| [Revolut](https://revolut.com/) | Global fintech super-app and Tempo design partner. | `active` |
| [Shopify](https://shopify.com/) | Commerce platform and Tempo design partner. | `active` |
| [Standard Chartered](https://sc.com/) | Global bank; its Zodia unit is a Tempo validator. | `active` |
| [Stripe](https://stripe.com/) | Co-incubator of Tempo, co-author of MPP, and an anchor validator. | `active` |
| [UBS](https://ubs.com/) | Global wealth manager in the Tempo partner set. | `active` |
| [Visa](https://visa.com/) | Design partner and the first external corporate validator on Tempo. | `active` |
| [Zodia Custody](https://zodia.io/) | Institutional custodian and early Tempo validator. | `active` |

## Investors

4 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| **Greenoaks** | Co-lead of Tempo's Series A (reported). Official URL not supplied. | `active` |
| [Paradigm](https://paradigm.xyz/) | Crypto-native VC; co-incubator of Tempo. | `active` |
| [Sequoia](https://sequoiacap.com/) | Reported Series A participant in Tempo. | `active` |
| [Thrive Capital](https://thrivecap.com/) | Co-lead of Tempo's $500M Series A (reported). | `active` |

## Validator infrastructure

2 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Figment](https://figment.io/) | Institutional staking and validator operations. | `active` |
| [Luganodes](https://luganodes.com/) | Institutional-grade validator infrastructure. | `active` |

## People

5 entries.

| Project / entity | Description | Reported status |
| --- | --- | --- |
| [Dan Romero](https://x.com/dwr) | Farcaster co-founder; joined Tempo in February 2026. | `active` |
| [Matt Huang](https://x.com/matthuang) | CEO of Tempo; co-founder and Managing Partner of Paradigm. | `active` |
| **Patrick Collison** | CEO of Stripe, a key Tempo backer. Official URL not supplied. | `active` |
| **Patrick O'Grady** | Founder of Commonware (Simplex BFT). Official URL not supplied. | `active` |
| [Varun Srinivasan](https://x.com/v) | Farcaster co-founder; joined Tempo in February 2026. | `active` |

## Network and developer resources

- [Tempo documentation](https://docs.tempo.xyz/) — network connection details, protocol concepts and development guides.
- [Tempo GitHub](https://github.com/tempoxyz) — official repositories.
- [Contract verification](https://contracts.tempo.xyz/) — contract-verification tooling.
- [Web wallet](https://wallet.tempo.xyz/) — Tempo’s web wallet.
- [Network status](https://status.tempo.xyz/) — service status.
- [Testnet faucet instructions](https://docs.tempo.xyz/quickstart/faucet) — official test-token instructions.
- [Tempo blog](https://tempo.xyz/blog) — official announcements.

Use the current official documentation for chain IDs and RPC endpoints; this README deliberately does not freeze network configuration.

## Sources and updates

The entries above are drawn from TempoAtlas’s published directory and individual profiles. Direct external links were transcribed from those profiles; their presence is not an independent availability, safety or integration check. See the [TempoAtlas methodology](https://tempoatlas.net/methodology) for the source site’s evidence and confidence model.

Snapshot date: **14 September 2026**. This is a manually maintained README, not an automatic feed. Profile review dates may differ from the snapshot date. Status, integration scope and service availability can change.

## Contributing

Open an issue or pull request with the entry name, category, a concise neutral description, an official project URL and at least one primary-source reference for its Tempo relationship. Include the date checked and distinguish live, testnet-only, planned and uncertain integrations.

For corrections, identify the existing entry and explain the evidence. Keep one entry per entity, avoid referral links and unsupported performance or affiliation claims, and preserve attribution and licensing when reusing material. Never submit credentials or private information.
