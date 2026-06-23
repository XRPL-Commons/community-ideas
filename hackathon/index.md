# Hackathon Ideas

Actionable project ideas for building on the XRP Ledger. Each idea is scoped for a hackathon (24-72 hours), has a clear path to generating on-chain transaction volume, and can be demoed live.

---

## Drive Usage

Build applications that drive real usage, sustainable TVL, and ecosystem growth on XRPL.

> Note: the ecosystem-wide **Make Waves** opportunity registry now lives in its own
> section — see [`make-waves/index.md`](../make-waves/index.md).

### Payments & Micropayments

1. **X402 Pay-Per-Article**
   A middleware that serves web content behind HTTP 402 paywalls. Readers pay per article in XRP microtransactions. Publishers set prices per page. Every read is an on-chain payment.
   `X402`, `Micropayments`, `Payment Channels`

2. **Streaming Tips**
   Live-streaming overlay where viewers send XRP tips that trigger on-screen animations. Each tip is a real XRPL payment. Integrate with OBS/Twitch chat via webhooks.
   `Micropayments`, `Webhooks`, `Payment Channels`

3. **Split & Settle**
   Group expense app where users create a shared wallet, log expenses, and settle balances in XRP. Final settlement triggers multiple on-chain payments atomically.
   `Multi-signing`, `Payments`, `Escrow`

4. **Subscription Escrow**
   Recurring payment system using XRPL escrows. Users lock XRP monthly, service providers claim on delivery. Cancel anytime -- unclaimed escrows return automatically.
   `Escrow`, `Time-based Release`, `Recurring Payments`

### DeFi & Trading

5. **RLUSD Remittance Rail**
   Cross-border remittance app using RLUSD. User sends RLUSD on XRPL, recipient gets a notification to cash out. Each transfer is an on-chain payment with trustline setup.
   `RLUSD`, `Trustlines`, `Cross-border Payments`

6. **DEX Limit Order Bot**
   Automated trading bot that places and manages limit orders on the XRPL DEX. Users set strategies (DCA, grid trading), bot executes OfferCreate/OfferCancel transactions.
   `DEX`, `OfferCreate`, `Automated Trading`

7. **Liquidity Pool Dashboard**
   AMM interface for XRPL's native AMM. Users can deposit/withdraw liquidity, view pool stats, and track fees earned. Every LP action is on-chain.
   `AMM`, `Liquidity Provision`, `AMMDeposit/Withdraw`

8. **Flash Swap Arbitrage**
   Bot that detects price discrepancies across XRPL DEX pairs and executes arbitrage in a single transaction. Generates high transaction volume by design.
   `DEX`, `Path Finding`, `OfferCreate`

### Gaming & Engagement

9. **Prediction Market**
   Binary prediction market where users bet XRP on yes/no outcomes. Market maker holds funds in escrow, pays winners on resolution. Every bet and payout is on-chain.
   `Escrow`, `Conditional Release`, `Multi-signing`

10. **NFT Battle Cards**
    Collectible card game where cards are XRPL NFTs. Players mint, trade, and wager cards in PvP battles. Card trades use NFTokenCreateOffer/Accept. Wagers use escrow.
    `NFTs`, `NFTokenMint`, `Escrow`

11. **On-Chain Achievements**
    Gaming achievement system where completing in-game milestones mints achievement NFTs on XRPL. Achievements are tradeable. Rare ones have real value.
    `NFTs`, `NFTokenMint`, `Metadata`

12. **Arcade Token Machine**
    Web arcade where users deposit XRP to get play tokens (issued currency). Win games to earn more tokens. Cash out tokens back to XRP via the DEX.
    `Issued Currencies`, `Trustlines`, `DEX`

### AI-to-AI & Agents

13. **AI Agent Marketplace**
    Platform where AI agents offer services (summarization, translation, code review) and get paid in XRP per request. Each API call triggers a micropayment. Agents can also pay other agents.
    `X402`, `Micropayments`, `Agent-to-Agent`

14. **Data Feed Oracle**
    On-chain oracle that AI agents pay to query. Price feeds, weather data, sports scores -- each query costs a small XRP fee. Data is posted to XRPL memos for transparency.
    `Memos`, `Micropayments`, `Oracle Pattern`

15. **AI Content Bounty Board**
    Post bounties for AI-generated content (articles, images, code). AI agents claim bounties, submit work, humans approve, payment releases from escrow automatically.
    `Escrow`, `Conditional Release`, `Memos`

### Ad-Tech & Attention Economy

16. **Pay-Per-Click Ads**
    Decentralized ad network where advertisers deposit XRP, publishers get paid per verified click. Smart escrow releases funds based on click proofs stored in memos.
    `Escrow`, `Memos`, `Micropayments`

17. **Survey Rewards**
    Users earn XRP for completing surveys. Each completed survey triggers an instant on-chain payment. Brands fund survey pools via escrow.
    `Escrow`, `Micropayments`, `Payments`

---

## Impact Finance

Blockchain at the service of social and environmental impact.

### Financial Inclusion

