# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_16-28-46
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 49
- Near-miss setups: 55
- Debit signals: 1
- Credit signals: 0
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BBAI | debit | bull_ema8_pullback | 12 | strong_setup | 133 | 0.18499999999999994 | 0.8150000000000001 | 0.18499999999999994 | 4.405405405405407 | 0.23421115051418473 | 0.5354765379908856 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 7.4%/6.6%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 66
- near_miss setup; below option evaluation threshold: 55
- watchlist setup; below option evaluation threshold: 49
- no options expirations found: 18
- no/insufficient daily data: 14
- short leg illiquid (vol=1, oi=20): 3
- short leg illiquid (vol=1, oi=7): 3
- short leg illiquid (vol=20, oi=292): 2
- short leg illiquid (vol=1, oi=14): 2
- spread mid/width too high (31.5%>20.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 249
- SETUP_REJECT: 170
- PRICING_REJECT: 21
- OPTION_CHAIN_REJECT: 18
- DATA_REJECT: 14
- RISK_REJECT: 5

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
