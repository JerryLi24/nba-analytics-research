# NBA Analytics Research

This repository contains the complete codebase, datasets, and analysis for our NBA analytics research paper examining team performance and ranking methodologies across multiple seasons (2016-2024).

## 🏀 Overview

Our research applies advanced statistical modeling and machine learning techniques to analyze NBA team performance, with a focus on logistic regression models for ranking and classification tasks. The study encompasses comprehensive data from regular seasons, playoffs, and play-in tournaments.

## 📁 Repository Structure

### Core Files
- `README.md` - This documentation
- `index.md` - GitHub Pages homepage  
- `_config.yml` - Site configuration

### Documentation (`docs/`)
- `paper.pdf` - Full research paper
- `methodology.md` - Detailed methodology

### Data (`data/`)

**Game Logs (`gamelogs/`)**
- `nba_games_cleansed.csv` - Cleaned NBA game data
- `nba_games.csv` - Raw NBA game data  
- `playin.csv` - Play-in tournament data
- `playoffs_2016.csv` to `playoffs_2024.csv` - Playoff data by season

**Standings (`standings/`)**  
- `standing_2016.csv` to `standing_2024.csv` - Season standings by year

**Analysis Tables (`tables/`)**
- `pseudo_r_squared_cleansed_total.csv` - Complete pseudo R² results
- `pseudo_r_squared_cleansed.csv` - Cleaned pseudo R² analysis  
- Additional statistical output tables

### Code (`code/`)

**Data Cleaning (`cleaning_code/`)**
- `parse.ipynb` - Data parsing notebook
- `preprocessing.ipynb` - Data preprocessing  
- `scrape.ipynb` - Web scraping scripts
- `sort_by_year.ipynb` - Temporal data organization

**Statistical Models (`models/`)**
- `Ranking_group_logreg_overall.ipynb` - Overall ranking model
- `Ranking_group_logreg.ipynb` - Group-based ranking model  
- `tbl_pseudor.ipynb` - Pseudo R-squared analysis
- `tbl_reg.ipynb` - Regression tables
- `tbl_stats.ipynb` - Statistical summaries

### Results (`results/`)
- `figures/` - Generated visualizations
- `tables/` - Output tables and results

## 🔬 Research Components

### Data Collection & Processing
- **Web Scraping**: Automated data collection from NBA sources
- **Data Cleaning**: Comprehensive preprocessing and validation
- **Temporal Organization**: Multi-season data structuring (2016-2024)

### Statistical Modeling
- **Logistic Regression**: Team ranking and classification models
- **Pseudo R-squared Analysis**: Model performance evaluation
- **Group-based Analysis**: Hierarchical team performance modeling

### Analysis Scope
- **Regular Season**: Complete game logs and standings
- **Playoffs**: Tournament bracket analysis and predictions
- **Play-in Tournament**: Recent format analysis (2021-2024)

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Analysis
1. **Data Preparation**: Run notebooks in `code/cleaning_code/` in order:
   ```
   parse.ipynb → preprocessing.ipynb → sort_by_year.ipynb
   ```

2. **Statistical Modeling**: Execute analysis notebooks in `code/models/`:
   ```
   Ranking_group_logreg.ipynb
   Ranking_group_logreg_overall.ipynb
   tbl_stats.ipynb
   tbl_reg.ipynb
   tbl_pseudor.ipynb
   ```

3. **Results**: Generated tables and figures will be saved to `results/`

## 📊 Key Findings

- Comprehensive analysis of NBA team performance metrics
- Novel ranking methodologies using logistic regression
- Multi-season trend analysis and predictive modeling
- Statistical validation through pseudo R-squared metrics

## 📖 Documentation

- **Full Paper**: [docs/paper.pdf](./docs/paper.pdf)
- **Methodology**: [docs/methodology.md](./docs/methodology.md)
- **GitHub Pages Site**: [https://yourusername.github.io/nba-analytics-research](https://yourusername.github.io/nba-analytics-research)

## 🔄 Reproducibility

All analysis is fully reproducible:
1. Clone this repository
2. Install requirements
3. Run Jupyter notebooks in specified order
4. Results will match published findings

## 📈 Data Sources

- NBA official statistics
- Historical game logs (2016-2024)
- Playoff and regular season standings
- Play-in tournament data (2021-2024)

## 🏆 Results

Our analysis provides:
- Team ranking algorithms with statistical validation
- Performance prediction models
- Comprehensive statistical tables
- Visualization of trends and patterns

## 📝 Citation

If you use this research or data in your work, please cite:

```
[Your Name] (2025). NBA Analytics Research: Advanced Statistical Modeling 
for Team Performance and Ranking. GitHub Repository. 
https://github.com/yourusername/nba-analytics-research
```

## 🤝 Contributing

This is an open-source research project. Contributions are welcome:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Author**: [Your Name]
- **Email**: [your.email@university.edu]
- **Institution**: [Your Institution]
- **Research Group**: [Your Research Group/Lab]

## 🔗 Links

- **Live Site**: https://yourusername.github.io/nba-analytics-research
- **Paper**: [Link to published paper when available]
- **Data**: All datasets included in this repository
- **Code**: Complete analysis pipeline in Jupyter notebooks

---

*This research was conducted in the spirit of open science and reproducible research. All data, code, and results are freely available for academic and research purposes.*
