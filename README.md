# IPL Mini-Project 2 — Complete Deliverables

**Course:** Data Science Summer Training — Batch 3
**Topic:** Analysis of the IPL Dataset (matches.csv + deliveries.csv)
**Dataset:** Kaggle IPL 2008–2019 (mirrored from the
`aryansinghnaman/ipl-data-analysis` GitHub repository so the project is
reproducible end-to-end without a Kaggle API key).

## Folder layout

```
IPL_Mini_Project_2/
├── README.md                         (this file)
├── insights.json                     (all computed numbers used by report/PPT)
├── data/
│   ├── matches.csv                   (raw — 756 matches)
│   ├── deliveries.csv                (raw — 179,078 deliveries)
│   ├── merged_sample.csv             (first 2 000 rows of the merged df)
│   ├── avg_runs_per_match.csv
│   ├── best_team_per_season.csv
│   ├── top_economy_bowlers.csv
│   └── death_over_stats.csv
├── notebook/
│   └── IPL_Analysis.ipynb            (full Jupyter notebook, Parts A–C)
├── charts/                           (all 8 figures used in the report/PPT)
│   ├── 05_toss_impact.png
│   ├── 05b_toss_by_season.png
│   ├── 06_top10_runs.png
│   ├── 06b_top3_dismissals.png
│   ├── 07_avg_runs_trend.png
│   ├── 07b_regression.png
│   ├── 08_venue_heatmap.png
│   └── 09_death_overs.png
├── report/
│   └── IPL_Mini_Project_2_Report.pdf  (~6-page graded report)
└── ppt/
    └── IPL_Mini_Project_2.pptx        (18-slide presentation)
```

## What each Part covers

| Part | File / asset | Contents |
|------|--------------|----------|
| A.1 Load & merge          | notebook §A1 | 179,078 × 39 merged dataframe across 12 seasons (2008–2019) |
| A.2 Missing data          | notebook §A2 | `city` imputed from venue; `player_of_match` → "No Award"; `dismissal_kind` NaN → "not out" |
| A.3 Feature engineering   | notebook §A3 | `total_runs_calc`, `is_boundary`, `over_phase`, `year`, `month` |
| A.4 Aggregations          | notebook §A4 | Top 5 batsmen, bowler economy (≥500 balls), best team / season |
| B.5 Toss impact           | charts 05/05b | Field-first 55.9 % vs bat-first 45.7 % |
| B.6 Top scorers + dismissals | charts 06/06b | V Kohli leads; "caught" dominates dismissals |
| B.7 Seasonal trend        | charts 07/07b | +3.6 runs/season — IPL is getting more high-scoring |
| B.8 Venue / home advantage | chart 08 | Chinnaswamy (RCB) & Wankhede (MI) strongest home tilt |
| B.9 Death-over performance | chart 09 | CSK = most consistent, RCB = most explosive |
| C  Storytelling           | PDF + PPT | Executive summary, key insights, recommendation, self-reflection |

## How to reproduce

```bash
pip install pandas numpy matplotlib seaborn jupyter nbformat
jupyter notebook notebook/IPL_Analysis.ipynb
```

The notebook is self-contained and uses the CSVs already in `data/`.

## Dataset source

If you specifically need the Kaggle origin, the original dataset is:
**"IPL Complete Dataset (2008-2020)"** by Patrick B. — uploaded to Kaggle as
`patrickb1912/ipl-complete-dataset-2008-2020`. The CSVs included here are the
same 2008–2019 subset and were downloaded from a public GitHub mirror so the
project runs without Kaggle credentials.
