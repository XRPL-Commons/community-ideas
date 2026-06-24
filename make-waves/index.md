# Make Waves — Builder Opportunities

Unlike the [Hackathon](../hackathon/index.md) and [Platform](../platform/index.md) lists — which are scoped, demoable builds — these are **market gaps**: spaces where the ecosystem needs something built. Each is tagged by **type** (`APP` for users · `TOOL` for builders) and **tier** (`HIGH` ecosystem-wide multiplier · `MEDIUM` community/regulatory demand · `LOW` specific vertical or novelty), along with its source registry id.

> Imported as-is from the source registry. Overlaps with existing Hackathon/Platform ideas are flagged in [`../ideas.json`](../ideas.json) (`overlaps_with`) and are **not yet deduplicated**. Source anomalies are preserved verbatim: ID `OPP-016` appears twice in the source, and `OPP-026` is absent.

---

## Wallets

1. **Cross-Device Session Continuity**
   Library enabling seamless wallet sessions across devices without re-authentication.
   `TOOL`, `HIGH`, `OPP-001`

2. **Institutional Multisig Wallet**
   Safe-equivalent full UI for institutional treasury on XRPL.
   `APP`, `LOW`, `OPP-002`

3. **Smart Contract Wallet on EVM**
   ERC-4337 account abstraction wallet for the EVM Sidechain.
   `APP`, `MEDIUM`, `OPP-003`

4. **Unified Cross-Chain Wallet SDK**
   Single SDK supporting XRPL native + EVM Sidechain signing.
   `TOOL`, `LOW`, `OPP-004`

5. **Treasury Wallet B2B XRPL-native**
   Coinshift/Utopia Labs equivalent for XRP/RLUSD business workflows.
   `APP`, `MEDIUM`, `OPP-005`

6. **KYC Reusable Cross-App**
   User identity passport managing reusable KYC across apps via XLS-70.
   `APP`, `MEDIUM`, `OPP-006`

7. **Hardware Wallet Integration**
   Ledger/Trezor signing support library for XRPL wallets.
   `TOOL`, `LOW`, `OPP-007`

8. **DeFi-First Consumer Wallet**
   Consumer wallet with optimized DeFi UX (2-click yield, visible positions).
   `APP`, `MEDIUM`, `OPP-008`

9. **XRPL DeFi Position Aggregator**
   Cross-protocol dashboard like DeBank for XRPL + EVM positions.
   `APP`, `LOW`, `OPP-009`

10. **Socials Onboarding for XRPL**
    Social login (Google/Twitter/Apple) wallet tool eliminating seed-phrase friction.
    `TOOL`, `MEDIUM`, `OPP-010`

11. **Account Abstraction Layer**
    Web3Auth hybrid combining 3rd-party auth + wallet creation + sponsored fees.
    `TOOL`, `MEDIUM`, `OPP-068`

12. **XRPL "Jupiter-Style" Super-App**
    Unified interface combining swap, lending, portfolio, and predictions.
    `APP`, `MEDIUM`, `OPP-069`

## B2B

13. **Institutional Data Emission Adapter**
    ISIN/CFI/LEI/FIX/IFRS format adapters for institutional system integration.
    `TOOL`, `HIGH`, `OPP-011`

14. **Stablecoin Accounting Export**
    QuickBooks/Xero/IFRS-compatible export library for RLUSD/USDC.
    `TOOL`, `MEDIUM`, `OPP-012`

15. **Multi-Flow Institutional Access Control**
    Library composing Permissioned Domains + Credentials for institutional flows.
    `TOOL`, `MEDIUM`, `OPP-013`

16. **On-Chain Accounting + Reporting**
    Full accounting/reporting platform (P&L, balance sheet, audit trails, multi-currency).
    `APP`, `MEDIUM`, `OPP-014`

17. **Streaming Payroll for DAOs**
    Continuous stream payments for DAO/freelancer payroll on XRPL.
    `APP`, `LOW`, `OPP-015`

18. **Regional POS / Merchant Tooling**
    Retail terminals for emerging markets with EU/MiCA compliance.
    `APP`, `MEDIUM`, `OPP-016`

19. **B2B Stablecoin FX Desk**
    API-first FX corridor routing multi-hop stablecoin trades via the native DEX.
    `APP`, `HIGH`, `OPP-017`

20. **Monitoring & B2B Alerting**
    Tenderly-equivalent B2B alerting product with UI for production XRPL ops.
    `APP`, `MEDIUM`, `OPP-018`

21. **XRPL-Native dApp Analytics**
    DappRadar + Dune combined: rankings + custom dashboards for XRPL.
    `APP`, `HIGH`, `OPP-019`

