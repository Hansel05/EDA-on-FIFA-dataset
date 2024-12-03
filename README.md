# EDA-on-FIFA-dataset

## Overview
This project involves performing Exploratory Data Analysis (EDA) on the FIFA dataset. The aim is to extract meaningful insights and visualize trends within the dataset, focusing on various aspects such as player attributes, team performances, and other relevant statistics.

## Objectives
Understand the structure and contents of the FIFA dataset.
Identify key insights regarding player and team data.
Perform data cleaning and preprocessing.
Visualize important patterns and trends using graphs and charts.

## Dataset
> The data is updated till 2022.

Dataset description for `fifa_ranking_2022-10-06.csv`.
- `team`: Name of the team
- `team_code`: Name of the team (3 characters)
- `association`: Association responsible to oversee football in that continent
- `rank`: Rank of the team
- `previous_rank`: Previous rank of the team
- `points`: Points earned by the team
- `previous_points`: points earned by the team previously

Dataset description for `world_cup.csv`.
- `Year`: Year in which the FIFA tournament was held
- `Host`: Country that hosted the tournament
- `Teams`: Total number of team that participated in the tournament
- `Champion`: Winner of the tournament
- `Runner-Up`: Runner-Up of the tournament
- `TopScorrer`: Top scorer of the tournament
- `Attendance`: Total number of audience during the tournament
- `AttendanceAvg`: Average number of audience during the tournament
- `Matches`: Total number of matches played during the tournament

Dataset description for `matches_1930_2022.csv`.
- `home_team`: Name of the home team
- `away_team`: Name of the away team
- `home_score`: Goals scored by home team
- `home_xg`: Expected goals by home team
- `home_penalty`: Goals scored by home team during a penalty (incase of a tie)
- `away_score`: Goals scored by away team
- `away_xg`: Expected goals by away team
- `away_penalty`: Goals scored by away team during a penalty (incase of a tie)
- `home_manager`: Manager of home team
- `home_captain`: Captain of home team
- `away_manager`: Manager of away team
- `away_captain`: Captain of away team
- `Attendance`: Total number of audience during the match
- `Venue`: Venue at which the match was held
- `Officials`: Officials of the match (Referee, AR1, AR2, 4th, VAR)
- `Round`: Round of the match
- `Date`: Date on which the match was held
- `Score`: Total score of the match ((home penalty score) home score - (away penalty score) away score)
- `Referee`: Referee of the match
- `Notes`: Extra notes for the match held
- `Host`: Country that hosted the FIFA tournament
- `Year`: Year in which the FIFA tournament was held
- `home_goal`: Name of the player(s) that scored the home goal along with timing
- `away_goal`: Name of the player(s) that scored the away goal along with timing
- `home_goal_long`: Details of goal(s) scored by home team
- `away_goal_long`: Details of goal(s) scored by away team
- `home_own_goal`: Own goal(s) scored by home team
- `away_own_goal`: Own goal(s) scored by away team
- `home_penalty_goal`: Details of penalty goals scored by home team
- `away_penalty_goal`: Details of penalty goals scored by away team
- `home_penalty_miss_long`: Details of missed penalty goals by home team
- `away_penalty_miss_long`: Details of missed penalty goals by away team
- `home_penalty_shootout_goal_long`: Detals of penalty goal(s) shot by home team
- `away_penalty_shootout_goal_long`: Detals of penalty goal(s) shot by away team
- `home_penalty_shootout_miss_long`: Detals of penalty goal(s) missed by home team
- `away_penalty_shootout_miss_long`: Detals of penalty goal(s) missed by away team
- `home_red_card`: Red card given to home team
- `away_red_card`: Red card given to away team
- `home_yellow_red_card`: Yellow card given to home team
- `away_yellow_red_card`: Yellow card given to away team
- `home_yellow_card_long`: Details of yellow card given to player of home team
- `away_yellow_card_long`: Details of yellow card given to player of away team
- `home_substitute_in_long`: Player substitutions for home team
- `away_substitute_in_long`: Player substitutions for away team

## Tools and Technologies
Programming Language: Python

Libraries Used: Pandas, NumPy, Matplotlib, Seaborn
