# Milestone II: NFL Game Outcome Prediction

## Project Overview
Replication of Ethan Dinh's NFL prediction project using machine learning to forecast NFL game outcomes. This implementation reproduces the original methodology with enhanced reproducibility and extended evaluation metrics.

## Original Work: Ethan Dinh's NFL-Prediction
Repository: https://github.com/ethan-dinh/NFL-Prediction

## Dataset
Source: Historical NFL game data (1980-2022)
Files:
- nfl_games.csv - Game statistics and outcomes
- nfl_teams.csv - Team information and mappings
- spreadspoke_scores.csv - Betting spreads and scores

## Requirements
pip install -r requirements.txt

## Key Dependencies
- Python 3.8+
- scikit-learn 1.3+
- pandas 1.5+
- numpy 1.21+
- matplotlib 3.5+
- xgboost 1.7+
- hyperopt 0.2+


## Project Structure
MilestoneII_Machine/
- repro_m2.ipynb          # Main implementation
- Data/                      # Dataset directory
  - nfl_games.csv
  - nfl_teams.csv
  - spreadspoke_scores.csv
- README.md

## Reproducibility
- Random Seed: 42 (ensures identical results across runs)
- Fixed Splits: 70-30 train-test split
- Stratified CV: 5-fold cross-validation
- Environment: Exact package versions specified

## Models Implemented
1. Logistic Regression with GridSearchCV
2. Random Forest with Hyperopt optimization
3. XGBoost with Hyperopt optimization

## Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- AUROC, Confusion Matrices
- Temporal validation (2019+ seasons)
- Statistical significance testing

## Results
- Model performance comparison with original study
- Hyperparameter tuning visualizations
- Classification metric curves (ROC, Precision-Recall)
- Extrapolation analysis on unseen data

## Attribution
Core Methodology: Ethan Dinh
Implementation: Johnathan Gutierrez-Diaz
Course: Machine Learning Milestone II
Date: October 2025
