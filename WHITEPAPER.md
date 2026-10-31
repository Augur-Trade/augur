<p align="center"><a href="https://augur-trade.com/whitepaper/"><img src="media/header.jpg" alt="A.U.G.U.R" width="100%"></a></p>

# A.U.G.U.R Whitepaper

**Autonomous Unit for Gauging Upside & Risk** · version 1.0 · 31 October 2026

An autonomous trading platform for Solana and 13 EVM chains: fast execution, an AI agent that reads every token, and a token whose holders share the platform's fees.

📄 **[Read it on the web](https://augur-trade.com/whitepaper/)** · **[Download the PDF](docs/whitepaper/augur-whitepaper.pdf)**

## Contents
1. Overview
2. The problem
3. The platform
4. Safety & intelligence
5. A.L.F, the agent
6. The $AUGUR token
7. Fees & holder rewards
8. Oracle Run
9. Trust & transparency
10. Roadmap
11. Risks & disclaimer
12. Official links

---

> **Abstract.** Memecoin markets reward whoever sees a token first and reads it correctly. Most traders lose on both counts: they are slower than bots, and they cannot tell a real launch from a rug in the seconds that matter. A.U.G.U.R closes that gap. It pairs sub-second execution (snipers on Telegram and X calls, copy trading, automatic exits) with a safety layer trained on our own recording of every pump.fun trade, and an AI agent, A.L.F, that runs the community and explains every token in plain words. The platform charges 2% on buys and nothing on sells, and half of all platform fees are paid to $AUGUR holders in SOL, every day.

## 1. Overview

A.U.G.U.R is a non-custodial trading desk. Every user gets their own wallet, created by our Telegram bot, with a private key that belongs to them and can be exported at any time. The same account works in three places: the Telegram bot [@TradeWithAUGUR_bot](https://t.me/TradeWithAUGUR_bot), the web app at [augur-trade.com/app](https://augur-trade.com/app/), and the Android app.

The project started as MAD and relaunched as A.U.G.U.R in October 2026. MAD holders carried over 1:1 into $AUGUR through an on-chain claim, so the token began with an existing holder base rather than an empty launch.

| 14 | 2% | 50% | 19.1% |
|---|---|---|---|
| chains: Solana + 13 EVM | fee on buys · sells free | of fees paid to holders | of supply locked by the team |

## 2. The problem

- **Speed.** Calls are posted in Telegram groups and on X, and the first buyers take the move. A human copying a contract address into a wallet is seconds behind automated traders.
- **Rugs and traps.** Bundled launches, dev wallets that dump, honeypots and fake liquidity look identical to real tokens at first glance.
- **Discipline.** Most losses come from exits: holding winners too long and losers too far. Manual take-profit and stop-loss rarely survive a fast market.
- **Fragmentation.** Opportunities are spread across Solana and many EVM chains, each with its own wallet, bridge and swap.

## 3. The platform

- **Paste-to-buy.** Paste any Solana or EVM address to see price, market cap, liquidity and a safety grade, then buy in one tap. Every buy gets take-profit and stop-loss automatically.
- **Snipers.** Arm Telegram call groups or X accounts. When a contract address is posted, A.U.G.U.R buys immediately, with per-source size, exits, liquidity and market-cap filters, one-shot mode and caller filters.
- **Copy trade & whale copy.** Mirror any Solana wallet's buys (and optionally its sells) at your own size, or follow Meteora liquidity whales.
- **Exits that hold.** Take-profit, stop-loss and tiered take-profit (sell in steps) run on the server, so they work while your phone is off.
- **Multi-wallet.** Up to nine wallets that buy together, each as its own position, with SOL dispersal between them.
- **Multichain.** One EVM wallet with the same address on Base, Ethereum, BNB Chain, Arbitrum, Robinhood and eight more, with honeypot checks before any buy and a built-in bridge to and from Solana.

Execution on Solana routes through PumpPortal and Jupiter. Once a call is detected, a snipe typically lands in under a second.

## 4. Safety & intelligence

### Auspice: the token scanner

[Auspice](https://augur-trade.com/rug/) grades any token in seconds: liquidity, holder concentration, bundled launches, developer history and red flags. Its rug-risk model is trained on our own continuous recording of pump.fun bonding-curve trades. On held-out data it ranks rug risk correctly about 84% of the time (AUC 0.84), and its probabilities are calibrated: a token scored at 50% risk rugs roughly half the time.

### Foresight: an oracle for AI agents

[Foresight](https://augur-trade.com/foresight/) exposes the same data and tooling to other AI agents over MCP and HTTP, paid per call in USDC or SOL with free daily calls: on-chain data across chains, pump.fun analytics, risk scans and research utilities. Its interface, documentation and SDKs are public on [GitHub](https://github.com/Augur-Trade).

## 5. A.L.F, the agent

A.L.F (Autonomous Learning Framework) is the AI agent of A.U.G.U.R. It reads tokens and answers with a clear BUY / WATCH / AVOID and the reasons, helps users with their own accounts, hosts the community on Telegram, Discord and X, and can join voice chats and calls. A.L.F never asks for keys or seed phrases and never DMs anyone first, which makes impersonators easy to spot.

## 6. The $AUGUR token

| | |
|---|---|
| Name / ticker | A.U.G.U.R · $AUGUR |
| Chain / standard | Solana · Token-2022 (no transfer tax, no transfer hook) |
| Contract | `7yqTtb47Sa1w2KNabXCSLkv99DH1uCLLehK8uDpapQEe` |
| Total supply | 964,831,218 $AUGUR |
| Launch | 26 October 2026 on pump.fun, single developer buy, no presale; graduated to PumpSwap the same day |
| MAD migration | MAD holders credited 1:1 and claimed on-chain through a Streamflow distributor |
| Supply split (28 Oct) | Liquidity pool 21.6% · team, OG & project wallets ~52% · public ~26% |

*The supply split is measured from on-chain balances and published, wallet by wallet, at [augur-trade.com/wallets](https://augur-trade.com/wallets/). Most OG wallets are long-term holders carried over from MAD.*

## 7. Fees & holder rewards

A.U.G.U.R charges **2% on buys**. Selling is free and there is no subscription. **Half of all platform fees go to $AUGUR holders**, paid in SOL every day at 12:00 UTC, straight to the wallet that holds the tokens. There is nothing to stake or claim.

| Holding | Share of platform fees |
|---|---|
| 5,000,000+ $AUGUR | Shares a pool of 12.5% of fees, split by balance |
| 10,000,000+ $AUGUR | Also shares a second pool of 37.5% of fees, split by balance |

Users who invite traders through their referral link (Invite & Earn in the app) also earn a share of the fees those traders generate. Every payout is recorded in a public ledger at [augur-trade.com/holders](https://augur-trade.com/holders/).

## 8. Oracle Run

Oracle Run is the game built into the app. Players earn coins on every verified run, and **1 coin = 1 $AUGUR**, paid to their own A.U.G.U.R wallet from a dedicated, public rewards pool. Payouts are capped at 20,000 $AUGUR per player per day, and the weekly top three win 100,000, 80,000 and 50,000 $AUGUR.

Oracle Race is the multiplayer mode: two to five players on the same seeded track, with the top two taking the pot. Racing for the pot requires 10,000 $AUGUR in the player's app wallet, and anti-farming rules remove inactive players.

## 9. Trust & transparency

### Team supply lock

The team committed to locking **at least 15% of the supply for six months** on Streamflow, and has gone past it: **19.1% of the supply is locked**. Locks cannot be cancelled, moved or redirected, and each one returns only to the wallet that locked it. Every lock has a public certificate.

*184.3M $AUGUR (19.1% of supply) locked across three team wallets as of 31 October 2026, against a 15% goal (marker). Live figures: [augur-trade.com/lock](https://augur-trade.com/lock/).*

### Verifiable by design

- Every project wallet is labelled with its purpose and live balance at [/wallets](https://augur-trade.com/wallets/).
- User wallets are non-custodial: keys are created for each user and can be exported at any time.
- Holder rewards, game payouts and locks are all on-chain and independently checkable.
- The only official contract address is `7yqTtb47Sa1w2KNabXCSLkv99DH1uCLLehK8uDpapQEe`. Admins never DM first, and A.U.G.U.R never asks anyone to connect a wallet or share a seed phrase.

## 10. Roadmap

We publish what has shipped and what is actively being built. We do not publish dates we cannot keep.

- ✅ **Oct 2026** · A.U.G.U.R relaunch, $AUGUR on pump.fun and PumpSwap, MAD 1:1 claim
- ✅ **Oct 2026** · Daily holder rewards in SOL, referral rewards, public payout ledger
- ✅ **Oct 2026** · Oracle Run $AUGUR payouts, multiplayer races, share cards
- ✅ **Oct 2026** · Team supply lock passes its 15% goal: 19.1% of supply locked for six months
- ✅ **Oct 2026** · Android app, Telegram bot with full sniper controls, race links that open the app
- 🔄 **In progress** · Multi-wallet management, token launcher and bridge inside the Telegram bot

## 11. Risks & disclaimer

> [!WARNING]
> This document describes a product and a token. It is not financial advice, an offer, or a solicitation to buy any asset.

- **Market risk.** Memecoins, including $AUGUR, are extremely volatile and can lose most or all of their value. Only trade what you can afford to lose.
- **No guaranteed returns.** Holder rewards depend on platform fee income, which varies with usage. Past payouts do not predict future ones.
- **Tool risk.** Snipers, copy trading and automated exits act fast on your behalf. They can buy tokens that fall, and safety grades are probabilities, not guarantees.
- **Technical risk.** Blockchains, RPC providers, bridges and third-party protocols can fail, congest or change.
- **Regulatory risk.** Rules for digital assets differ by country and may change. You are responsible for complying with the laws where you live.

## 12. Official links

| | |
|---|---|
| Website | [augur-trade.com](https://augur-trade.com) |
| Web app | [augur-trade.com/app](https://augur-trade.com/app/) |
| Telegram bot | [@TradeWithAUGUR_bot](https://t.me/TradeWithAUGUR_bot) |
| Community | [t.me/AUGUR_Trade](https://t.me/AUGUR_Trade) · channel [t.me/augurtrading](https://t.me/augurtrading) |
| X | [x.com/augurtrading](https://x.com/augurtrading) |
| GitHub | [github.com/Augur-Trade](https://github.com/Augur-Trade) |
| Transparency | [Wallets](https://augur-trade.com/wallets/) · [Team lock](https://augur-trade.com/lock/) · [Holder ledger](https://augur-trade.com/holders/) |

*Anything else claiming to be A.U.G.U.R is fake.*

---

*A.U.G.U.R Whitepaper v1.0 · 31 October 2026 · Figures are as of publication; live numbers are on the linked pages.*