22. **XRPL Card Issuance Frontend**
    Dev-friendly wrapper around a card-issuance API plugged into XRPL.
    `APP`, `HIGH`, `OPP-070`

23. **XRPL Stablecoin On-Ramp Aggregator**
    UI to buy USDC/RLUSD directly via fiat, aggregating multiple providers.
    `APP`, `HIGH`, `OPP-071`

24. **POAP / Event Attendance NFT App**
    Proof-of-attendance NFT framework for conferences and events. *(Duplicate ID `OPP-016` in source.)*
    `APP`, `MEDIUM`, `OPP-016`

25. **Dynamic NFT Framework**
    dNFT ticketing/credentials/loyalty leveraging URI-update post-mint.
    `APP`, `MEDIUM`, `OPP-027`

## RWA & Stables

26. **Physical-to-Digital Binding (EU DPP)**
    Regulatory-compliant digital product passport binding for the 2027 deadline.
    `TOOL`, `LOW`, `OPP-020`

27. **Yield-Bearing Stablecoin**
    T-bill-backed stablecoin like USDe on XRPL.
    `APP`, `LOW`, `OPP-021`

28. **RWA Issuance Studio EU/MiCA**
    Turnkey tokenization: MPT + DID + cap table for MiCA compliance.
    `APP`, `MEDIUM`, `OPP-022`

29. **Mid-Market Corporate Bonds**
    On-chain bond marketplace for $10M–$500M revenue companies.
    `APP`, `MEDIUM`, `OPP-023`

30. **RWA Structuring Firm (AI Service)**
    AI agent + lawyer service handling RWA tokenization structuring.
    `APP`, `MEDIUM`, `OPP-024`

31. **Compliance-Native Consumer Payments**
    Merchant checkout + billing + remittance combining Credentials + RLUSD.
    `APP`, `HIGH`, `OPP-025`

## DeFi

32. **Vault Wrapper Pattern Library**
    XLS-65 wrapper library enabling rapid vault product deployment.
    `TOOL`, `HIGH`, `OPP-028`

33. **Risk-Signal Aggregation from MPT**
    Extract Kennedy reassurance signals from MPT trading data.
    `TOOL`, `LOW`, `OPP-029`

34. **Lending Protocol on EVM**
    Morpho-style lending protocol for the EVM Sidechain.
    `APP`, `HIGH`, `OPP-030`

35. **Uncollateralized Lending Interface**
    UI for XLS-66 unsecured credit enabling borrower/lender interaction.
    `APP`, `MEDIUM`, `OPP-031`

36. **Compliant Credit Vault**
    Agent-curator institutional credit vault with attestation-based KYC.
    `APP`, `MEDIUM`, `OPP-032`

37. **Native Yield Aggregator**
    Yearn-equivalent routing cross-protocol yield on XRPL.
    `APP`, `MEDIUM`, `OPP-033`

38. **Lending Front-End on Single Asset Vault**
    Lend/borrow UI + yield dashboard NOW on XLS-65 (pre-XLS-66).
    `APP`, `HIGH`, `OPP-034`

39. **Non-USD Stablecoin DeFi Rails**
    EUR/BRL/SGD/AUD rails integrating into lending, AMMs, and vaults.
    `TOOL`, `LOW`, `OPP-035`

40. **Restaking Protocol for XRP**
    Babylon-fork allowing $110B+ XRP cap productive redeployment.
    `APP`, `HIGH`, `OPP-036`

41. **Synthetic Assets / CDP Protocol**
    Gold/stocks/forex synthetic assets like Synthetix on EVM.
    `APP`, `MEDIUM`, `OPP-037`

42. **Perpetual DEX**
    vAMM or order-book derivatives protocol (highest-volume DeFi category).
    `APP`, `MEDIUM`, `OPP-038`

43. **Decentralized Insurance Protocol**
    Smart contract insurance for institutional DeFi adoption.
    `APP`, `MEDIUM`, `OPP-039`

44. **Prediction Markets Infrastructure**
    Engine layer (oracle resolution, settlement) like Polymarket.
    `TOOL`, `MEDIUM`, `OPP-040`

45. **Prediction Markets dApps**
    Consumer-facing prediction apps for politics/sports/crypto.
    `APP`, `MEDIUM`, `OPP-041`

46. **DeFi Underwriting (AI Service)**
    AI agent pricing DeFi risk for insurance protocols.
    `APP`, `LOW`, `OPP-042`

47. **Liquid Staked XRP (LST)**
    Lido-equivalent enabling stXRP composition in DeFi.
    `APP`, `HIGH`, `OPP-043`

48. **Yield Tokenization Platform**
    Pendle-equivalent splitting yield-bearing assets into PT/YT tokens.
    `APP`, `MEDIUM`, `OPP-044`

