# Tableau Dashboard

## [👉Exploring NBA Players' Salary and Their Performance](https://public.tableau.com/views/502465_IndividualDashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)


## Dataset Description

The dataset contains two parts. The first is the salary data for each NBA player in each season from 1985 to 2018. The second is an additional part with the players’ information, including basic information (name / height / weight / college / draft pick / etc.) and performance indicators (points / assists / rebounds / field goal percentage / etc.). 

The dataset was collected and cleaned by Chris Davis on data.world (https://data.world/datadavis/nba-salaries), and the original source was basketball reference (https://www.basketball-reference.com).

## Design Concept

This dashboard aims to explore the relationship between the salary of NBA players and its possible factors, including the season they played in, players’ performance (points per game / win share), and players’ draft pick. 

For the first graph on the upper right, I used a box plot to show the distribution of each players’ salary across seasons. We learned that NBA players’ average salary increased over time, possibly due to inflation and the ease of the league’s salary cap. However, we can observe some outliers in earlier periods, especially Michael Jordan during the years of 1996~1998. 

Next, in the lower-left chart, I examined the relationship between salary and players’ performance. I compared the R-square for salary and different performance indicators (points / assists / rebounds / field goal percentage / etc.), and picked out the two most correlated variables, points per game and win share. I used a parameter for the viewers to choose between the two variables. To learn more about players’ performance regarding their salary, I added a quadrant using average salary and points / win share, so we could see clearly who was receiving high salary but having poor performance, and vice versa. Furthermore, to remove the effect of different seasons, I set an interactive filter so the viewers can browse within a single season. 

Lastly, I used a bar chart to show the average salary for each draft pick. Since players with higher draft picks were usually considered with higher potential, their salary tended to be higher as well. Additionally, I implemented a dashboard filter action, so when the viewers clicked on a specific bar, the two other graphs would show only the players in that draft pick. 
