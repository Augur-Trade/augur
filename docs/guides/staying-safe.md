# Staying safe

Most losses in memecoin trading come from three places: rugs, scams aimed at you, and sizing that's too big. A.U.G.U.R helps with the first. The other two are up to you.

## Your wallet

- **Never share a private key or seed phrase.** Nobody legitimate will ever ask for one: not support, not a moderator, not a "verification bot". Anyone asking is trying to drain you.
- **Exporting your bot-wallet key is for you only.** Do it from **Wallet**, on your own device, and store it somewhere offline.
- **Split your money.** Keep long-term holdings in a wallet you control directly. Fund the bot wallet with what you plan to trade.
- **Use a separate bot wallet for each automated strategy** if you run several (sniper, copy trading, whale copy), so they never compete for the same SOL and a bad run in one can't empty the others.

## Links and accounts

- The website is **augur-trade.com**. Check the address before you sign in or connect a wallet.
- Fake "airdrop", "claim" and "migration" pages are the most common drainer. A.U.G.U.R holder rewards are paid automatically, so there is **nothing to claim**. See [Holder rewards](../features/holder-rewards.md).
- **Connect wallet** in the app is read-only. If any page asks you to sign a transaction just to "verify" or "connect", close it.

## Before every buy

- **Read the risk scan.** It's free for every token. An **Avoid** verdict usually means something concrete: the developer still holds or has sold out, supply is concentrated, wallets were funded together, or the contract can still mint, freeze or charge transfer fees. See [Risk scan](../features/risk-scan.md).
- **Check liquidity.** A thin pool means even a small sell moves the price a lot, and your stop-loss fills far below your number.
- **Look at the token age.** Most rugs happen in the first minutes and hours.

## Automation

Snipers, calls, copy trading and whale copy all **spend real SOL without asking first**.

- Start with small sizes and a limit on how many trades can run at once.
- Always set a **stop-loss**. Exits are checked every second, but in a fast crash the fill can still be worse than your number.
- Use the **daily loss limit** where one exists (whale copy has one). When it's hit, new trades stop for the day.
- Re-check what you're copying. Wallets and whales go cold, often within days.

## Know the odds

- Across the market, **most copy trading loses money**. The whale-copy screen shows the live number at the top. On 17 October 2026, whale copiers across the market had lost about 67 SOL over 18,000 copies in 30 days, and only 32 of 127 whales made their copiers money.
- Past results, caller scores and backtests don't guarantee future results.
- Only trade what you can afford to lose.
