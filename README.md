# Genpact-Machine-Learning-Hackathon

This was a machine learning contest on Analytics Vidhya sponsored by Genpact. The challenge was to predict the number of orders for a meal for a given restaurant for the next 15 weeks, provided the meals ordered data for the last 145 weeks and some metadata about the restaurants (city, region, type of restaurant etc.) and meals (category and cuisine of the meal).

I made an ensemble of xgboost and catboost models. Did 10 fold stratified cross-validation over restaurant and meal. Major features were target encoded, time lag features and rolling statistics features (like rolling mean over past few weeks).

Ranked in Top 7 percentile among more than 3800 participants.
