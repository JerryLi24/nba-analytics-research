# NBA Analytics Research

This repository contains the complete codebase, datasets, and analysis for our NBA analytics research paper examining team performance and ranking methodologies across multiple seasons (2016-2024).

## 🏀 Overview

Our research applies advanced statistical modeling and machine learning techniques to analyze NBA team performance, with a focus on logistic regression models for ranking and classification tasks. The study encompasses comprehensive data from regular seasons, playoffs, and play-in tournaments.

## 📁 Repository Structure

### Core Files
- `README.md` - This documentation

### Data

**Game Logs (`gamelogs/`)**
- `nba_games_cleansed.csv` - Cleaned NBA game data
- `nba_games.csv` - Raw NBA game data

**Standings (`standings/`)**  
- `standing_2016.csv` to `standing_2024.csv` - Season standings by year

### Code

**Data Cleaning (`cleaning_code/`)**
- `parse.ipynb` - Data parsing notebook
- `preprocessing.ipynb` - Data preprocessing  
- `scrape.ipynb` - Web scraping scripts
- `sort_by_year.ipynb` - Temporal data organization

**Statistical Models (`models/` and `tables/`)**

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

## 🔄 Reproducibility

All analysis is fully reproducible:
1. Clone this repository
2. Install requirements
3. Run Jupyter notebooks in specified order (need to change the directories accordingly)
4. Results will match published findings

## 📈 Data Sources

- NBA official statistics
- Historical game logs (2016-2024)
- Regular season standings

## 🏆 Results

Our analysis provides:
- Team ranking algorithms with statistical validation
- Performance prediction models
- Comprehensive statistical tables
- Visualization of trends and patterns

## 📝 Citation

If you use this research or data in your work, please cite:

```
[Li & Jabbari] (2025). NBA Analytics Research: Advanced Statistical Modeling 
for Team Performance and Ranking. GitHub Repository.
https://github.com/JerryLi24/nba-analytics-research
```
