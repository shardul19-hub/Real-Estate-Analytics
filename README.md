# Notebooks

The full analytical pipeline, in order:

| Notebook | Purpose |
|---|---|
| [`01_etl_pipeline.ipynb`](01_etl_pipeline.ipynb) | Data ingestion, cleaning, LINC drift reconciliation (`Base_Address` engineering), neighbourhood crosswalk, ghost asset classification |
| [`02_feature_engineering_geocoding.ipynb`](02_feature_engineering_geocoding.ipynb) | Pre-modeling transformation: F1–F5 engineered features, the 5-layer offline geocoding pipeline, Bank of Canada mortgage rate sync |
| [`03_modeling_and_forecasting_final.ipynb`](03_modeling_and_forecasting_final.ipynb) | Final modeling notebook — OLS / Random Forest / Gradient Boosting comparison and SARIMA forecasting. Matches the results reported in the final report (R² = 0.9922, MAE = $16,536) |

## `earlier-iterations/`

Two earlier modeling drafts are kept here to show how the model evolved through iteration — from an initial baseline pass to a revised version before reaching the final, reported results:

- `modeling_draft_v1.ipynb` — first modeling pass
- `modeling_draft_v2_revised.ipynb` — revised version after initial feedback, before final tuning

These aren't dead weight — they're evidence of iterative refinement (a real part of the data science process), not just a single polished output.