18. **Micro-Savings Circles (Tontine)**
    Digital tontine/savings circle where members contribute XRP weekly via escrow. Each round, one member receives the pool. All contributions and payouts are on-chain.
    `Escrow`, `Multi-signing`, `Scheduled Payments`

19. **Micro-Insurance Pool**
    Community insurance pool where members deposit small XRP amounts. Claims are voted on by members (multi-sign). Approved claims trigger automatic payout.
    `Multi-signing`, `Escrow`, `Voting`

20. **Remittance for the Unbanked**
    Simple mobile-first remittance app targeting unbanked populations. Sender pays in XRP/RLUSD, recipient gets a QR code to cash out at local agents. Every transfer is on-chain.
    `RLUSD`, `Payments`, `QR Codes`

21. **Micro-Lending Circle**
    P2P micro-lending where lenders fund loans via escrow with time-based release. Borrowers repay in installments. Credit score tracked via on-chain repayment history.
    `Escrow`, `Time-based Release`, `Memos`

### Climate & Environment

22. **Carbon Credit Marketplace**
    Tokenize carbon credits as XRPL issued currencies. Businesses buy credits to offset emissions, credits are burned (sent to black-hole account). Every purchase and retirement is on-chain.
    `Issued Currencies`, `Trustlines`, `Token Burning`

23. **Community Solar Ledger**
    Track community solar panel energy production. Producers earn energy tokens (issued currency on XRPL). Consumers buy tokens to offset their energy bill. All trades on the DEX.
    `Issued Currencies`, `DEX`, `IoT Integration`

24. **Reforestation Tracker**
    Fund tree planting with XRP. Each tree is an NFT with GPS coordinates and growth photos. Donors can track their tree's progress. Planting organizations receive funds via escrow.
    `NFTs`, `Escrow`, `Metadata Updates`

### Humanitarian & Social Good

25. **Transparent Aid Distribution**
    Aid organizations distribute funds in RLUSD to beneficiaries. Every disbursement is on-chain and publicly auditable. Beneficiaries spend at approved merchants.
    `RLUSD`, `Trustlines`, `Payments`

26. **Disaster Relief Fund**
    Crowdfunding for disaster relief where donations are in XRP, held in multi-sign escrow. Fund release requires approval from multiple aid organizations. Full transparency.
    `Multi-signing`, `Escrow`, `Crowdfunding`

27. **Education Scholarship DAO**
    Community-funded scholarship pool. Members contribute XRP, vote on scholarship recipients via multi-sign. Funds release to the student's wallet on approval.
    `Multi-signing`, `Escrow`, `Voting`

28. **Supply Chain Provenance**
    Track fair-trade goods from producer to consumer. Each handoff is a transaction with memo data (GPS, timestamp, handler). Consumers scan QR to see the full chain.
    `Memos`, `NFTs`, `Supply Chain`

---

## General Ideas

29. **NFT Event Tickets**
    Mint event tickets as NFTs. Transfer = resale (with royalty enforced by XRPL). Check-in burns the ticket. Every mint, transfer, and burn is on-chain.
    `NFTs`, `NFTokenMint`, `Transfer Fees`

30. **Freelancer Escrow**
    Client deposits XRP in escrow, freelancer delivers work, client approves release. Dispute resolution via multi-sign arbitrator. Every project = 2-3 on-chain transactions minimum.
    `Escrow`, `Multi-signing`, `Conditional Release`

31. **Loyalty Points System**
    Issue loyalty tokens as XRPL currency. Customers earn tokens on purchase, redeem for rewards. Tokens tradeable on DEX. Every purchase and redemption is on-chain.
    `Issued Currencies`, `Trustlines`, `DEX`

32. **DAO Treasury Manager**
    Multi-sig wallet for DAO treasuries. Members propose and vote on spending. Approved proposals auto-execute payments. All governance is on-chain via memos.
    `Multi-signing`, `Memos`, `Payments`

33. **Digital Identity Credentials**
    Issue verifiable credentials as NFTs (diplomas, certificates, badges). Institutions mint, holders present, verifiers check on-chain. Credential = NFT with metadata.
    `NFTs`, `Metadata`, `Verification`

34. **Bounty Board**
    Post open-source bounties funded with XRP escrow. Developers claim, submit PRs, maintainers approve, escrow releases. Every bounty lifecycle generates 3+ transactions.
    `Escrow`, `Conditional Release`, `Memos`

35. **Payroll on XRPL**
    Batch payroll system that pays employees/contractors in XRP or RLUSD. Employer loads funds, system distributes on schedule. Each pay run = N on-chain payments.
    `Payments`, `RLUSD`, `Batch Transactions`

---

**How to pick an idea:**
1. Can you demo a working transaction in 24 hours? If not, scope down.
2. Does normal usage generate on-chain transactions? The more transactions per user action, the better.
3. Can a judge try it live? Build for testnet with a faucet-funded demo wallet.

Contribute to this list on [GitHub](https://github.com/XRPL-Commons/community-ideas/blob/main/hackathon/index.md)
