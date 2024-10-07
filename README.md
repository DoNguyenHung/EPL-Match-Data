# EPL-Match-Data

Dataset: https://www.football-data.co.uk/englandm.php

I wanted to create a fun little project about whether I could build and test ML models to see if they could predict Premier League games. So I did just that with the following models: 
* Stochastic Gradient Descent (SGD) Classifier
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Classifier (SVC)

If you want to go through how I organize my project, first, check out EDA.ipynb where I did an Exploratory Data Analsysis, filtered, and prepared data for training. Then, go to Train_ML_models.ipynb for how I trained these models and made predictions without betting odds. Finally, you can go to Train_ML_models_with_bets.ipynb to see how the results look different compared to without odds, which is a moderate increase.

If I have more time, I would like to play around more with what additional features I can add and maybe how to rescope the project, as in, instead of trying to predict a full season, I want to see how the results would differ if I make predictions on a per-game basis with more information shown before the whistle is blown, such as the weather, starting lineups, previous yellow card infractions, etc.