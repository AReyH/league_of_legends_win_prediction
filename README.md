# League of Legends Win Prediction Model: Project Overview:

This is the notebook I used to write my [Medium article.](https://medium.com/swlh/league-of-legends-win-prediction-5f5516c4b1d7)

This is a project aimed to predict which team will by the 10 minute mark. You can try this out yourself by downloading the model.pkl and scaler.pkl files and using it in your own notebook.

- Created a tool to predict the outcome of a game besed on in game stats.
- Downloaded dataset from [Kaggle](https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min).
- Selected features based on feature correlation and feature importance.
- Obtained a 73% accuracy only using a select number of features.

## Requirements
- **Python Version:** 3.7.10
- **Packages:** Numpy, Pandas, Sklearn, Matplotlib, Seaborn.

## Results
Even though the accuracy is only about 73%, this might be attributed to the random events throughout a game that are not present in the data collected. These unaccounted events can be a player disconnecting or just post 10 minute mistakes.

The image below shoes the confusion matrix for the test set.
[!alt text](https://github.com/AReyH/league_of_legends_win_prediction/blob/main/images/cm_1.png)
