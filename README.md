# F1 Pit Stop Analysis

**Group 3** — Jack Lichwa, Hemant Kumaar, Prithika K  
**Course**: DATA 5322 — Statistical Machine Learning II, Seattle University

## Project Overview

Formula 1 (F1) is the pinnacle of motorsport, combining elite driver skill with cutting-edge engineering. A critical and often race-deciding element of F1 strategy is the **pit stop**  a brief pause in which a team changes tires, makes aerodynamic adjustments, or responds to race incidents. The duration of a pit stop, even down to fractions of a second, can determine whether a driver retains or loses a podium position.

For top-finishing drivers (those who finish in the top 3), pit stop strategy is especially high-stakes. A slow stop can cost a driver a podium; an efficiently timed stop can vault them ahead of a competitor. Understanding what factors influence the **maximum pit stop duration** experienced by top 3 finishers has implications for race engineering, team strategy optimization, and performance analytics.

This study investigates whether historical race data, tire information, and race conditions can be used to predict the maximum pit stop duration among the top three drivers in a Formula 1 race. Can the maximum pit stop duration for the top 3 drivers in a Formula 1 race be predicted using race context and historical performance data?

## Repository Structure

```
PIT-STOP-ANALYSIS/
├── code/
│   └── F1_PIT_STOP_NOTEBOOK.ipynb       
├── data/
│   ├── f1_top3_pitstop_regression_data.csv    # Race-level dataset (451 races, 2003–2024)
│   └── f1_driver_classification_data.csv      # Driver-level dataset (5,970 entries, 2011–2024)
└── report/
    ├── F1_PitStop_Technical_Report.docx
    └── F1_Pit_Stop_Analysis_Group3.pptx
```

## Data Source

All raw data comes from the [Formula 1 Race Data](https://www.kaggle.com/datasets/jtrotman/formula-1-race-data) dataset on Kaggle (jtrotman), covering F1 history from 1950 onwards.

## Running the Notebook

Open `code/F1_PIT_STOP_NOTEBOOK.ipynb` and run all 

## Notebook Contents

The final notebook covers six labs in sequence:

| Section | Topic |
|---|---|
| LAB 1 | EDA, data cleaning, feature engineering |
| LAB 2 | Regression: Bagging, Random Forest, Gradient Boosting, XGBoost |
| LAB 3 | Classification: SVC baseline |
| LAB 4 | Classification: Linear SVM, RBF SVM, Logistic Regression |
| LAB 8 | PCA: dimensionality reduction + missing value imputation |
| LAB 9 | Clustering: K-Means + Hierarchical |
