# F1

## Austin GP Winner Predictor

[`Austin_GP_Winner_Predictor.ipynb`](Austin_GP_Winner_Predictor.ipynb) ranks likely winners of the
Austin (United States) Grand Prix from past results, using FastF1 data and an XGBoost / scikit-learn model.

- Open it in Google Colab and run **Runtime → Run all**.
- The target race and all later results are excluded from training; the previous full season is held out for testing.
- Scores are a ranking from historical results, not confirmed win probabilities.
