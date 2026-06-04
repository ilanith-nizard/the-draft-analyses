# F1 Cost Cap Analysis

Companion code for ["when leveling the field doesn't level the field"](https://open.substack.com/pub/thedrafthq/p/when-leveling-the-field-doesnt-level?r=6hubxb&utm_campaign=post&utm_medium=web) — published on The Draft, May 2026.

## What this does
Pulls Formula 1 constructor standings and race results (2014–2024) from the Jolpica F1 API to examine whether the FIA's cost cap, introduced in 2021, actually narrowed the competitive gap between top and bottom teams.

## Key findings
- Top-3 teams' share of total points averaged ~75% pre-cap and ~71.5% post-cap — a modest 3.5 percentage point reduction
- Year-to-year volatility exceeds the cap's average effect
- 2023 had only 3 unique race winners, the lowest since 2015, entirely under the cap

## Data source
[Jolpica F1 API](https://api.jolpi.ca/) — the modern replacement for the deprecated Ergast API

## Requirements
pandas, matplotlib, seaborn, requests

## Author
Ilanith Nizard — [The Draft](https://thedrafthq.substack.com)
