---
priority: 0.6
title: NBA Trading Algorithm — Pricing Edges from Player Metrics
excerpt: Price games from player metrics (DARKO), schedule effects, and lineups to spot mispriced lines.
categories: works
background-image: works-sample.png
tags:
  - Python
  - Pandas
  - Web Scraping
---

#### Results

- 19% increase in M, measured by N
- ...

#### Summary

I price NBA games using player-level signals and compare to the market. Better numbers → better lines.

**Signals** — DARKO trends, rest/fatigue, lineup changes, home/away, travel.  
**Model** — Elo baseline + logistic blend, calibrated to avoid overconfidence.  
**Backtests** — Walk-forward; realistic costs; CLV vs close.  
**Results** — _Hit-rate, CLV, tiny equity curve screenshot._  
**Next** — Injury nowcasting; Bayesian lineup uncertainty; execution hooks.