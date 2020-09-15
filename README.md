# Zimnat_Insurance_top-9
My solution for #9 in privat leaderboard. Score=0.0260809843625832


1. Run Zimnat-lgb_best_score.ipynb. It contains lightgbm and xgboost models with a some preprocessing.
2. Run Zimnat_insurance_cat_target+multy.ipynb. It contains some another and same preprocessing and first: catboost for multiclass; second: catboost for binary with target values.
3. Run Zimnat_insurance_best_multy_overall.ipynb. It contains the same preprocessing and new catboost model. In the end of code you can see blending all models and some postprocessing from statistics.
