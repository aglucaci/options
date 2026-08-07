# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_17-30-11
- Rows scanned: 478
- Valid signals: 2
- Watchlist setups: 52
- Near-miss setups: 51
- Debit signals: 1
- Credit signals: 1
- Rejected rows: 476

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BBAI | debit | bull_ema8_reclaim | 14 | strong_setup | 133 | 0.17999999999999994 | 0.8200000000000001 | 0.17999999999999994 | 4.555555555555557 | 0.2433555294944093 | 0.5493464863313188 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 7.1%/4.3%, regime accepted. |
| GOOGL | credit | bear_failed_reclaim | 9 | valid_setup | 105 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7855041316435933 | 0.5292501218662282 | Bearish pullup: EMA setup met, liquid quotes: short OI 2254, long OI 869, bid/ask 3.1%/3.4%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 71
- watchlist setup; below option evaluation threshold: 52
- near_miss setup; below option evaluation threshold: 51
- no options expirations found: 17
- no/insufficient daily data: 14
- short leg illiquid (vol=2, oi=292): 3
- short leg illiquid (vol=1, oi=20): 3
- short leg illiquid (vol=1, oi=7): 3
- spread mid/width too high (26.5%>20.0%): 2
- short leg illiquid (vol=1, oi=14): 2

## Rejection Classes

- LIQUIDITY_REJECT: 241
- SETUP_REJECT: 174
- PRICING_REJECT: 24
- OPTION_CHAIN_REJECT: 17
- DATA_REJECT: 14
- RISK_REJECT: 6

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
