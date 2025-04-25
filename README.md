# Self-Organizing Map

Custom **Self-Organizing Map** implementation on the UCI Bank Marketing dataset —
preprocessing, dimensionality reduction, and classifier evaluation on SOM-reduced features.

Built for an Artificial Neural Networks course assignment.

## What this project covers

- Categorical encoding and missing-value handling
- SOM training with 2D/8D/4D reductions and classifier comparison (Q1)
- SOM visualization, hyperparameter grid search, and clustering (Q2–Q4)
- Comparison with PCA and t-SNE (Q5)

## Project layout

| File | Description |
|------|-------------|
| `main.ipynb` | Preprocessing, SOM, and experiments |
| `Project_Description.pdf` | Assignment brief |
| `Report.pdf` | Report |
| `requirements.txt` | Python dependencies |

## Quick start

```bash
python -m venv .venv
.venv\Scripts\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

The dataset is fetched via `ucimlrepo` at runtime. Notebook outputs are saved so plots render on GitHub.
