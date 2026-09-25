# MakerWorld Contest Theme & Category Demand Study

Which 3D design contest themes attract the most makers and attention? This project analyzes 158 MakerWorld contests (Oct 2023 – Sep 2026). It scores each finished contest with a composite KPI, ranks them into S/A/B/C tiers, and compares six theme categories.

- **Interactive report:** https://flaakira.github.io/makerworld-contest-analysis.html
- **Notebook:** `makerworld_contest_analysis.ipynb`
- **Data:** `data/contest_cards.csv` (contest cards), `data/contest_details.csv` (prizes & winners), `data/contests_scored.csv` (final scored dataset)

## Main findings
- 12 holiday contests produced 33.7% of all submitted models and had 4.4x the median participation of other contests.
- Regular contests launched Sep–Dec get 34% fewer participants.
- Engineering & Tech contests draw viewers but have the lowest participation.
- Prize size shows no positive link to participation (Spearman ρ = −0.18).

## Method
Composite score = 40% participants + 30% models/day + 30% views (percentile ranks). Tiers: S top 10%, A next 20%, B middle 40%, C bottom 30%. Data was collected from public MakerWorld pages on 2026-09-25.

Author: Flavio Akira Tikaishi · [Portfolio](https://flaakira.github.io/) · [LinkedIn](https://www.linkedin.com/in/flavio-akira)
