# Daily EMA Options Research Summary

- Run timestamp: 2026-06-17_16-51-21
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 44
- Near-miss setups: 31
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AAPL | credit | bear_ema8_rejection | 14 | strong_setup | 93 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7782474982696702 | 0.524355689773937 | Bearish pullup: EMA setup met, liquid quotes: short OI 7983, long OI 5490, bid/ask 3.8%/4.7%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 110
- watchlist setup; below option evaluation threshold: 44
- near_miss setup; below option evaluation threshold: 31
- no options expirations found: 17
- no/insufficient daily data: 12
- short leg illiquid (vol=1, oi=1): 4
- short leg illiquid (vol=0, oi=1): 2
- short leg bid/ask too wide (15.4%>15.0%): 2
- short leg illiquid (vol=6, oi=5245): 2
- short leg bid/ask too wide (22.9%>15.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 225
- SETUP_REJECT: 185
- RISK_REJECT: 20
- PRICING_REJECT: 18
- OPTION_CHAIN_REJECT: 17
- DATA_REJECT: 12

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
