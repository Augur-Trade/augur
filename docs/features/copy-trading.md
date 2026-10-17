# Copy trading

Mirror any Solana wallet's trades from your own bot wallet, with your own size and exits. Every wallet is **graded with a copy-backtest before you follow**, so you know whether copying it would actually have paid.

Open it from **More → Copy Trader**.

## The three tabs

| Tab | What's there |
|---|---|
| **My wallets** | Wallets you copy: each one's grade, live status, size and exits, with a switch to pause it |
| **Discover** | Active smart-money wallets, already backtested and graded, refreshed every 30 minutes |
| **Copies** | Every position opened by copying, with live P&L |

The header shows open copy P&L, copies open and wallets live.

## Grades

Paste a wallet and you get an instant **copy-backtest**: what would have happened if you'd copied its recent buys, entering a couple of seconds after it (the delay a real copy has), with fees included.

| Grade | Meaning |
|---|---|
| **Copyable** (A–B) | Copying it would have made money |
| **Mixed** | Some edge, inconsistent |
| **Fades** | The wallet makes money, but copiers arriving seconds later don't |
| **Risky** | Losses, or patterns that suggest a bot, insider or wash trader |

> [!NOTE]
> Many profitable wallets **fade** when copied: they buy first and sell into the buyers who follow, which includes you. The grade is built to catch that. On the day this feature launched, only 6 of the top 36 smart-money wallets graded copyable.

## Adding a wallet

1. Paste the address. The backtest preview appears instantly.
2. **Size:** a fixed SOL amount per trade, or a multiple of their size with a maximum.
3. **Exits:** pick *Safe*, *Balanced* or *Degen*, or set your own take-profit and stop-loss.
4. **Mirror sells:** sell when they sell, on top of your own exits.
5. Save. Copying starts with their next buy.

You can also start a copy straight from [Flow](flow.md): every big buyer there has a **Copy trades** button.

## Tips

- Re-check grades. Wallets that copied well last week can fade this week.
- Use a fixed size until you trust a wallet. Multiples of a big wallet's size get expensive fast.
- Mirror sells helps with wallets that exit early. Your own stop-loss still protects you if they hold through a dump.

For liquidity-pool whales on Meteora, see [Whale copy](whale-copy.md). It's a different strategy with its own page.
