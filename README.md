# NBA Team Performance Analysis

Uses 30 years of NBA team data (1996–2026) to answer: **do teams win as many games as their team stats say they should?**

A Ridge Regression model predicts expected wins from 17 offensive and defensive team stats. The gap between actual and predicted wins — the **residual** — reveals which teams and coaches consistently over- or underperformed their talent.

## Features

- Pulls live data from the NBA API for every team and season
- Walk-forward model trained only on past seasons (no data leakage)
- **Interactive dropdown menus** (powered by `ipywidgets`) to explore (which are not available in this github format) :
  - 30-year performance charts for any franchise
  - Coaching history by team
  - Season-by-season career breakdowns for any coach
- League-wide coach rankings by residual
- Era-adjusted "most surprising seasons"

## Tools

`nba_api` · `pandas` · `scikit-learn` · `matplotlib` · `ipywidgets`

Open the notebook in Jupyter and run all cells. Use the dropdown menus to explore different teams and coaches interactively — no code changes needed.

## Here's the first chart from this project

<img width="1391" height="980" alt="Screenshot 2026-05-05 223929" src="https://github.com/user-attachments/assets/407aec2a-3fc1-4428-ab70-f4444f1566d8" />

