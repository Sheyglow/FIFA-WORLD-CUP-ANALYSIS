# FIFA-WORLD-CUP-ANALYSIS (Data Analytics Team 2)
Football World Cup also called FIFA meaning Federation Internationale de Football Association, is an international association football competition contested by the senior men’s national teams. The championship has been awarded every four years since the inaugural tournament in 1930, except in 1942 and 1946 which explains the gaps in our analysis, this was due to the Second World War.

# Background and Findings
As a team, work on a football world cup analysis using data from 1930 till the present. Scrap, clean, and visualize with Power BI. <br />
Your dashboard must show the following: <br />
Number of world cup winning title. <br />
Attendance. <br />
Number of teams. <br />
Goals and matches per cup. <br />
Goals per team per world cup. <br />
Matches with the highest attendance. <br />
Stadium with the highest average attendance. <br />
Which countries had won the world cup. <br />
Number of goals per country and match outcome by home and away. <br />

# Data Sourcing and Cleaning
The dataset was gotten from Kaggle. <br />
The process of cleaning the dataset was done partly on Excel and most of it was done on Power bi, the 2018 dataset was missing we had to source for it online, then removed the columns that are not needed and duplicates was removed, then the dataset was loaded into Power bi query where we corrected the spelling errors, removed the time from the date column, added a new column which we called fixtures that gotten from the away team name and home team name, added another column called unique fixture this was gotten by merging the fixture and match ID.

![Fifa_table](https://user-images.githubusercontent.com/109004397/201990870-b6bbcc4a-e39c-4087-a6c1-0731378172c8.jpeg)

# Insights

Figure 1

![Fifa_fig 1](https://user-images.githubusercontent.com/109004397/201991399-e376fb38-9477-4959-b080-e973f134f13e.jpeg)

The daashboard above (fig.1) shows that the world cup had been played for a total of 21times and a total of 9 countries had won the world cup since inception. Brazil had won the cup for 5 times which makes them the country with the highest cup wins. <br />
The second tile shows that Home teams had the highest number of wins at 504times.
<br />
<br />
<br />
Figure 2

![Fifa_fig 2](https://user-images.githubusercontent.com/109004397/201992036-bb06ab55-d58a-4822-a052-47296624c752.jpeg)

A total of 2,548goals had been score in all from 900 fixtures. Year 1998 recorded the highest world cup goals at 171goals. The trend of the countries involvement can also be seen. (fig.2)
<br />
<br />
<br />
Figure 3

![Fifa_fig 3](https://user-images.githubusercontent.com/109004397/201992500-578ba31a-ca2c-451d-9746-97c5a89db80b.jpeg)

A record of over 4million fans had watched the world cup between 1930 and 2018 while a total of 192 stadia had been used. A top and bottom 10 analysis of fixture and stadium were also done. The match between Uruguay and Brazil recorded the highest number of spectators while Chile vs France recorded the lowest. Maracana stadium has the highest average attendance in history while Pocitos stadium has the lowest average attendance. (fig.3)
<br />
<br />
<br />
Figure 4

![Fifa_fig 4](https://user-images.githubusercontent.com/109004397/201992791-341e3153-3b6e-436d-aab1-58225e8debe1.jpeg)

The attendance by year and the number of qualified team for each world cup year.
<br />
<br />
<br />
Figure 5

![Fifa_fig 5](https://user-images.githubusercontent.com/109004397/201993163-33ad93f5-6c9a-48e9-a4c7-b01a5e4a8ee2.jpeg)

This shows an analysis of the goals each country scored at every of their world cup appearance. This can be sliced or formatted by the Country slicer in order to drill down or more specific.
