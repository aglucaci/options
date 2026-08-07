# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_19-35-43
- Rows scanned: 478
- Valid signals: 2
- Watchlist setups: 40
- Near-miss setups: 54
- Debit signals: 2
- Credit signals: 0
- Rejected rows: 476

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TLT | debit | bull_continuation | 8 | valid_setup | 84 | 0.66 | 4.34 | 0.66 | 6.575757575757575 | 0.30926084487175043 | 0.6275915580591671 | Bullish pullback: EMA setup met, liquid quotes: short OI 886, long OI 555, bid/ask 8.7%/1.3%, regime accepted. |
| BBAI | debit | bull_ema8_pullback | 13 | strong_setup | 133 | 0.19499999999999995 | 0.805 | 0.19499999999999995 | 4.1282051282051295 | 0.23893839080866908 | 0.5291622206044886 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 7.1%/2.1%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 70
- near_miss setup; below option evaluation threshold: 54
- watchlist setup; below option evaluation threshold: 40
- no options expirations found: 18
- no/insufficient daily data: 14
- short leg illiquid (vol=0, oi=1): 4
- short leg illiquid (vol=2, oi=292): 3
- spread mid/width too high (34.7%>20.0%): 2
- short leg illiquid (vol=2, oi=120): 2
- spread mid/width too high (31.3%>20.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 236
- SETUP_REJECT: 164
- PRICING_REJECT: 36
- OPTION_CHAIN_REJECT: 18
- DATA_REJECT: 14
- RISK_REJECT: 8

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