## Builder Primitives

49. **Chunked Data + On-Chain Anchoring**
    Standard pattern for IPFS/S3 + on-chain anchoring of large data.
    `TOOL`, `LOW`, `OPP-045`

50. **Gaming Utility-NFT Framework**
    Play-to-earn + cross-game asset interop framework for game devs.
    `TOOL`, `LOW`, `OPP-046`

51. **Pre-Deployed Testnet Infrastructure**
    SurfPool-equivalent local node + pre-deployed contract sandbox.
    `TOOL`, `HIGH`, `OPP-047`

52. **Vendor-Neutral Oracle/Bridge/Ramp**
    Zero-code-change library for swapping provider implementations.
    `TOOL`, `LOW`, `OPP-048`

53. **CeDeFi Yield Integration SDK**
    SDK routing 60%+ CEX-held XRP into XRPL DeFi yield.
    `TOOL`, `MEDIUM`, `OPP-049`

54. **P-256/secp256r1 Signing**
    XLS proposal supporting Apple Enclave + WebAuthn + HSM keys.
    `TOOL`, `MEDIUM`, `OPP-050`

55. **Data Marketplace · Oracle Aggregator**
    Multi-source feed marketplace connecting data sellers and buyers.
    `TOOL`, `LOW`, `OPP-051`

56. **DEX + AMM Liquidity Aggregator SDK**
    SDK routing across native order book + AMM with slippage optimization.
    `TOOL`, `HIGH`, `OPP-052`

57. **XRPL Transaction Indexer**
    TheGraph-equivalent backend indexer powering analytics and dApps.
    `TOOL`, `MEDIUM`, `OPP-053`

58. **Pluggable Proof Primitives Library**
    Composable framework (hash, signature, ZK, custom schemes).
    `TOOL`, `LOW`, `OPP-054`

59. **Proof of Humanity / KYA-NFT**
    Gitcoin Passport/Worldcoin parallel: human verification NFT + score.
    `TOOL`, `MEDIUM`, `OPP-055`

60. **XRPL Scaffolding Extension**
    Scaffolder with a plugin system for RWA/DeFi/NFT frameworks.
    `TOOL`, `MEDIUM`, `OPP-072`

61. **Builder Blocks Catalog**
    Meta-documentation indexing available APIs, wallets, and ramps.
    `TOOL`, `LOW`, `OPP-073`

62. **Dev Utilities Pack**
    Airdrop tool, signing wrapper, glacier API for cold storage.
    `TOOL`, `LOW`, `OPP-074`

## AI Agents

63. **AgentPay — x402 + XRPL Settlement**
    AI agent payment facilitator bridging x402 + XRPL for the agent economy.
    `TOOL`, `LOW`, `OPP-056`

64. **AI-Native Compliance Ops**
    AI + lawyer service delivering compliance-as-a-service at high margin.
    `APP`, `MEDIUM`, `OPP-057`

65. **AI-Native Treasury Ops**
    AI service automating RLUSD management, rebalancing, and yield optimization.
    `APP`, `LOW`, `OPP-058`

66. **AI-Native Restaking Manager**
    AI yield optimizer auto-rebalancing across restaking protocols.
    `APP`, `LOW`, `OPP-059`

67. **On-Chain Reputation for AI Agents**
    KYA primitive enabling agents to build verifiable track records.
    `TOOL`, `LOW`, `OPP-060`

68. **Market-Making-as-a-Service**
    AI agent providing token launch liquidity at high margin.
    `APP`, `MEDIUM`, `OPP-061`

69. **Community-Ops-as-a-Service**
    AI agent managing Discord, Twitter, and grants ops 24/7.
    `APP`, `MEDIUM`, `OPP-062`

70. **Dispute Resolution & Recovery**
    AI-handled claims, refunds, and recovery for on-chain disputes.
    `APP`, `LOW`, `OPP-063`

71. **AI Trading Agents**
    Pre-built (DCA, momentum) or custom alpha trading strategies.
    `APP`, `MEDIUM`, `OPP-064`

72. **Agent Treasury + Wallet for AI**
    Programmatic wallet with guardrails (spending limits, multisig).
    `TOOL`, `LOW`, `OPP-065`

73. **Audit & Continuous Monitoring**
    AI service continuously auditing client protocols at high margin.
    `APP`, `LOW`, `OPP-066`

74. **AI Agent Credit Card with RLUSD**
    OpenClaw-equivalent credit-card primitive for agent spending.
    `APP`, `LOW`, `OPP-067`

---

Contribute to this list on [GitHub](https://github.com/XRPL-Commons/community-ideas/blob/main/make-waves/index.md).
