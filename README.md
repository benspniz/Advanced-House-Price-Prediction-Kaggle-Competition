# Advanced-House-Price-Prediction-Kaggle-Competition
Work Log  
1. Handle missing values.    
    - Categorical Features - Impute 'None' for features where NaN means No feature avaialable. Else Impute mode of the feature!  
    - Numerical Features - Impute mean of the feature!  
2. Mean encode the categorical values.  
3. Make Prediction and Submit it to obtain Kaggle Public Leaderboard Score (Evaluation metric Root Mean Squared Logarithmic Error). Scores are:
    * Random Forest Regressor - 0.14344
    * XGBoost Regressor - 0.12712
    * Lasso Regressor - 0.14314
    * Ridge Regressor - 0.13476
    * ElasticNet Regressor - 0.17210
    * Blended Model (XGB, Lasso, Ridge) - 0.12530
    
