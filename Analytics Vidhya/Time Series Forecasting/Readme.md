Finished 29/396 in public leaderboard and 66/396 in private leaderboard.

links to the problem statement - https://datahack.analyticsvidhya.com/contest/janatahack-time-series-forecasting

Steps:

1) Creating month,day,week,hour from datetime columns.
2) Creating weekend and important months are created.
3) Creating mean and std for every month and hour combinations.
4) Creating lag columns 
5) while predicting each value are predicted separetely and this value is used to predict next value
6) catboost is used the final model
