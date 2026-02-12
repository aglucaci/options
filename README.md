# Options

This repository hosts the **public-facing output** of the Options workflow.

## Overview

The purpose of this repository is to provide:

-   A clean public data endpoint
-   A lightweight research dashboard
-   Daily high-signal option spread ideas
-   A stable URL for external dashboards and tools



------------------------------------------------------------------------

## Structure

    tables/
        TODAY.csv        # Latest published signal table (auto-updated)

    index.html           # Optional dashboard (GitHub Pages)
    README.md

Only sanitized output is stored here --- no private models or strategy
logic.

------------------------------------------------------------------------

## Data

`TODAY.csv` is refreshed automatically by a scheduled workflow.

Typical fields may include:

-   Ticker / underlying
-   Spread parameters
-   Expected value / edge
-   Signal score
-   Risk metrics
-   Liquidity filters
-   Strategy flags

Column names may evolve as the research workflow improves.

------------------------------------------------------------------------

## GitHub Pages

If enabled, this repository can serve a live dashboard.

To enable:

    Settings → Pages → Deploy from branch → main / root

Your dashboard will then be available at:

    https://aglucaci.github.io/options/

------------------------------------------------------------------------

## Update Pipeline

This repo is **read-only from a development perspective**.

Updates occur via automation:

1.  Private research repository runs strategy workflow
2.  Timestamped tables remain private
3.  A single curated `TODAY.csv` is published here

No manual commits are required.

------------------------------------------------------------------------

## Intended Use

This repository is designed for:

-   Research visualization
-   Signal monitoring
-   Public dashboards
-   Data sharing

It is **not** intended to contain trading logic or proprietary
infrastructure.

------------------------------------------------------------------------

## Disclaimer

This repository is for informational and research purposes only.

Nothing here constitutes financial advice or a recommendation to trade
any security or derivative instrument.

All strategies carry risk.
