# Daily EMA Options Research Summary

- Run timestamp: 2026-09-04_19-53-46
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 55
- Near-miss setups: 56
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GOOGL | credit | bear_ema8_rejection | 19 | strong_setup | 77 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7727332529384402 | 0.5231751344634135 | Bearish pullup: EMA setup met, liquid quotes: short OI 1872, long OI 1315, bid/ask 3.7%/4.2%, regime accepted. |

## Top Rejection Reasons

- near_miss setup; below option evaluation threshold: 56
- watchlist setup; below option evaluation threshold: 55
- setup_score_below_near_miss_threshold: 49
- no options expirations found: 17
- no/insufficient daily data: 14
- spread mid/width too high (29.8%>20.0%): 2
- short leg bid/ask too wide (19.4%>15.0%): 2
- short leg illiquid (vol=32, oi=26): 2
- spread mid/width too high (30.5%>20.0%): 2
- short leg illiquid (vol=11, oi=1227): 2

## Rejection Classes

- LIQUIDITY_REJECT: 230
- SETUP_REJECT: 160
- PRICING_REJECT: 39
- OPTION_CHAIN_REJECT: 17
- RISK_REJECT: 17
- DATA_REJECT: 14

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
