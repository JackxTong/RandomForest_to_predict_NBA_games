This was part of the UChicago PATHWAYS IN DATA SCIENCE Summer School project in July-August 2021. 
The summer school was taught by PHILLIP LO and ABBY STEVENS, as an intro to college level machine learning.
The final project was to come up with a model using one of the popular ML algorithm: linear regression, KNN, decision tree... on an online dataset.
I employed [hollinger's team and game datasets](https://www.espn.com/nba/hollinger/teamstats) to train a random forest on three season of NBA games: 18-19, 19-20 and 20-21.

<h2 align="left"> Files:  </h2>

- **game_results_18.csv** : data file for each game in the 18-19 season, with home_team_ID, away_team_ID and 1/0 for home win/loss
- **game_results_19.csv** : data file for each game in the 19-20 season, with home_team_ID, away_team_ID and 1/0 for home win/loss
- **game_results_20.csv** : data file for each game in the 20-21 season, with home_team_ID, away_team_ID and 1/0 for home win/loss
- **team18.csv**: data containing 6 features measuring the performance of every team in that season, and we will use those as predictive variable.
- **NBA_randomforest.ipynb** : Jupyter notebook with python implementation of this project.


<h2 align="left"> Features:  </h2>

- **PACE** : Pace Factor - the number of possessions a team uses per game.
- **AST** : Assist Ratio - the percentage of a team's possessions that ends in an assist.ss
- **TO** : Turnover Ratio - the percentage of a team's possessions that end in a turnover.
- **REBR** : Rebound Rate - the percentage of missed shots that a team rebounds.
- **OFF EFF**: Offensive Efficiency - the number of points a team scores per 100 possessions.
- **DEF EFF**: Defensive Efficiency - the number of points a team allows per 100 possessions.

