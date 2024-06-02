# EPL Performance Analysis
Data analytics project - EPL Performance analysis

### Project Overview
The EPL Performance Analysis project examines key performance metrics of English Premier League teams, players, and matches using statistical and data visualization techniques to identify trends and insights. The analysis aims to provide a comprehensive understanding of factors influencing team success and player performance.

### Data Sources
Match Data: The primary dataset used for this analysis is the "EPL.csv" file, containing detailed information about EPL matches.

### Tools
PowerBI - Creating reports

### Data Analysis Using Power BI

1. Formula to create MinutesperMatch column
      = MinutesperMatch = EPL_20_21[Mins]/EPL_20_21[Matches]

1. Formula to create GoalsperMatch column
      = GoalsperMatch = EPL_20_21[Goals]/EPL_20_21[Matches]

#### DAX Queries
Create a following meaurements :
1. Total Goals = sum(EPL_20_21[Goals])
1. Total Assists = sum(EPL_20_21[Assists])
1. Expected Goals = sum(EPL_20_21[xG])
1. % of goals against xG = ([Expected Goals]/[Total Goals])*100



