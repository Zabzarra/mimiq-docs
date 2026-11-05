---
title: Glossary
description: Terms used in these docs.
---

**bp (basis point).** 0.01%. 1 bp of a 10,000 USD trade is 1 USD.

**Builder / integrator fee.** A fee a venue lets an app add on top of its own fee. This is how Mimiq earns its 1 bp.

**Copy source.** The venue and trader whose positions you mirror.

**Execution venue.** The venue where your orders are placed.

**Delta-Neutral.** Long and short the same token on two venues, so price moves cancel out.

**Funding rate.** A periodic payment between longs and shorts on perpetual futures.

**Leg.** One side of a Delta-Neutral pair, or one position of a Pair Trade.

**Basis trade.** A Delta-Neutral pair with the token bought on a spot market as the long leg and its perp as the short leg.

**Pair Trade.** Several long and short legs on any tokens and venues, opened and closed together.

**Total TP/SL.** A take-profit or stop-loss on the combined PnL of all legs. It comes on top of the stops on each leg, never instead of them.

**Hedge guard.** Watches open pairs. If one leg is closed, stopped or liquidated, it closes the other.

**Smart Plan.** A Delta-Neutral plan that opens, holds, closes and repeats on its own.

**Slippage ladder.** Mimiq retries a market order with a wider price limit: 0.3%, 0.6%, 1.0%, 1.5%, 2.0%. Your max slippage (default 2.0%) is a hard ceiling: steps above it are never sent.

**Max slippage.** The furthest from the price a market order of yours may fill. Set it under `⚙️ Settings`.

**Limit order.** An order that rests on the venue at your price until it fills or is cancelled.

**Chase.** An order that rests at the best price of your side and moves with the market until it is filled.

**TWAP.** An order split into tranches over time.

**Scale.** Several orders spread between two prices.

**Maker / taker.** A maker order rests on the book and adds liquidity; a taker order fills against it. Venues charge makers less.

**Reduce-only.** An order that can only shrink a position, never grow it.
