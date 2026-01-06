# Car Price Prediction & Data Parsing

## Overview
This project combines web data parsing with a car price prediction pipeline. It includes data collection, preprocessing, EDA, model training, and evaluation for price prediction tasks.

## Project Structure
- `parsing.ipynb` — notebook for parsing/scraping raw car listings data.
- `sf-dst-car-price-prediction.ipynb` — notebook for preprocessing, EDA, and model training.
- `readme.md` — original project notes (English).

## Data
The parsing notebook gathers raw listings data, and the prediction notebook uses cleaned datasets for modeling. See the notebooks for data sources and ingestion steps.

## Requirements
- Python 3.x
- Jupyter Notebook/Lab
- pandas, numpy, scikit-learn
- Optional: requests/bs4 or other scraping libraries, depending on parsing implementation

## Usage
1. Run `parsing.ipynb` to collect or refresh raw data (optional).
2. Open `sf-dst-car-price-prediction.ipynb` to preprocess data, train models, and evaluate predictions.

## Results
Model metrics and analysis results are embedded in the notebook outputs.

## Notes
- Parsing may require rate limiting or pauses to avoid request throttling.
- Update any paths or data source configurations inside the notebooks as needed.
