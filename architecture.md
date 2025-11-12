# Architecture (simple)

data/
  churn_dataset.csv  -- source synthetic data

src/
  data_pipeline.py   -- loading & preprocessing
  train.py           -- train & save model
  predict.py         -- predict on new data

notebooks/
  01_exploration_and_features.ipynb
  02_modeling_and_evaluation.ipynb

app/
  dashboard.py       -- Streamlit app for visualization & predictions

artifacts/
  model.pkl
  metrics.json
  sample_predictions.csv

CI: .github/workflows/ci.yml
Tests: tests/test_data_pipeline.py
