# Google Play Store App Rating Prediction with ML

A machine learning project focusing on **regression** to predict the user rating of applications listed on the Google Play Store based on their attributes.

---

## Goal
Build and evaluate a Machine Learning model to accurately predict the `Rating` of an app, utilizing features like installs, reviews, category, and price.

---

## Dataset
- **Source:** [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Description:** Contains data on over 10,000 apps, including key metrics such as `Rating` (target variable), `Reviews`, `Installs`, `Category`, and `Price`.

---

## Approach
- **Data Cleaning & Preprocessing:** Handled missing values, converted string columns (e.g., `Size`, `Installs`, `Price`) to numerical types.
- **Data Transformation:** Applied Transformation to the target and highly skewed features.
- **Model Training:** The model used was an **XGBoost Regressor** trained and evaluated to predict app ratings.

---

## How to Use
- Clone this repo: `git clone https://github.com/danial-baraty/google-play-rating-predictor.git`
- Install dependencies: `pip install pandas numpy scikit-learn seaborn xgboost`
- Run the Jupyter notebook: `Google_Play_Store_App_Rating_Prediction_with_ML.ipynb`
