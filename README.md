# Magnus Carlsen Lichess Games Dataset Analysis
 Magnus Carlsen Lichess Games Dataset Analysis
The raw data set is too large to be uploaded to github. It can be seen here: https://www.kaggle.com/zq1200/magnus-carlsen-lichess-games-dataset



Main visualization:
![image](https://user-images.githubusercontent.com/85703853/162316504-ebc260df-88ce-4298-917e-bdc7616833a4.png)

Fractional score is calculated by wins + ties * 0.5 divided by total number of games. 
Average opponent rating is the average opponent rating in the games that meet the shown condition (color, year, first move, time control)

Main takeaways:

Correlation coefficient is -0.7 and r^2 is 0.494. This means about half of the variance in fractional score is due to opponent rating.

g6 stands out a lot as the best 1st move for black.

d4 stands out a lot as the best 1st move for white.

Not 1+0 stands out as a bad time control for Magnus.

2018 stands out of a bad year for Magnus.

Magnus clearly plays better as White than as Black.
