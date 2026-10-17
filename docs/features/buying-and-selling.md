# Buying and selling

## Instant buy

Tap **⚡ Buy** in the bottom bar.

1. **Paste a contract address.** The token card fills in (price, market cap, liquidity, age) and the [risk scan](risk-scan.md) runs underneath. Recent coins you've looked at sit below the field for one-tap reuse, and **Hot right now** suggests what's moving.
2. **Chart.** A live chart sits on top, showing the same price as the token card and the token page. Hide it if you want a compact screen.
3. **Amount.** Pick a preset (0.05 · 0.1 · 0.25 · 0.5 · 1 SOL) or type your own.
4. **Wallets.** If you have several bot wallets, choose which ones buy. Each wallet that buys gets its own position (a "lot").
5. **Exits.** The exits strip shows take-profit, stop-loss, slippage and priority. Tap it to change them for this buy, or set tiers. See [Automated exits](automated-exits.md).
6. **Buy.** A sticky checkout at the bottom shows the token, the total and the USD value before you tap.

If the scan says **Avoid**, the app asks you to confirm before buying.

### Buying from several wallets

When more than one wallet buys, a live card follows every leg: which wallets have filled, at what price, and any that failed (usually for lack of SOL). Each wallet's lot is tracked and sold separately.

### Non-SOL pairs

Some tokens trade against something other than SOL. Those buys route through a swap aggregator automatically, so you still pay in SOL.

## Positions

Every open position shows on **Home** and on the token page with:
- entry → current value and P&L in % and SOL
- age, and which wallet holds it
- its exits: take-profit, stop-loss and tiers

**Manage** a position to:
- **Sell** a percentage of the position
- **Add to position** (buy more)
- **Change exits** at any time. Exits you change after buying are the ones that apply. See [Automated exits](automated-exits.md)
- **Remove position, keep tokens**: stop tracking it without selling

**Track a token you already hold:** in **Wallet**, tap **+ Track** on any holding to turn it into a position, either with your default take-profit and stop-loss, or just tracked with no exits.

## Selling, verified on chain

When you sell, the app **checks your wallet on chain** before telling you anything:

- **Sold:** the tokens left your wallet. It shows how much sold and the SOL received.
- **Not sold:** your token balance didn't change, so nothing happened and you can safely try again.
- **Partly sold:** shown with the exact percentage that went.

You'll never see "Sold" for a sell that didn't land.

## Recent trades

Home lists every buy, sell, snipe and take-profit across all your wallets. It also includes swaps you made on chain outside the app (in Phantom, for example), so the history is complete.

## P&L you can trust

Position values are marked to the live market price, not a cached one, so the number on the card is what you'd roughly get selling now (before slippage).
