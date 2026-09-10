# Daily EMA Options Research Summary

- Run timestamp: 2026-09-10_17-11-58
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 58
- Near-miss setups: 63
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GOOGL | credit | bear_ema8_rejection | 14 | strong_setup | 99 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7810816910912812 | 0.5206258917417885 | Bearish pullup: EMA setup met, liquid quotes: short OI 12755, long OI 2448, bid/ask 5.1%/7.1%, regime accepted. |

## Top Rejection Reasons

- market regime blocks bullish debit spread: 110
- near_miss setup; below option evaluation threshold: 63
- setup_score_below_near_miss_threshold: 61
- watchlist setup; below option evaluation threshold: 58
- no/insufficient daily data: 14
- no options expirations found: 11
- credit/width<20.0% (credit_width=19.0%): 4
- short leg illiquid (vol=1, oi=58): 2
- credit/width<20.0% (credit_width=15.5%): 2
- short leg illiquid (vol=0, oi=1): 2

## Rejection Classes

- SETUP_REJECT: 182
- LIQUIDITY_REJECT: 144
- REGIME_REJECT: 110
- RISK_REJECT: 15
- DATA_REJECT: 14
- OPTION_CHAIN_REJECT: 11
- PRICING_REJECT: 1

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
