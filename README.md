# league_of_legends_ml
### Exploring league of legends with machine learning.
Blog post [here](https://medium.com/@lawsus/total-gold-prediction-in-league-of-legends-using-champion-stats-68cc9bf5f3ff)

### [data](data)
* data_857.csv contains data from 857 matches
* [kaggle link](https://www.kaggle.com/datasets/lawsus/lolstats) contains data from 8792 matches
* data 0-3 is from the process of collecting larger dataset
* matches.json contains matchIds of 8792 matches collected from 160 high elo players on the NA server

### [graphs](raphs)
* all_features_857.png is a feature importance plot using all features from 857 matches
* only_stats_857.png is a feature importance plot using only champion stats from 857 matches
* learning_curve_857.png is a learning curve from using deep learning on only champion stats from 857 matches
* only_stats_8792.png is a feature importance plot using only champion stats from 8792 matches

### [notebook](notebook)
* lol_machine_learning.ipynb is the google colab notebook used for this experiment
