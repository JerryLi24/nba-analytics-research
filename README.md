# NBA-Game-Predictors/
├── README.md
├── index.md (or index.html)
├── _config.yml
├── docs/
│   ├── paper.pdf
│   └── methodology.md
├── data/
│   ├── gamelogs/
│   │   ├── nba_games_cleansed.csv
│   │   ├── nba_games.csv
│   │   ├── playin.csv
│   │   ├── playoffs_2016.csv
│   │   ├── playoffs_2017.csv
│   │   └── [all other playoff files...]
│   ├── standings/
│   │   ├── standing_2016.csv
│   │   ├── standing_2017.csv
│   │   └── [all other standing files...]
│   └── tables/
│       ├── pseudo_r_squared_cleansed_total.csv
│       ├── pseudo_r_squared_cleansed.csv
│       └── [other analysis tables...]
├── code/
│   ├── cleaning_code/
│   │   ├── parse.ipynb
│   │   ├── preprocessing.ipynb
│   │   ├── scrape.ipynb
│   │   └── sort_by_year.ipynb
│   └── models/
│       ├── Ranking_group_logreg_overall.ipynb
│       ├── Ranking_group_logreg.ipynb
│       ├── tbl_pseudor.ipynb
│       ├── tbl_reg.ipynb
│       └── tbl_stats.ipynb
└── results/
    ├── figures/
    └── tables/
