# Daily EMA Options Research Summary

- Run timestamp: 2026-09-11_20-03-31
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 58
- Near-miss setups: 52
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AMZN | credit | bear_ema8_rejection | 13 | strong_setup | 98 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7830770885672048 | 0.5309222190937598 | Bearish pullup: EMA setup met, liquid quotes: short OI 15513, long OI 23664, bid/ask 2.9%/1.7%, regime accepted. |

## Top Rejection Reasons

- watchlist setup; below option evaluation threshold: 58
- near_miss setup; below option evaluation threshold: 52
- setup_score_below_near_miss_threshold: 49
- no options expirations found: 16
- no/insufficient daily data: 14
- spread mid/width too high (32.5%>20.0%): 3
- short leg illiquid (vol=1, oi=300): 3
- spread mid/width too high (32.2%>20.0%): 3
- long leg bid<0.05 (bid=0.02): 2
- credit/width<20.0% (credit_width=15.0%): 2

## Rejection Classes

- LIQUIDITY_REJECT: 231
- SETUP_REJECT: 159
- PRICING_REJECT: 41
- OPTION_CHAIN_REJECT: 16
- RISK_REJECT: 16
- DATA_REJECT: 14

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
