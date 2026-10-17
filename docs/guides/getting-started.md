# Getting started

From nothing to your first trade in about five minutes.

## 1. Try the demo first (optional)

The **[live demo](https://augur-trade.com/app/?explore=1)** is the real app running on a demo account. Every screen works, prices and charts are live, and nothing you do moves real money. Trades and settings there are blocked with a "Preview mode" note.

It's the fastest way to learn the layout before you fund anything.

## 2. Open A.U.G.U.R

Pick whichever you prefer. It's one account everywhere, and you can switch at any time.

- **Browser:** [augur-trade.com/app](https://augur-trade.com/app/)
- **Telegram:** use **Start in Telegram** on [augur-trade.com](https://augur-trade.com)
- **Android:** the app loads the same live web app, so new features arrive without an update

See [Platforms](platforms.md) for what differs between them.

## 3. Sign in

You sign in with Telegram. Your account, settings, wallets, snipers and history follow you across the browser, Telegram and Android.

> [!NOTE]
> **Connect wallet** (Phantom or Solflare) is a read-only mode. You can browse with your real balances, but you can't trade from it. Trading needs a bot wallet (next step).

## 4. Create your bot wallet

Trades are sent from a **bot wallet**, a Solana wallet A.U.G.U.R signs with so it can buy and sell in under a second without asking you to approve each one.

- **It's yours.** You can export its private key at any time from **Wallet** and import it into Phantom or any other wallet.
- You can run **several bot wallets** from one account and buy from many at once. See [Wallets](../features/wallets.md).
- Keep your long-term holdings in your own wallet, and fund the bot wallet with what you intend to trade.

## 5. Fund it

Send SOL to the bot wallet address shown in **Wallet**. You can also buy SOL with a bank card from **More → Buy SOL**.

How much you need depends on what you'll do:

| You want to | Have at least |
|---|---|
| Make manual buys | Your buy size + about 0.01 SOL for fees and token-account rent |
| Run a channel sniper | Your snipe size × the number of snipes you allow at once, plus a buffer |
| Use whale copy | Your copy size + about 0.11 SOL per open copy (rent, refunded on close, plus a reserve for exits) |

Solana keeps a small rent deposit on every token account. It comes back when the account is closed. See [Wallets → rent](../features/wallets.md#rent-and-reclaiming-it).

## 6. Your first trade

1. Open **Buy** and paste a contract address.
2. Read the **risk scan** that appears under the token. If it says **Avoid**, think twice. See [Risk scan](../features/risk-scan.md).
3. Pick an **amount** and, if you have several wallets, which wallets buy.
4. Check the **exits** strip: take-profit, stop-loss, slippage and priority. Change them here or in **Buy settings**.
5. Tap **Buy**. The position appears on **Home** with live P&L, and your exits start watching it immediately.

To sell, open the position and choose a percentage, or let your exits do it. Every sell is checked against the chain before the app tells you it landed. See [Buying and selling](../features/buying-and-selling.md).

## 7. Set up automation (when you're ready)

- **[Channel sniper](../features/channel-sniper.md):** buy the moment a contract address is posted in a group, channel or X account you trust.
- **[Calls](../features/calls-and-top-picks.md):** auto-buy calls that pass your filters.
- **[Copy trading](../features/copy-trading.md):** mirror a wallet that backtests well.
- **[Whale copy](../features/whale-copy.md):** copy liquidity whales that are making copiers money.

Start small. Every automated feature spends real SOL without asking first.

---
<sub>Trading crypto is risky. Only trade what you can afford to lose.</sub>
