# Bike Sharing Demand Prediction

Regression project predicting daily bike rentals.# Bike Sharing Demand Prediction

Regression project predicting daily bike rentals using machine learning and deep learning models (ANN, Tuned SVR, and Tuned XGBoost).

## Project Overview
This project analyzes bike-sharing demand data to predict daily rental counts. It includes data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

## Models Evaluated
- **Artificial Neural Network (ANN)**
- **Tuned Support Vector Regression (SVR)**
- **Tuned XGBoost Regressor** (Best performing model with R²: ~0.867 and lowest test errors)

## Dataset
- **File:** `day.csv` (contains 731 daily records with weather and seasonal features).
- Ensure `day.csv` is placed in the root directory alongside the Jupyter Notebook.

## Project Structure & Setup
1. **Jupyter Notebook:** Open `Bike_sharing_analysis.ipynb` and run all cells sequentially.
2. **Dependencies:** Install required libraries listed in `requirements.txt`.
3. **Saved Models:** The notebook automatically creates a `saved_models/` directory and saves the following artifacts using `joblib`:
   - `saved_models/best_xgboost_model.pkl`
   - `saved_models/best_xgboost_model.json`
   - `saved_models/feature_preprocessor.pkl`

## License
MIT License
