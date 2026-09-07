# ICC-Indicator-Tradingview-Pinescript
# TradesBySci ICC Method Indicator

A Pine Script v6 indicator for TradingView that visualizes the **Indication → Correction → Continuation (ICC)** market structure method taught in the TradesBySci trading course.

## What it does

- Marks swing highs/lows and classifies them as **HH / HL / LH / LL / EQH / EQL**
- Flags an **Indication** when price breaks the last opposing swing level
- Shades the **Correction** zone (the pullback that follows)
- Signals **Continuation** — the "2nd push" back through the broken level
- Draws the origin level as a target reference
- Optional trading session highlight (default: London)

This is a visualization tool only — it does not place trades. For automated entries, see the companion strategy script.

## Installation

1. Open TradingView → **Pine Editor**
2. Copy the contents of [`tradesbysci-icc-indicator.pine`](./tradesbysci-icc-indicator.pine)
3. Paste into a new script and click **Add to Chart**

## Settings

| Group | What it controls |
|---|---|
| Market Structure | Swing pivot length, equal high/low tolerance, label visibility |
| Indication / Correction / Continuation | Toggle each stage's visuals and the origin target line |
| Session | Highlight a trading session window (e.g. London, New York) |
| Visuals | Bullish / bearish / neutral colors |

## Alerts

Four alert conditions are included: bullish indication, bearish indication, continuation buy, continuation sell.

## Method reference

Based on the [TradesBySci trading course](https://github.com/mabdullahns007/tradesbysci-trading-course-okf) (Open Knowledge Format bundle).

## Disclaimer

For educational purposes only. Not financial advice. Past performance does not guarantee future results.

## License

MIT
