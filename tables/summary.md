# Daily EMA Options Research Summary

- Run timestamp: 2026-08-05_17-52-47
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 62
- Near-miss setups: 48
- Debit signals: 1
- Credit signals: 0
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TLT | debit | bull_ema8_reclaim | 9 | valid_setup | 86 | 0.855 | 4.145 | 0.855 | 4.847953216374268 | 0.33304043472928424 | 0.634988201801339 | Bullish pullback: EMA setup met, liquid quotes: short OI 560, long OI 422, bid/ask 5.7%/1.9%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 67
- watchlist setup; below option evaluation threshold: 62
- near_miss setup; below option evaluation threshold: 48
- no options expirations found: 15
- no/insufficient daily data: 14
- short leg illiquid (vol=1, oi=1): 3
- short leg illiquid (vol=2, oi=6): 3
- spread mid/width too high (32.7%>20.0%): 2
- short leg illiquid (vol=1, oi=16): 2
- spread mid/width too high (32.8%>20.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 235
- SETUP_REJECT: 177
- PRICING_REJECT: 22
- OPTION_CHAIN_REJECT: 16
- DATA_REJECT: 14
- RISK_REJECT: 13

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
