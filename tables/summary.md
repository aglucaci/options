# Daily EMA Options Research Summary

- Run timestamp: 2026-09-11_17-13-40
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 55
- Near-miss setups: 51
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AMZN | credit | bear_ema8_rejection | 13 | strong_setup | 98 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7896299671392036 | 0.5330423962555346 | Bearish pullup: EMA setup met, liquid quotes: short OI 15513, long OI 23664, bid/ask 3.8%/0.9%, regime accepted. |

## Top Rejection Reasons

- watchlist setup; below option evaluation threshold: 55
- setup_score_below_near_miss_threshold: 53
- near_miss setup; below option evaluation threshold: 51
- no options expirations found: 15
- no/insufficient daily data: 14
- short leg illiquid (vol=1, oi=300): 3
- short leg illiquid (vol=1, oi=58): 2
- spread mid/width too high (32.0%>20.0%): 2
- spread mid/width too high (25.6%>20.0%): 2
- spread mid/width too high (34.8%>20.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 246
- SETUP_REJECT: 159
- PRICING_REJECT: 34
- OPTION_CHAIN_REJECT: 15
- DATA_REJECT: 14
- RISK_REJECT: 9

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
