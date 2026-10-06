# Cartographies of Educational Risk

Privacy-safe portfolio reconstruction of a year-long educational analytics project on academic performance, attendance, digital participation and contextual inequality.

## Project scale

The original confidential notebook processed a principal attendance/grades table of **1,962,950 rows and 30 columns before cleaning**, plus student/context data and several weekly digital-platform activity sources.

This public repository uses a smaller **synthetic** sample for reproducibility and confidentiality.

## What this repository preserves

- multi-source integration
- documented data-quality and cohort rules
- 11-subject curriculum validation
- subject × period → student-level transformation
- academic trend / variability features
- cumulative attendance transformation and validation
- annual absence, rate and volatility
- chronic absenteeism
- weekly platform activity grouped to academic periods
- platform actions, comments, login-days and task submissions
- period-specific participation thresholds
- exploratory analysis
- chi-square association tests
- Spearman correlation analysis
- urban/rural and over-age comparisons
- educational-risk target definition
- Logistic Regression
- Decision Tree
- Random Forest + GridSearchCV
- XGBoost with imbalance handling and early stopping
- train/test comparison and model-governance discussion

## Original final-model results

The confidential project reported approximately:

| Model | Test Accuracy | Risk Recall |
|---|---:|---:|
| Logistic Regression | 88% | 88% |
| Decision Tree | 89% | 90% |
| Random Forest | 90% | 90% |
| XGBoost | 90% | 89% |

These are documented project results. They are **not** generated from the synthetic public data.

## Privacy

No real student data, institution names, original IDs, exact locations, private file paths or Drive links are included. See `PRIVACY.md`.

## Stack

Python, pandas, NumPy, matplotlib, SciPy, scikit-learn, XGBoost, Jupyter.

## Author

Narella de los Santos
