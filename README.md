# Coach-I-want-to-play-
Operation Research Project - provide a baseline rotation strategy based on the basketball players' fantasy point to theoretically maximize the team’s potential.


## Context
This project builds four models to solve the problem of how to arrange players based on their scoring ability (fantasy points) in a basketball game. The objective of all four models is to maximize the sum of fantasy points in a forty-eight-minute basketball game. The construction of the four models’ constraints is mainly a gradual exploration of the characteristics of the players’ scoring ability and physical strength in an actual situation.

## Dataset
To model the problem, we gathered 3 seasons (from 2019 to 2021) NBA players statistics of team Golden State Warriors, Dallas Mavericks, and LA Lakers. The features include players’ Team, position played, height, weight, the year they were born to calculate age, average time played per game, and RPM which indicates overall how well they played. (124 records, 9 features)

## Insights
The goal is to provide a baseline rotation strategy that theoretically maximizes the team’s potential. Then, in reality, the coach can use our result as a default rotation and modify it given particular game circumstances.
From the improved model, due to the introduction of the stamina decrease rate, the best fantasy dropped from 847.53 to 506.12. We can see more players participating in the game, especially the guard position. In addition, new players generally enter the late game. This is because compared with key players, they did not have a high fantasy point at the beginning. 
After considering the stamina recovery rate, the objective has increased from 506.12 to 561.81. The star players have more contributions in the later stage of the game than the previous model.
The situation is in line with reality. When the star players are exhausted, other players start to replace them temporarily. After the star players' physical strength recoveres, they will take the lead again.

## Collaborators
Pei Qin
Miao He
Shaobin Qiao
Yuankai Ma
Jiankun Wang
