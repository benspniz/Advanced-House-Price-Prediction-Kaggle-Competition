# Advanced-House-Price-Prediction-Kaggle-Competition
Work Log 
1. Remove the author identified outliers
2. Log transform the target to get a normal distribution. 
1. Handle missing values. (Separately for train and test to avoid leakage) 
    * Categorical Features - Impute 'None' for features where NaN means No feature available. Else Impute mode of the feature!  
    * Numerical Features - Impute median of the feature!  
2. Mean encode the categorical values.  
3. Make Prediction and Submit it to obtain Kaggle Public Leaderboard Score (Evaluation metric Root Mean Squared Logarithmic Error). Scores are:
    * Random Forest Regressor - 0.14344
    * XGBoost Regressor - 0.12611
    * Lasso Regressor - 0.13425
    * Ridge Regressor - 0.13409
    * ElasticNet Regressor - 0.13425
    * Blended Model (XGB, Ridge, ElasticNet, Lasso) - 0.12558




    
    
