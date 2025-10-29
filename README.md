# Movie Data Analysis

## Project Overview
End-to-end exploratory data analysis of 4,803 movies to uncover commercial success patterns and global market dynamics.

## Key Findings
- **Revenue Drivers**: vote_count is strongest predictor (60% influence via SHAP)
- **Market Segments**: 3 distinct country clusters by genre preferences  
- **Seasonal Trends**: $3,845 daily growth with summer peaks (+$38M in June)
- **Budget Patterns**: Significant differences across genres (Action: $80M vs Documentary: $0.5M)

## Technical Stack
Python, Pandas, Scikit-learn, SHAP, Statistical Testing, Data Visualization

## Methods Used
- Data cleaning & feature engineering
- Random Forest + SHAP interpretation  
- K-Means clustering (63 countries)
- Time series decomposition
- Statistical testing (Kruskal-Wallis, Spearman correlation)

## Quick Start
```bash
pip install pandas scikit-learn matplotlib seaborn shap
jupyter notebook 50087310.ipynb
