# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_15-31-36
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 45
- Near-miss setups: 53
- Debit signals: 1
- Credit signals: 0
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BBAI | debit | bull_ema8_pullback | 12 | strong_setup | 133 | 0.175 | 0.825 | 0.175 | 4.714285714285714 | 0.22940942640176754 | 0.5467984819356352 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 11.3%/4.5%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 71
- near_miss setup; below option evaluation threshold: 53
- watchlist setup; below option evaluation threshold: 45
- no options expirations found: 18
- no/insufficient daily data: 14
- short leg illiquid (vol=1, oi=20): 3
- short leg illiquid (vol=1, oi=7): 3
- short leg illiquid (vol=0, oi=1): 3
- short leg illiquid (vol=20, oi=292): 2
- short leg illiquid (vol=1, oi=14): 2

## Rejection Classes

- LIQUIDITY_REJECT: 251
- SETUP_REJECT: 169
- PRICING_REJECT: 22
- OPTION_CHAIN_REJECT: 18
- DATA_REJECT: 14
- RISK_REJECT: 3

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
