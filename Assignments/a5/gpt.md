nflgames.csv contains the following columns:
GameID,Week,HomeTeamID,AwayTeamID,HomeScore,AwayScore,DayOfWeek,TimeOfDay,FieldType,Temp,Wind

nflplayers.csv contains the following columns:
PlayerID,PlayerName,PositionID,TeamID

nflposition.csv contains the following columns:
PositionID,PositionName

nflteams.csv contains the following columns:
TeamID,TeamName,TeamCapsAbrv,TeamAbrv



1. Merge the (nfl games dataset with the nfl teams dataset to associate team names with game scores. Then use groupby to find the team with the highest average score per game in the season.

2. Create a new column in the nfl players that records the last name of the players. Are their common last names?

3. Create a pivot table from the (nfl games dataset to show the average HomeScore and AwayScore for each team, broken down by FieldType.

4. On average, how many players does a team have in each position?