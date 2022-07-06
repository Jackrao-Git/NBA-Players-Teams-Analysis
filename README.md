# NBA-Players-Teams-Analysis

The data analytical project focuses on the players stats and teams stats of the NBA from season 1996-1997 to 2020-2021. Data is downloaded from Kaggle.

Questions to be answered:
1. How has the average height, average weight, average age of players changed during this period?
2. How many 1st round picked players are from the US and how many are not from the US?
3. What are the top 10 players leading in points, rebounds, assists in this period?

Preparation stage:
Season is not consistently formatted so have to do some works in the excel before getting them to python. 
Missing data and NaN content are removed before analysis

There are 11700 rows, which means 11700 units of players in all seasons of this period.
Note: Players' height are in cm, players' weight are in kg.

![df info](https://user-images.githubusercontent.com/108682585/177452748-c2957159-e67d-4b75-b64b-b59a17fe2bae.PNG)

![des](https://user-images.githubusercontent.com/108682585/177452772-d27aa27f-a97f-43ba-afab-b1a924252d95.PNG)


PS: It's interesting to see the gp, which stands for game played has the maximum of 85 in a season. This is not an error as NBA records the game played by the team a player represents. The player may be traded to a team that will be played multiple times in the mid of a season and that would count twice in the game played by this player who are traded.


Question 1:

![vt](https://user-images.githubusercontent.com/108682585/177453779-2c6ae428-5f46-4a4c-89d7-aa1a2afe1fc4.PNG)

![height](https://user-images.githubusercontent.com/108682585/177453848-d90f2cd1-f632-4e2f-bd12-40dbb385d0bf.PNG)

Thanks to Golden States Warriors, the average height of players is decreasing and the trend is likely to continue as they won it again this year...

![weight](https://user-images.githubusercontent.com/108682585/177453946-6a4b2f7e-3a83-45ac-9a55-1828c9bb272b.PNG)

Decreasing weight makes sense as more players shoot 3s and less post ups. Players would be lighter generally as the height is decreaing as well.

![age](https://user-images.githubusercontent.com/108682585/177453961-23ab8d74-bb01-41e8-87b1-17948bf694d5.PNG)

More and more younger rookies are getting in the league.



Question 2:

![111](https://user-images.githubusercontent.com/108682585/177456351-6de183f0-77d5-4d8a-b27d-7ffb11389e2c.PNG)

Around 18.2% of the 1st round picked players are from outside of the United States


Question 3:

Scoring:
![scoring](https://user-images.githubusercontent.com/108682585/177456955-02a9c0d3-2451-4c00-bb98-c04685350d78.PNG)
AI and KD are great scorers

Assisting:
![assist](https://user-images.githubusercontent.com/108682585/177456973-b51bc490-25c7-4feb-9ee4-b2eafa67630e.PNG)
Kidd and Nash... Okay

Rebounding:
![rebound](https://user-images.githubusercontent.com/108682585/177456999-5012a5ad-dd77-4c9e-8fac-0d184e9f03df.PNG)
Familiar names


All 3 questions solved and I love doing analysis on NBA!!!




