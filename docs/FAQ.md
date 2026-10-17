# FAQ

**What is A.U.G.U.R?**
An autonomous trading agent for Solana and 13 EVM chains. It snipes new tokens from the channels you follow, manages exits automatically, copies wallets you choose and reads any token before you buy. It runs in the browser, in Telegram and on Android.

**What does it cost?**
2% on buys. Selling is free and there is no subscription.

**How do automated exits work?**
Set take-profit, stop-loss, tiered exits and trailing stops for each trade. Positions are checked every second and sold on the fast path, so you exit close to your number.

**How does copy trading work?**
Choose any wallet and A.U.G.U.R mirrors its trades with your own size, take-profit and stop-loss. Each wallet is graded with a copy-backtest first, and you can unfollow in one tap.

**What does the risk scan check?**
Mint and freeze authority, hidden fees and transfer hooks, top-holder concentration, developer history, snipers and liquidity, summed up as one score. It's free for every token, in the app and at [augur-trade.com/rug](https://augur-trade.com/rug/).

**Who is A.L.F?**
A.L.F (Autonomous Learning Framework) is the AI agent inside A.U.G.U.R. It reads a token's liquidity, buy pressure, holder flow and socials, then gives a plain verdict (buy, watch or avoid) with its reasoning.

**Which chains are supported?**
Solana, Ethereum, Base, BNB Chain, Arbitrum, Optimism, Polygon, Avalanche, Robinhood Chain, Berachain, Sonic, Linea, Unichain and HyperEVM, with a built-in bridge.

**What is whale copy?**
It copies the liquidity positions of Meteora DLMM whales from your bot wallet, at your size, with a stop-loss and a daily loss limit. Whales are ranked by what copying them actually returned, and the default view only shows whales copiers are profiting on right now. It costs 10% of the profit on winning copies and nothing on losses. [Full guide](features/whale-copy.md).

**Why doesn't whale copy rank whales by their own profit?**
Because it doesn't predict copy results. Across 62 whales, a whale's own 30-day return and its copiers' 30-day return were essentially uncorrelated. Most "profit" in whales' own books is also token value at the moment of withdrawal, not SOL. [Details](features/whale-copy.md#where-the-numbers-come-from).

**Are my bot wallets mine?**
Yes. You can export the private key of any bot wallet from Wallet and import it into Phantom or any other Solana wallet.

**How do holder rewards work?**
Half of all platform fees go to holders, paid daily at 12:00 UTC in SOL. 5M+ holders share 12.5% of fees, and 10M+ holders share a further 37.5%. There is nothing to claim. [Details](features/holder-rewards.md).

**Where are the full docs?**
In [docs/](README.md): guides, every feature, pricing, a glossary and the changelog.

**Can I try it without an account?**
Yes. The [live demo](https://augur-trade.com/app/?explore=1) runs the real app on a demo account. Nothing in it is real money.

**Is the code open source?**
No. This repository is a showcase. The trading engine is closed source.

---
Trading crypto is risky. Nothing here is financial advice.
