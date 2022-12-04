# RainInAustralia


Description :

This project predicts whether it will rain next day  by training classification models on a number of attributes and the target variable RainTomorrow.

Dataset :

This dataset contains about 10 years of daily weather observations from many locations across Australia.
RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.

Shape - (145460 x 23)

Languages and libraries:

This project uses python3, sklearn, numpy, pandas, xgboost in kaggle jupyter notebook environment.

Models and techniques used :
 1. DecisiontreeClassifier, RandomForestClassifier, XGBClassifier.
 2. PermutationImportance for feature importance, pca for dimensionality reduction and RandomizedSearchCV to find parameters for the models.
