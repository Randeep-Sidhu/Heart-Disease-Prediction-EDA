# Heart Disease Prediction: Exploratory Data Analysis

## Overview
This project performs exploratory data analysis (EDA) on the UCI Heart Disease dataset to uncover patterns, clean data, and prepare for machine learning. The goal is to identify risk factors for heart disease using Python (`pandas`, `seaborn`, `scipy`). Key steps include data cleaning, feature engineering, hypothesis testing, and dataset preparation for modeling (e.g., logistic regression).

## Dataset
- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Size**: 920 rows, 16 columns
- **Features**: Age, sex, chest pain type (`cp`), cholesterol (`chol`), target (`num`, binarized as `target`)
- **File**: `heart_disease_uci.csv` (included)

## Key Findings
- **Age**: Older patients (>55) are significantly more likely to have heart disease (t-test, p<0.05).
- **Chest Pain**: Asymptomatic chest pain predicts disease in ~83% of cases.
- **Exercise-Induced Angina**: 80% of patients with `exang=True` have heart disease.
- **Features**: `age`, `cp`, `exang`, `thalch`, `oldpeak` are strong predictors.

## Files
- `eda.ipynb`: Jupyter Notebook with EDA code, visualizations, and outputs.
- `Heart Disease Prediction.pdf`: Detailed report with findings, tables, and plots.
- `heart_disease_uci.csv`: Dataset.


## Tools Used
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
- Jupyter Notebook
- Microsoft Word (for report)

## License
This project uses the UCI Heart Disease dataset, licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).
