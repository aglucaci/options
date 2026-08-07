# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_18-27-42
- Rows scanned: 478
- Valid signals: 2
- Watchlist setups: 44
- Near-miss setups: 57
- Debit signals: 1
- Credit signals: 1
- Rejected rows: 476

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AAPL | credit | bear_ema8_rejection | 15 | strong_setup | 105 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7813020776476756 | 0.5269628177398962 | Bearish pullup: EMA setup met, liquid quotes: short OI 7540, long OI 2191, bid/ask 2.4%/4.8%, regime accepted. |
| BBAI | debit | bull_ema8_pullback | 12 | strong_setup | 133 | 0.19999999999999996 | 0.8 | 0.19999999999999996 | 4.000000000000001 | 0.2383146973459237 | 0.5131718634042218 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 10.5%/6.2%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 65
- near_miss setup; below option evaluation threshold: 57
- watchlist setup; below option evaluation threshold: 44
- no options expirations found: 18
- no/insufficient daily data: 14
- short leg illiquid (vol=0, oi=1): 4
- short leg illiquid (vol=2, oi=292): 3
- short leg illiquid (vol=1, oi=20): 3
- short leg illiquid (vol=1, oi=7): 3
- spread mid/width too high (35.1%>20.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 245
- SETUP_REJECT: 166
- PRICING_REJECT: 28
- OPTION_CHAIN_REJECT: 18
- DATA_REJECT: 14
- RISK_REJECT: 5

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
