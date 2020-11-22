# `ncaa_basketball.mbb_historical_teams_games`
`bq-1` | `bigquery-public-data`
Final scores for men's basketball games, starting with the 1996-97 season. Each game is included twice, with one entry per team. 

Data provided by the NCAA.

## Column details
* [INTEGER]   `season`
  - [Game data] Season the game was played in
* [STRING]    `scheduled_date`
  - [Game data] Date the game was played
* [FLOAT]     `attendance`
  - [Game data] Attendance of the game
* [STRING]    `market`
  - [Team data] Team school name (using Sportradar names)
* [STRING]    `name`
  - [Team data] Team name
* [STRING]    `team_code`
  - [Team data] School code (see http://stats.ncaa.org/game_upload/team_codes)
* [STRING]    `team_id`
  - [Team data] Sportradar team ID
* [STRING]    `alias`
  - [Team data] Team alias
* [STRING]    `current_division`
  - [Team data] The division the team currently plays in
* [INTEGER]   `points_game`
  - [Game data] Points scored by team
* [BOOLEAN]   `win`
  - [Game data] Whether the team won the game
* [STRING]    `opp_market`
  - [Opponent data] Opponent school name (using Sportradar names)
* [STRING]    `opp_name`
  - [Opponent data] Opponent name
* [INTEGER]   `opp_code`
  - [Opponent data] Opponent school code (see http://stats.ncaa.org/game_upload/team_codes)
* [STRING]    `opp_id`
  - [Opponent data] Opponent school ID (using Sportradar IDs)
* [STRING]    `opp_alias`
  - [Opponent data] Opponent alias
* [STRING]    `opp_current_division`
  - [Opponent data] The division the opponent currently plays in
* [INTEGER]   `opp_points_game`
  - [Opponent data] Points scored by opponent

-------------------------------------------------------------------------------
*Do not make edits above this line.*
