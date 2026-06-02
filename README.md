# Dax Virani - Titanic Data Cleaning

Objective
- Provide a clear, reproducible data cleaning and feature-engineering pipeline for the Titanic dataset to prepare it for modeling.

Steps performed
- Load raw CSV and inspect missingness
- Impute missing values and extract features (Title, Deck, Family size)
- Encode categorical variables and scale numeric features
- Export a model-ready DataFrame for downstream modeling

Tools / Libraries
- pandas, numpy, scikit-learn

Outcome (brief)
- Notebook produces a cleaned dataset and documented feature transformations that can be used directly for training ML models.

How to run

```bash
pip install -r requirements.txt
jupyter lab
jupyter nbconvert --to notebook --execute "Dax Virani - titanic_datacleaning.ipynb" --inplace
```

Notes
- Place the Titanic CSV in the workspace; verify relative path in the first cell.
- Author: Dax Virani
