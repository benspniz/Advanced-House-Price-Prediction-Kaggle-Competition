# Advanced-House-Price-Prediction-Kaggle-Competition
Work Log  
1. Handle missing values.    
    - Categorical Features - Impute 'None' for features where NaN means No feature avaialable. Else Impute mode of the feature!  
    - Numerical Features - Impute mean of the feature!  
2. Mean encode the categorical values.  
3. Make Prediction and Submit it to obtain Kaggle Public Leaderboard Score (Evaluation metric RMSE). Scores are:
    * Random Forest Regressor Model 1 - 0.14929 
    * Random Forest Regressor Model 3 - 0.14846