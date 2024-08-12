![logo](https://github.com/Dhruv3004/T20-World-Cup-2022-Players-Analysis-Power-BI/blob/main/icc-t20-wc-2022-logo-.jpg?raw=true)

## T20 World Cup 2022 Power BI Dashboard

## Project Overview

The primary aim of this Power BI Dashboard project is to identify the best 11 players of the T20 World Cup 2022, based on their performance across various parameters. The dashboard facilitates the selection of top performers in categories such as opening batsmen, middle-order batsmen, all-rounders, and bowlers. By analyzing match summaries, player statistics, and key performance indicators, the dashboard provides a comprehensive view of the tournament.

## Tables Used

## 1. dim_match_summary

Columns: team1, team2, winner, margin, ground, matchDate, match_id
Description: Contains summary information for each match, including the teams involved, the winner, margin of victory, venue, and date.

## 2. dim_players

Columns: name, team, image, battingStyle, bowlingStyle, playingRole, description
Description: Provides detailed information about each player, including their team, batting and bowling styles, playing role, and a brief description.

## 3. fact_batting_summary

Columns: match, teamInnings, battingPos, batsmanName, runs, balls, 4s, 6s, SR, out/not_out, match_id
Description: Contains detailed batting statistics for each player in each match, including runs scored, balls faced, boundaries hit, strike rate, and whether the batsman was out or not.

## 4. fact_bowling_summary

Columns: match, bowlingTeam, bowlerName, overs, maiden, runs, wickets, economy, 0s, 4s, 6s, wides, noBalls, match_id
Description: Contains detailed bowling statistics for each player in each match, including overs bowled, maidens, runs conceded, wickets taken, economy rate, and extras.

## Calculated Columns

1. Boundary Runs Scored (Batsmen)
Created to analyze the contribution of boundaries to a batsman’s total runs.

2. Boundary Runs Conceded (Bowlers)
Created to assess the impact of boundaries on a bowler’s performance.

## Key Measures

Batting:

Average Balls Faced: Calculates the average number of balls faced by a batsman.

Batting Average: Measures the batting average of a player.

Strike Rate: Measures the rate at which a batsman scores runs per 100 balls.

Total Runs: Sum of all runs scored by a batsman.

Batting Position: Determines the position at which a batsman plays in the batting order.

Boundary% Scored: Percentage of runs scored through boundaries.

Total Balls Faced: Sum of all balls faced by a batsman.

Total Innings Batted: Number of innings played by a batsman.

Total Innings Dismissed: Number of times a batsman was dismissed.


Bowling:

Balls Bowled: Total number of balls bowled by a player.

Bowling Strike Rate: Measures the average number of balls bowled per wicket taken.

Bowling Average: Calculates the average runs conceded per wicket.

Dot Ball%: Percentage of dot balls bowled.

Economy: Average runs conceded per over.

Runs Conceded: Total runs conceded by a bowler.

Total Innings Bowled: Number of innings bowled by a player.

Wickets: Total number of wickets taken by a bowler.

## Tooltips

Custom tooltips were created for batsmen, bowlers, and all-rounders, providing additional context and detailed statistics when hovering over visualizations.

