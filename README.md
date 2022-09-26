## Overview  

The National Basketball Association (NBA) is a professional basketball league in North America. The league comprises 30 teams (29 in the United States and 1 in Canada) and is one of the four major professional sports leagues in the United States and Canada. It is the premier men's professional basketball league in the world. [source of information: [Wikipedia](https://en.wikipedia.org/wiki/National_Basketball_Association)]  

Career longevity is dependent on various factors for any player in all the games and so for NBA Rookies. The factors like games played, count of games played, and other statistics of the player during the game.


## Objective
 
Using machine learning techniques determine if a player’s career will flourish or not.


## About the data
The dataset contains player statistics for NRB Rookies. There are 1100+ observations in the train dataset with 19 variables excluding the target variable (i.e. Target).

 
#### Data Description

- GP: Games Played (here you might find some values in decimal, consider them to be the floor integer, for example, if the value is 12.789, the number of games played by the player is 12)
- The values for given attributes are averaged over all the games played by players
- MIN:  Minutes Played
- PTS: Number of points per game
- FGM: Field goals made
- FGA: Field goals attempt
- FG%: field goals percent
- 3P Made: 3 point made
- 3PA: 3 points attempt
- 3P%: 3 point percent
- FTM: Free throw made
- FTA: Free throw attempts
- FT%: Free throw percent
- OREB: Offensive rebounds
- DREB: Defensive rebounds
- REB: Rebounds
- AST: Assists
- STL: Steals
- BLK: Blocks
- TOV: Turnovers
- Target: 0 if career years played < 5, 1 if career years played >= 5



*You should submit a CSV file with a header row and the sample submission can be found below:*

prediction

1
0
0
0
0
1
0
1
.
.
.
Etc.

Note that the header name should be ‘prediction’