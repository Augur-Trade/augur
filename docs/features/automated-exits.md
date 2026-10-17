# Automated exits

Every position can sell itself. Exits are checked **every second** and sold on the fast path.

## Exit types

| Exit | What it does | Example |
|---|---|---|
| **Take-profit** | Sells when the position is up by your target | TP +50% sells at 1.5× |
| **Stop-loss** | Sells when the position is down by your limit | SL −35% sells at 0.65× |
| **Tiered take-profit** | Sells part of the position at each level | 30% at +50%, 30% at +100%, rest at +200% |
| **Trailing stop** | Follows the price up and sells when it drops back by your distance from the high | Trail 20%: a peak of 3× sells at about 2.4× |

## Where exits come from

| How you bought | Exits used |
|---|---|
| Instant buy | Your Buy settings, or what you set on that buy |
| Channel or X sniper | That sniper's own exits |
| Calls auto-buy | Your Calls exits |
| Copy trading | The exits you set for that copied wallet |
| Snipe Top Picks | The exits set for Top Picks |

## Changing exits later

Change take-profit, stop-loss or tiers on any open position, at any time, from **Manage**. **The exits you set last are the ones that apply.** After buying more of the same token, open **Manage** and check the exits are still what you want.

## What an exit can't promise

An exit triggers at your number, then sells at the **next available price**. In a sudden crash, or in a pool with little liquidity, the fill can be well past your stop. In the first minutes of a launch, gaps of 10–30% between candles happen. Size for that.

## Panic sell

**Panic** on Home sells every open position across every wallet at once. Use it when you need out of everything.

## Whale copy exits

Whale copies work differently: they close when the whale exits or your stop-loss is hit. See [Whale copy](whale-copy.md#closing).
