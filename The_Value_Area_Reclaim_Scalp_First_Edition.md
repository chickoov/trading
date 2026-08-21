# The Value Area Reclaim Scalp

## SECTION 1: Strategic Blueprint & Core Rules

### LONG Setup:
- **Entry Trigger**: Price closes above the VWAP + 2σ (Standard Deviation) band on a 5-minute chart, AND price is already above POC.
- **Confirmation**: Order Flow shows bullish absorption — *aggressive selling at/through the level, followed by price reclaiming it*. CVD must show divergence: **price ↑ while CVD ↓**.
- **Exit**: Take profit at T1 = 10% of anchored range’s price distance from POC. Trail stop to VWAP on move.

### SHORT Setup:
- **Entry Trigger**: Price closes below the VWAP - 2σ band on a 5-minute chart, AND price is already below POC.
- **Confirmation**: Order Flow shows bearish absorption — *aggressive buying at/through the level, followed by price rejecting it*. CVD must show divergence: **price ↓ while CVD ↑**.
- **Exit**: Take profit at T1 = 10% of anchored range’s price distance from POC. Trail stop to VWAP on move.

## SECTION 2: Fixed Range VP Tool Placement & Level Mapping

### Anchoring:
- Anchor FRVP to the last 3 RTH (Regular Trading Hours) session open, OR the most recent impulse wave high/low.
- **POC**: Price level with highest traded volume in the anchored range. This is not a midpoint — it’s the *volume-weighted center of mass*.
- **VAH / VAL**: Upper and Lower Value Area boundaries — these are price levels defining the 70% volume range (or custom % if specified). These are structural anchors for entry triggers.

### Level Mapping:
- **High Volume Node (HVN)**: Price level with top 10% of volume in the anchored range; acts as a reaction zone — not resistance/support, but a transition point.
- **Low Volume Node (LVN)**: Price level with bottom 10% of volume in the anchored range; acts as a reaction zone — not support/resistance, but a transition point.
- **Volume Profile Nodes**: Every 5% volume tier from POC to VAH/VAL. Use these for dynamic stop placement and profit targets — *but stops must be measured in price, not % of volume*.

## SECTION 3: Order Flow Footprint Confirmation & Triggers

### Imbalance Requirements:
- **LONG**: Positive delta absorption > 1.2x the average daily imbalance (ADIB). Must be clustered within ±5% of VAH or HVN — *but only if price is reclaiming that level*. If sellers are being absorbed, it’s a valid confirmation.
- **SHORT**: Negative delta absorption > 1.2x ADIB. Must be clustered within ±5% of VAL or LVN — *but only if buyers are being absorbed*. This implies the structure is holding.

### CVD Divergence:
- LONG: Price moves up, but CVD declines (or rises slower than price). OR CVD rises faster than price — this indicates a structural imbalance.
- SHORT: Price moves down, but CVD rises (or declines slower than price). OR CVD declines faster than price — this indicates a structural imbalance.

## SECTION 4: Strict Risk Management & Multi-Target Profit Taking

### Stop Placement:
- **Initial Stop**: Place below the last FRVP VAL for LONG, or above the last FRVP VAH for SHORT — *measured in ticks or ATR* (not % of volume). Use 1.5x ATR as a default.
- **Time-Stop Rule**: If trade stalls >45 minutes without a move toward target → exit. Define “move toward target” as: price must reach at least +0.5R for long or −0.5R for short.

### Profit Targets:
- **Target 1 (T1)**: Exactly 10% of the anchored range’s price distance from POC — *not a node*. If no FRVP node exists at that level, use T1 = 10% of range.
- **Target 2 (T2)**: Exactly 20% of the anchored range’s price distance from POC — *not a node*. If no FRVP node exists at that level, use T2 = 20% of range.

## SECTION 5: Active Scalper's Daily Routine Checklist

1. Review FRVP anchors for last 3 RTH sessions.
2. Scan 5-minute charts for VWAP + 2σ / -2σ breaches — *only if price is already above/below POC*.
3. Confirm order flow imbalances and CVD divergence — *ensure price and CVD move in opposite directions*.
4. Place trades only on confirmed setups — no discretionary entries.
5. Close all positions by 16:00 (4 PM) to avoid overnight risk.

> *Print this as a desktop cheat sheet. Execute mechanically.*