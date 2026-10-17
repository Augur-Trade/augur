# Multichain

A.U.G.U.R runs on **Solana and 13 EVM chains** from one account and one balance view:

Ethereum · Base · BNB Chain · Arbitrum · Optimism · Polygon · Avalanche · Robinhood Chain · Berachain · Sonic · Linea · Unichain · HyperEVM

Switch with **SOL | EVM** in the header.

## Buying on EVM

1. Paste a `0x…` contract address. The app finds which chain it's on, and if the same token trades on several chains, offers an **also on** switcher.
2. A **preview** shows the round-trip cost, any buy/sell tax, a honeypot check (or "not checked" when it can't be confirmed) and whether the amount is below the minimum.
3. Amounts are shown in the chain's native coin (ETH, BNB, AVAX, POL, …) with the USD value alongside.

If you don't have funds on that chain, the preview offers a **Bridge to** shortcut.

## Balances

Home shows your total across every chain and how many chains are funded. Wallet lists each chain with **Deposit**, **Withdraw** and **Bridge**. Empty chains are collapsed. Withdrawals always name the chain before you confirm.

## Bridge

Move funds **between any two supported chains, Solana included**, from inside the app. Pick the source, the destination and the amount, then review the route and fees before confirming.

## Scans on EVM

The [risk scan](risk-scan.md) and [Rugscope](https://github.com/Augur-Trade/rugscope) cover EVM tokens too: honeypots, taxes, owner privileges and holder concentration.
