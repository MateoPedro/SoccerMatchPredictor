# CS 4641 Group 1: 2022 Qatar World Cup Predictions

1. Introduction/Background

   > We’ll build the machine learning model to predict the result of the soccer game, especially for the upcoming 2022 Qatar World Cup. Predicting sports is a typical classification problem, which involves predicting the target variable in previously unseen data [1]. Since it is one of the common machine learning tasks, some sports prediction models are on the market. The model that we’ll build will be based on the factors involved in the game: the scores of past matches, and the player performance indicators. We will use the Kaggle FIFA World Cup matches dataset containing historical match results and the FIFA22 complete player dataset including the stats of each player in FIFA22.

2. Problem Definition

   > Predicting the outcome of sports interests anyone who loves sports. People like sports because they cannot know the result beforehand, but it is also fun to guess the results and compare them after matches. We want to build a prediction system that we can use for the upcoming World Cup in November. There are various sports prediction systems on the market, but none can be said to be the answer. Therefore, we thought it would be interesting and meaningful to use Machine Learning techniques in our way to building the model.

3. Methods

   > For this topic, there was a 2017’s Soccer Prediction Challenge where 13 groups of researchers competed to find the best machine learning model with given historical soccer match data. Team with the 2nd lowest average ranked probability score used a gradient boosted tree algorithm based on customized ratings of each team [2]. Winning team who obtained the lowest ranked probability score used the k-nearest neighbor model trained on match performance of each team [3]. However, the same researchers later improved the performance by adopting an ensemble of extreme gradient boosted trees, also known as XGBoost [3]. Given prior works on the topic, we plan to explore Linear Regression and XGboost(one of the Gradient boosting models) and compare their accuracies. One innovation that we will implement is that we have a dataset of the positions of all players in the squad, which would result in a more accurate performance measure of each team. So using the mentioned models, we plan to incorporate past international match histories and player ratings to accurately predict the result of the 2022 World Cup.

4. Potential Results and Discussion

   > By using historical FIFA World Cup games outcomes and players' ratings, we will be able to assemble a model that will achieve the following: predicting the outcome of every game (winner or a draw) including the knockout stage and the final. It will therefore predict the winner of the world cup. Having a perfect World Cup bracket is almost as unlikely as getting a perfect March Madness bracket. Results might not all be right as Soccer can be a very surprising sport where probabilities are often beaten. However, we hope to get acceptable range of values in quantitative metrics that we set, which could include accuracy, log-loss, f1-score, ranked probability score, etc.

5. References

   > - [1] Bunker, R. P., & Thabtah, F. (2019, January). A machine learning framework for sport result prediction. ScienceDirect. Retrieved October 4, 2022, from https://www.sciencedirect.com/science/article/pii/S2210832717301485
   > - [2] Hubáček, O., Šourek, G. & Železný, F. Learning to predict soccer results from relational data with gradient boosted trees. Mach Learn 108, 29–47 (2019). https://doi.org/10.1007/s10994-018-5704-6
   > - [3] Berrar, D., Lopes, P. & Dubitzky, W. Incorporating domain knowledge in machine learning for soccer outcome prediction. Mach Learn 108, 97–126 (2019). https://doi.org/10.1007/s10994-018-5747-8

6. Proposed Timeline (Please look at the "Fall" and "Fall Overview" tabs on the spreadsheet)

   > https://docs.google.com/spreadsheets/d/1ChYJgCThu9E_JKUZpXNkgquKj2bVRdus/edit#gid=2088064368

7. Contribution Table

   > ![image](https://user-images.githubusercontent.com/114958485/194668051-93b98063-6ade-473d-8653-01ec66f9a5e1.png)

8. Datasets

   > - FIFA22 player stats dataset: https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset
   > - 2022 FIFA Worldcup Qatar FULL LIVE DATASET: https://www.kaggle.com/datasets/muhammad4hmed/2022-fifa-worldcup-qatar-full-live-dataset
   > - International football results from 1872 to 2022: https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

9. Video Link
   > https://youtu.be/Az87T_d1q0k
