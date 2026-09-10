# Soccer & Baseball Prediction Data Lake

GitHub中心で運用する、サッカー・野球予測モデル用の時系列データ基盤です。

## Colab smoke test

[Open the smoke-test notebook in Colab](https://colab.research.google.com/github/sasasotaro1202-star/soccer-npb-data/blob/main/notebooks/colab_smoke_test.ipynb)

The smoke test verifies Python, pandas, Parquet, chronology checks, feature generation, and ZIP export without requiring private API keys.

## Scope

- Soccer: Football-Data.co.uk, StatsBomb Open Data, Understat where available
- Baseball: MLB public data / Statcast where available, and authorized NPB files supplied by the user
- Storage: GitHub for code and small manifests; Google Drive or other authorized storage for large RAW files
- Validation: chronological ordering, prediction cutoff, duplicate detection, missingness, and leakage flags

No authentication, paywall, robots policy, or provider terms are bypassed. Licensed or private data must be placed in `dropzone/` only when the user is authorized to use it.
