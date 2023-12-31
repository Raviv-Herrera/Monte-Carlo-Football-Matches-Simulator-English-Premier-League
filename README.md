# Monte-Carlo-Simulation-English-Premier-League
Monte-Carlo simulation generator for the English-Premier-League (EPL) based on xG model  

## Description 
In this repo I present my implementation for Monte-Carlo football match sumulation for the English Premier League (EPL). 
The simulator is based on my own logic that represents the best simulation conditions for having as much as relaistic results.
The simulator is based on several metrics:
  - xG model
  - Home & Away shots

The data I used was of the last 5 years in the EPL, meaning seasons 2018-2019 up  to 2022-2023. 
I composed and manipulated the data from 2 different resources.
  - https://projects.fivethirtyeight.com/soccer-api/club/spi_matches.csv
  - https://www.football-data.co.uk/englandm.php
 

The results are good and reflect the real world in victory ratio, but when we dive deep and look at the simulated number of goals per game we see sometimes not so realistic results, hence we have here a Simpson's paradix.   

### Note <!> 
This repo is a part of "Prediction of Football Matches" project.

If you desire to learn more about the xG model itself 
- https://statsbomb.com/soccer-metrics/expected-goals-xg-explained/
- https://www.bundesliga.com/en/bundesliga/news/expected-goals-xg-model-what-is-it-and-why-is-it-useful-sportec-solutions-3177
