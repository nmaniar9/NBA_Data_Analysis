# NBA_Data_Analysis
Exploring NBA data from 1979 to 2022.

Data being explored : https://www.kaggle.com/datasets/loganlauton/nba-players-and-team-data
Tableau dashboard: https://public.tableau.com/app/profile/neil.maniar/viz/NBAplayeroverview/Dashboard1

File:
NBA_Project(1).

concepts and ideas learned: Exploratory data analysis with Python Pandas, grouping, querying, and filtering data. Plotting with matplotlib and plotly. Tableau dashboarding; filtering, calculated fields, data coversion, plotting comparison charts.

I explore the 4 datasets that are included in the kaggle datasets. first loading in the data sets and filtering them down to seasons after 1979. To me this marks the start of the modern NBA when the three point line was introduced. I use various data exploration and cleaning functions within the Python Pandas library including .describe(), .duplicate(), and .info(). 

Next, I explored the data sets to see various trends in the NBA, including how points rebounds and assists have increased over the last 50 seasons. using .groupby(), .query() and other data filtering methods. I plotted the various changes for the totals as well as breaking down how each postion has changed. For example, the small forward postion was the only postion whose points scored by players in that postions decreased over the 50 year period. 

Lastly, I explored the plus_minus statistic for players. the plus_minus stats was introduced in the 2007 season to better grasp how players impact games. I explored players whose avg points per game over their careers was greater than 20. we see that the players have a wide variety of plus_minus scores, but it is clear of those player the ones with high plus_minus's are the ones who have won the most shares of games.

The Tableau dashboard looks at the each player individually and their career statistics. We also look at the trends of the players statistics as well as compares them with other players using dot plots


