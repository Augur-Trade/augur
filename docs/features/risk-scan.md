# Risk scan

Every token gets a free scan **before you buy**: in the Buy screen, on every token page, on every call and at [augur-trade.com/rug](https://augur-trade.com/rug/).

## What it checks

| Check | Why it matters |
|---|---|
| **Mint authority** | If it isn't revoked, the developer can print more tokens and dilute you |
| **Freeze authority** | If it isn't revoked, your tokens can be frozen so you can't sell |
| **Transfer fees and hooks** (Token-2022) | Hidden fees on every transfer, or code that can block or redirect transfers |
| **Holder concentration** | A few wallets holding most of the supply can dump on everyone else |
| **Developer history** | Serial launchers and devs whose past tokens rugged |
| **Bundles and snipers** | Wallets that bought in the launch block, often funded together. A sign of a coordinated dump |
| **Insiders** | Supply sitting in wallets that never bought (it was transferred to them) |
| **Liquidity** | Too little, and you can't exit without crashing the price |

> [!NOTE]
> **Tokens still on a launchpad bonding curve** (pump.fun, Meteora DBC launchpads, letsbonk and others) have no DEX pool yet, so most market sites show **$0 liquidity** for them. The scan reads the SOL actually sitting in the curve straight from the chain instead: that's what you sell back into. It shows the curve and its launchpad, and never calls a curve token unsellable just because no pool exists yet.

## Reading the result

The scan sums everything into **one score** with a grade and a verdict. **The higher the score, the safer.** The top flags are listed under it, so you can see *why*.

An **Avoid** verdict means concrete red flags: a likely rug, a honeypot or a setup for a dump.

> [!NOTE]
> Most brand-new pump.fun coins scan **Avoid**: the developer has already sold, or is a serial launcher. That's what the market looks like, not the scanner being harsh.

## Where it acts for you

- **Buy:** an Avoid verdict asks you to confirm before buying.
- **Calls:** the scan guard can hide or skip Avoid tokens, or require a minimum score.
- **Snipers:** a stricter [rug guard](channel-sniper.md#the-rug-guard) runs before every snipe and skips when it can't check.
- **Whale copy:** every copy passes a token check before it opens.

## Rugscope

The full scanner is **A.U.G.U.R Rugscope**: ten engines in parallel (bundle forensics, the developer's all-time record, insiders, named wallets, contract traps and a dump-probability model), with one verdict in about a second, for Solana and 13 EVM chains. Engines, model card and the free API: **[Augur-Trade/rugscope](https://github.com/Augur-Trade/rugscope)**.
