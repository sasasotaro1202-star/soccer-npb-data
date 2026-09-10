# Soccer & NPB Prediction Data Lake

Google Colab notebook for chronological soccer and baseball prediction data acquisition and feature engineering.

## Notebook

Open `notebooks/sports_prediction_data_lake_colab.ipynb` in Google Colab.

## Sources

- Football-Data.co.uk
- StatsBomb Open Data
- Understat
- MLB Statcast test retrieval
- Authorized manual imports for NPB, licensed player data, odds, weather, injuries, and lineups

## Important

The notebook preserves raw data, records source and ingestion timestamps, builds leak-safe chronological features, writes coverage and quality reports, and exports a ZIP archive. It does not bypass authentication, provider terms, or licensing restrictions.