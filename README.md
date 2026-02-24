# Kaggle-Assignments-Combined

A combined archive of my Kaggle competition/assignment notebooks (EDA → feature engineering → model training/tuning → submission generation).

## Highlights
- Multiple submissions ranked **Top 50** on the leaderboard; some reached **Top 10** (per my Kaggle results).

## Notebooks
- **Assignment / Competition 1 (Regression):**
  - `22f3003226-ka-1-final.ipynb`
  - `22f3003226-mlp-ka1-final.ipynb`

- **Assignment / Competition 2 (Classification):**
  - `ka-2-train.ipynb`
  - `22f3003226-ka2.ipynb`

- **Assignment / Competition 3 (NLP Sentiment Classification):**
  - `ka3-22f3003226.ipynb`
  - `22f3003226-mlp-ka3.ipynb`

## Common workflow in these notebooks
1. Load Kaggle input datasets (`/kaggle/input/...`)
2. Basic EDA + missing values + duplicates + outlier review
3. Preprocessing pipelines (scaling + encoding / TF-IDF)
4. Train multiple models + compare metrics
5. Hyperparameter tuning for selected models
6. Create `submission.csv`

## How to run
These notebooks are written for the Kaggle runtime paths. To run locally:
- Update dataset paths (replace `/kaggle/input/...` with local file paths), or
- Run directly on Kaggle by uploading the notebook(s) and attaching the corresponding dataset/competition.

## Notes
- Some notebooks may contain saved cell outputs/plots; optionally clear outputs before committing for smaller diffs.
- Filenames reflect the original submission context and are kept unchanged.

