# Daily EMA Options Research Summary

- Run timestamp: 2026-09-09_20-02-58
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 59
- Near-miss setups: 62
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AAPL | credit | bear_failed_reclaim | 14 | strong_setup | 100 | 2.0 | 2.0 | 8.0 | 0.25 | 0.769225642383055 | 0.5211921514090471 | Bearish pullup: EMA setup met, liquid quotes: short OI 23062, long OI 14116, bid/ask 4.3%/4.1%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 63
- near_miss setup; below option evaluation threshold: 62
- watchlist setup; below option evaluation threshold: 59
- no/insufficient daily data: 14
- no options expirations found: 11
- options expiration fetch failed: Too Many Requests. Rate limited. Try after a while.: 3
- spread mid/width too high (26.3%>20.0%): 2
- credit/width<20.0% (credit_width=13.3%): 2
- short leg illiquid (vol=9, oi=1444): 2
- short leg illiquid (vol=1, oi=0): 2

## Rejection Classes

- LIQUIDITY_REJECT: 217
- SETUP_REJECT: 184
- PRICING_REJECT: 30
- OPTION_CHAIN_REJECT: 16
- RISK_REJECT: 16
- DATA_REJECT: 14

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
