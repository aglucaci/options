# Daily EMA Options Research Summary

- Run timestamp: 2026-09-10_20-02-31
- Rows scanned: 478
- Valid signals: 1
- Watchlist setups: 46
- Near-miss setups: 65
- Debit signals: 0
- Credit signals: 1
- Rejected rows: 477

## Top Ranked Signals

| ticker | spread | setup_family | setup_score | setup_tier | dte | spread_mid | max_profit | max_loss | reward_risk | pop | risk_adjusted_score | signal_reason |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MSFT | credit | bear_continuation | 9 | valid_setup | 99 | 1.0 | 1.0 | 4.0 | 0.25 | 0.778457748586874 | 0.5214139878225061 | Bearish pullup: EMA setup met, liquid quotes: short OI 2753, long OI 4897, bid/ask 5.2%/5.7%, regime accepted. |

## Top Rejection Reasons

- market regime blocks bullish debit spread: 114
- near_miss setup; below option evaluation threshold: 65
- setup_score_below_near_miss_threshold: 61
- watchlist setup; below option evaluation threshold: 46
- no/insufficient daily data: 14
- no options expirations found: 11
- credit/width<20.0% (credit_width=19.0%): 4
- credit/width<20.0% (credit_width=9.5%): 2
- credit/width<20.0% (credit_width=16.5%): 2
- short leg illiquid (vol=0, oi=1): 2

## Rejection Classes

- SETUP_REJECT: 172
- LIQUIDITY_REJECT: 143
- REGIME_REJECT: 114
- RISK_REJECT: 22
- DATA_REJECT: 14
- OPTION_CHAIN_REJECT: 11
- PRICING_REJECT: 1

## Research Notice

Research output only. Not financial advice. Options involve risk, liquidity constraints,
assignment/expiration risk, and execution assumptions that may differ from live fills.
