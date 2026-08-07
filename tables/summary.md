# Daily EMA Options Research Summary

- Run timestamp: 2026-08-07_14-37-34
- Rows scanned: 478
- Valid signals: 2
- Watchlist setups: 51
- Near-miss setups: 51
- Debit signals: 1
- Credit signals: 1
- Rejected rows: 476

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BBAI | debit | bull_ema8_pullback | 13 | strong_setup | 133 | 0.16499999999999998 | 0.835 | 0.16499999999999998 | 5.060606060606061 | 0.2237934767497527 | 0.5590758961152205 | Bullish pullback: EMA setup met, liquid quotes: short OI 4893, long OI 4097, bid/ask 11.3%/4.7%, regime accepted. |
| META | credit | bear_ema8_rejection | 15 | strong_setup | 105 | 1.0 | 1.0 | 4.0 | 0.25 | 0.7959882282456873 | 0.5331380997207353 | Bearish pullup: EMA setup met, liquid quotes: short OI 994, long OI 151, bid/ask 5.0%/6.3%, regime accepted. |

## Top Rejection Reasons

- setup_score_below_near_miss_threshold: 68
- near_miss setup; below option evaluation threshold: 51
- watchlist setup; below option evaluation threshold: 51
- no options expirations found: 17
- no/insufficient daily data: 14
- short leg illiquid (vol=0, oi=1): 3
- short leg illiquid (vol=2, oi=2): 3
- short leg illiquid (vol=1, oi=14): 2
- short leg illiquid (vol=0, oi=5): 2
- short leg illiquid (vol=4, oi=1133): 2

## Rejection Classes

- LIQUIDITY_REJECT: 264
- SETUP_REJECT: 170
- OPTION_CHAIN_REJECT: 17
- DATA_REJECT: 14
- PRICING_REJECT: 9
- RISK_REJECT: 2

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
