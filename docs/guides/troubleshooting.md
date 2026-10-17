# Troubleshooting

## Buying

**"Insufficient funds" when I have SOL**
Every buy needs your buy size plus network fees, priority fee and the rent deposit for a new token account (about 0.002 SOL). Leave about 0.01 SOL spare on top of the buy.

**The buy failed or took a long time**
Busy blocks and fast-moving new tokens can push a transaction past its slippage limit. Raise slippage a little in **Buy settings**, or raise the priority fee, then try again. A failed transaction still costs the small network fee.

**The price I paid is higher than the chart showed**
Memecoins move in seconds. Your fill reflects the price when the transaction landed, plus slippage. In the first minutes of a launch, fills well above the call price are common.

**The scan says "Avoid". Can I still buy?**
Yes. The app asks you to confirm first. The scan is advice, not a block.

## Selling

**The app says a sell didn't land**
Every sell is checked against your wallet on chain before the app reports it. "Not sold" means the token balance didn't change. Nothing left your wallet, so you can safely try again.

**I sold a small percentage but more went**
Check the position card: each wallet holds its own lot. If several wallets hold the same token, a sell applies to the wallet you picked.

**My take-profit or stop-loss didn't fire at the exact number**
Exits are checked every second and sold on the fast path, but the fill is the next available price. In a sharp move, or in a thin pool, that can be noticeably past your number.

## Wallets

**My balance looks out of date**
The app reads your SOL balance from the chain itself. Pull down or reopen Wallet to refresh it. If a transfer was just sent, give it a few seconds to confirm.

**I can't send all my SOL from a wallet**
Solana only lets a wallet end at **0** or at **at least about 0.00089 SOL** (the rent minimum). Use **Max** to send everything, or leave at least that amount behind. A wallet with open token accounts needs a little SOL for fees to close them.

**There's SOL stuck in empty token accounts**
Every token account holds a small rent deposit. Use **Reclaim rent** in Wallet to close empty accounts and get it back. See [Wallets → rent](../features/wallets.md#rent-and-reclaiming-it).

**A token I hold isn't showing**
Holdings list tokens with a market price and some liquidity, so spam airdrops stay out. A token with no market won't appear until it has one.

**Some tokens have a transfer fee**
Newer Solana tokens (Token-2022) can charge a fee on every transfer, or block transfers entirely. The risk scan flags these before you buy, and Send refuses tokens that can't be transferred.

## Automation

**My sniper is armed but didn't buy**
- The post may not have contained a contract address the sniper recognised.
- The token may have failed your filters or the rug guard (serial developer, concentrated supply, bundled launch).
- The wallet may not have had enough SOL for your snipe size plus fees.

**My whale copy didn't open**
Copies only open when a whale you follow opens a new position with real size, the token passes the risk check, your wallet can cover the copy plus rent and reserve, and you're under your max open copies and daily loss limit. **My copies** shows your status at the top. See [Whale copy](../features/whale-copy.md#when-a-copy-wont-open).

## Still stuck?

Ask in the community chat in the app, or ask A.L.F. Never share your private key or seed phrase with anyone who offers to help.
