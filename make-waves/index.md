# Make Waves — Builder Opportunities

A registry of **74 market opportunities** on the XRP Ledger, sourced from the
[XRPL Builder Opportunities registry](https://xrpl-builder.vercel.app/en/opportunities)
(PWG, ATKA, ecosystem, YC, and founder interviews).

Unlike the [Hackathon](../hackathon/index.md) and [Platform](../platform/index.md)
lists — which are scoped, demoable builds — these are **market gaps**: spaces
where the ecosystem needs something built. Each is tagged by:

- **Type** — `APP` (for users) or `TOOL` (for builders)
- **Tier** — `HIGH` (ecosystem-wide multiplier), `MEDIUM` (community/regulatory demand), `LOW` (specific vertical or novelty)

> Imported as-is from the source registry. Overlaps with existing Hackathon/Platform
> ideas are flagged in [`../ideas.json`](../ideas.json) (`overlaps_with`) and are
> **not yet deduplicated**. Source anomalies are preserved verbatim: ID `OPP-016`
> appears twice in the source, and `OPP-026` is absent.

---

## 01. Wallets

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-001 | Cross-Device Session Continuity | TOOL | HIGH | Library enabling seamless wallet sessions across devices without re-authentication |
| OPP-002 | Institutional Multisig Wallet | APP | LOW | Safe-equivalent full UI for institutional treasury on XRPL |
| OPP-003 | Smart Contract Wallet on EVM | APP | MEDIUM | ERC-4337 account abstraction wallet for EVM Sidechain |
| OPP-004 | Unified Cross-Chain Wallet SDK | TOOL | LOW | Single SDK supporting XRPL native + EVM Sidechain signing |
| OPP-005 | Treasury wallet B2B XRPL-native | APP | MEDIUM | Coinshift/Utopia Labs equivalent for XRP/RLUSD business workflows |
| OPP-006 | KYC reusable cross-app | APP | MEDIUM | User identity passport managing reusable KYC across apps via XLS-70 |
| OPP-007 | Hardware wallet integration | TOOL | LOW | Ledger/Trezor signing support library for XRPL wallets |
| OPP-008 | DeFi-first consumer wallet | APP | MEDIUM | Consumer wallet with optimized DeFi UX (2-click yield, visible positions) |
| OPP-009 | XRPL DeFi position aggregator | APP | LOW | Cross-protocol dashboard like DeBank for XRPL + EVM positions |
| OPP-010 | Socials Onboarding for XRPL | TOOL | MEDIUM | Social login (Google/Twitter/Apple) wallet tool eliminating seed-phrase friction |
| OPP-068 | Account Abstraction layer | TOOL | MEDIUM | Web3Auth hybrid combining 3rd-party auth + wallet creation + sponsored fees |
| OPP-069 | XRPL "Jupiter-style" super-app | APP | MEDIUM | Unified interface combining swap, lending, portfolio, predictions |

## 02. B2B

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-011 | Institutional Data Emission Adapter | TOOL | HIGH | ISIN/CFI/LEI/FIX/IFRS format adapters for institutional system integration |
| OPP-012 | Stablecoin Accounting Export | TOOL | MEDIUM | QuickBooks/Xero/IFRS-compatible export library for RLUSD/USDC |
| OPP-013 | Multi-Flow Institutional Access Control | TOOL | MEDIUM | Library composing Permissioned Domains + Credentials for institutional flows |
| OPP-014 | On-chain accounting + reporting | APP | MEDIUM | Full accounting/reporting platform (P&L, balance sheet, audit trails, multi-currency) |
| OPP-015 | Streaming payroll for DAOs | APP | LOW | Continuous stream payments for DAO/freelancer payroll on XRPL |
| OPP-016 | Regional POS / merchant tooling | APP | MEDIUM | Retail terminals for emerging markets with EU/MiCA compliance |
| OPP-017 | B2B Stablecoin FX desk | APP | HIGH | API-first FX corridor routing multi-hop stablecoin trades via native DEX |
| OPP-018 | Monitoring & B2B alerting | APP | MEDIUM | Tenderly-equivalent B2B alerting product with UI for production XRPL ops |
| OPP-019 | XRPL-native dApp analytics | APP | HIGH | DappRadar + Dune combined: rankings + custom dashboards for XRPL |
| OPP-070 | XRPL card issuance frontend | APP | HIGH | Dev-friendly wrapper around card-issuance API plugged into XRPL |
| OPP-071 | XRPL stablecoin on-ramp aggregator | APP | HIGH | UI to buy USDC/RLUSD directly via fiat, aggregating multiple providers |
| OPP-016 | POAP / Event Attendance NFT app | APP | MEDIUM | Proof-of-attendance NFT framework for conferences and events (duplicate ID in source) |
| OPP-027 | Dynamic NFT framework | APP | MEDIUM | dNFT ticketing/credentials/loyalty leveraging URI-update post-mint |

## 03. RWA & Stables

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-020 | Physical-to-Digital Binding (EU DPP) | TOOL | LOW | Regulatory-compliant digital product passport binding for 2027 deadline |
| OPP-021 | Yield-Bearing Stablecoin | APP | LOW | T-bill-backed stablecoin like USDe on XRPL |
| OPP-022 | RWA Issuance Studio EU/MiCA | APP | MEDIUM | Turnkey tokenization: MPT + DID + cap table for MiCA compliance |
| OPP-023 | Mid-market corporate bonds | APP | MEDIUM | On-chain bond marketplace for $10M–$500M revenue companies |
| OPP-024 | RWA structuring firm (AI service) | APP | MEDIUM | AI agent + lawyer service handling RWA tokenization structuring |
| OPP-025 | Compliance-native consumer payments | APP | HIGH | Merchant checkout + billing + remittance combining Credentials + RLUSD |

## 04. DeFi

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-028 | Vault Wrapper Pattern Library | TOOL | HIGH | XLS-65 wrapper library enabling rapid vault product deployment |
| OPP-029 | Risk-Signal Aggregation from MPT | TOOL | LOW | Extract Kennedy reassurance signals from MPT trading data |
| OPP-030 | Lending Protocol on EVM | APP | HIGH | Morpho-style lending protocol for EVM Sidechain |
| OPP-031 | Uncollateralized Lending Interface | APP | MEDIUM | UI for XLS-66 unsecured credit enabling borrower/lender interaction |
| OPP-032 | Compliant Credit Vault | APP | MEDIUM | Agent-curator institutional credit vault with attestation-based KYC |
| OPP-033 | Native yield aggregator | APP | MEDIUM | Yearn-equivalent routing cross-protocol yield on XRPL |
| OPP-034 | Lending front-end on Single Asset Vault | APP | HIGH | Lend/borrow UI + yield dashboard NOW on XLS-65 (pre-XLS-66) |
| OPP-035 | Non-USD Stablecoin DeFi Rails | TOOL | LOW | EUR/BRL/SGD/AUD rails integrating into lending, AMMs, vaults |
| OPP-036 | Restaking Protocol for XRP | APP | HIGH | Babylon-fork allowing $110B+ XRP cap productive redeployment |
| OPP-037 | Synthetic Assets / CDP Protocol | APP | MEDIUM | Gold/stocks/forex synthetic assets like Synthetix on EVM |
| OPP-038 | Perpetual DEX | APP | MEDIUM | vAMM or order-book derivatives protocol (highest-volume DeFi category) |
| OPP-039 | Decentralized Insurance Protocol | APP | MEDIUM | Smart contract insurance for institutional DeFi adoption |
| OPP-040 | Prediction markets infrastructure | TOOL | MEDIUM | Engine layer (oracle resolution, settlement) like Polymarket |
| OPP-041 | Prediction markets dApps | APP | MEDIUM | Consumer-facing prediction apps for politics/sports/crypto |
| OPP-042 | DeFi underwriting (AI service) | APP | LOW | AI agent pricing DeFi risk for insurance protocols |
| OPP-043 | Liquid Staked XRP (LST) | APP | HIGH | Lido-equivalent enabling stXRP composition in DeFi |
| OPP-044 | Yield tokenization platform | APP | MEDIUM | Pendle-equivalent splitting yield-bearing assets into PT/YT tokens |

## 05. Builder Primitives

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-045 | Chunked Data + On-Chain Anchoring | TOOL | LOW | Standard pattern for IPFS/S3 + on-chain anchoring of large data |
| OPP-046 | Gaming utility-NFT framework | TOOL | LOW | Play-to-earn + cross-game asset interop framework for game devs |
| OPP-047 | Pre-Deployed Testnet Infrastructure | TOOL | HIGH | SurfPool-equivalent local node + pre-deployed contract sandbox |
| OPP-048 | Vendor-Neutral Oracle/Bridge/Ramp | TOOL | LOW | Zero-code-change library for swapping provider implementations |
| OPP-049 | CeDeFi Yield Integration SDK | TOOL | MEDIUM | SDK routing 60%+ CEX-held XRP into XRPL DeFi yield |
| OPP-050 | P-256/secp256r1 Signing | TOOL | MEDIUM | XLS proposal supporting Apple Enclave + WebAuthn + HSM keys |
| OPP-051 | Data marketplace · oracle aggregator | TOOL | LOW | Multi-source feed marketplace connecting data sellers and buyers |
| OPP-052 | DEX + AMM liquidity aggregator SDK | TOOL | HIGH | SDK routing across native order book + AMM with slippage optimization |
| OPP-053 | XRPL Transaction Indexer | TOOL | MEDIUM | TheGraph-equivalent backend indexer powering analytics and dApps |
| OPP-054 | Pluggable Proof Primitives Library | TOOL | LOW | Composable framework (hash, signature, ZK, custom schemes) |
| OPP-055 | Proof of Humanity / KYA-NFT | TOOL | MEDIUM | Gitcoin Passport/Worldcoin parallel: human verification NFT + score |
| OPP-072 | XRPL scaffolding extension | TOOL | MEDIUM | Scaffolder with plugin system for RWA/DeFi/NFT frameworks |
| OPP-073 | Builder Blocks Catalog | TOOL | LOW | Meta-documentation indexing available APIs, wallets, ramps |
| OPP-074 | Dev utilities pack | TOOL | LOW | Airdrop tool, signing wrapper, glacier API for cold storage |

## 06. AI Agents

| ID | Title | Type | Tier | Description |
|---|---|---|---|---|
| OPP-056 | AgentPay — x402 + XRPL settlement | TOOL | LOW | AI agent payment facilitator bridging x402 + XRPL for agent economy |
| OPP-057 | AI-Native Compliance Ops | APP | MEDIUM | AI + lawyer service delivering compliance-as-a-service at high margin |
| OPP-058 | AI-Native Treasury Ops | APP | LOW | AI service automating RLUSD management, rebalancing, yield optimization |
| OPP-059 | AI-Native Restaking Manager | APP | LOW | AI yield optimizer auto-rebalancing across restaking protocols |
| OPP-060 | Onchain Reputation for AI Agents | TOOL | LOW | KYA primitive enabling agents to build verifiable track records |
| OPP-061 | Market-making-as-a-Service | APP | MEDIUM | AI agent providing token launch liquidity at high margin |
| OPP-062 | Community-ops-as-a-Service | APP | MEDIUM | AI agent managing Discord, Twitter, grants ops 24/7 |
| OPP-063 | Dispute resolution & recovery | APP | LOW | AI-handled claims, refunds, recovery for on-chain disputes |
| OPP-064 | AI trading agents | APP | MEDIUM | Pre-built (DCA, momentum) or custom alpha trading strategies |
| OPP-065 | Agent treasury + wallet for AI | TOOL | LOW | Programmatic wallet with guardrails (spending limits, multisig) |
| OPP-066 | Audit & continuous monitoring | APP | LOW | AI service continuously auditing client protocols at high margin |
| OPP-067 | AI agent credit card with RLUSD | APP | LOW | OpenClaw-equivalent credit-card primitive for agent spending |

---

**Tier distribution:** HIGH (multiplier / ecosystem-wide) · MEDIUM (community & regulatory demand) · LOW (specific verticals / novelty).

**Source tags:** PWG-1/2/3/4, ATKA, ECO, YC, and founder interviews (djason, xavier, florian, florence, guillaume, thomas, kevin).

Contribute on [GitHub](https://github.com/XRPL-Commons/community-ideas/blob/main/make-waves/index.md).
