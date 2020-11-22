# `ncaa_basketball.mbb_teams_games_sr`
`bq-1` | `bigquery-public-data`
Team-level box scores from every men's basketball game from the 2013-14 season to the 2017-18 season. Each row shows a single team's stats in one game. This data is identical to mbb_games_sr, but is organized differently to make it easier to calculate a single team's statistics.

Data provided by Sportradar LLC, see www.sportradar.com for more details.

## Column details
* [STRING]    `game_id`
  - [Game data] Unique identifier for the game
* [INTEGER]   `season`
  - [Game data] Season the game was played in
* [STRING]    `status`
  - [Game data] Indicates the last state of Sportradar's game file
* [STRING]    `coverage`
  - [Game data] Type of coverage provided by Sportradar
* [BOOLEAN]   `neutral_site`
  - [Game data] Type of coverage provided by Sportradar
* [DATE]      `scheduled_date`
  - [Game data] Date the game was played
* [TIMESTAMP] `gametime`
  - [Game data] Date and time the game was played
* [BOOLEAN]   `conference_game`
  - [Game data] Indicator of whether the two teams were in the same conference at the time the game was played
* [STRING]    `tournament`
  - [Game data] Whether the game was played in a post-season tournament
* [STRING]    `tournament_type`
  - [Game data] Type of post-season tournament a game was in played
* [STRING]    `tournament_round`
  - [Game data] Tournament round
* [STRING]    `tournament_game_no`
  - [Game data] Tournament game number
* [INTEGER]   `attendance`
  - [Game data] Attendance of the game
* [INTEGER]   `lead_changes`
  - [Game stats] Number of lead changes in the game
* [INTEGER]   `times_tied`
  - [Game stats] Number of ties in the game
* [INTEGER]   `periods`
  - [Game stats] Number of periods the game
* [STRING]    `possession_arrow`
  - [Game stats] The unique identifier of the team that would receive the ball the next time a jump ball is called, see https://en.wikipedia.org/wiki/Jump_ball for more information
* [STRING]    `venue_id`
  - [Game data] Unique identifier for the venue where the game was played
* [STRING]    `venue_city`
  - [Game data] City where the game was played
* [STRING]    `venue_state`
  - [Game data] State where the game was played
* [STRING]    `venue_address`
  - [Game data] Address of the venue where the game was played
* [STRING]    `venue_zip`
  - [Game data] Address of the venue where the game was played
* [STRING]    `venue_country`
  - [Game data] Country where the game was played
* [STRING]    `venue_name`
  - [Game data] Name of the venue where the game was played
* [INTEGER]   `venue_capacity`
  - [Game data] Current capacity of the venue where the game was played
* [BOOLEAN]   `home_team`
  - [Team data] Team was the home team (Note: this doesn't mean the game was played at home because the game could have been played at a neutral site)
* [STRING]    `name`
  - [Team data] Team name
* [STRING]    `market`
  - [Team data] Team school name
* [STRING]    `team_id`
  - [Team data] Team school ID from SportRadar (unique)
* [STRING]    `alias`
  - [Team data] Team school alias (unique)
* [STRING]    `league_id`
  - [Team data] Team school league ID (not unique)
* [STRING]    `league_name`
  - [Team data] Team school league name (not unique)
* [STRING]    `league_alias`
  - [Team data] Team school league alias (not unique)
* [STRING]    `conf_id`
  - [Team data] Team current conference ID (not unique)
* [STRING]    `conf_name`
  - [Team data] Team current conference name (not unique)
* [STRING]    `conf_alias`
  - [Team data] Team current conference alias (not unique)
* [STRING]    `division_id`
  - [Team data] Team current division ID (not unique)
* [STRING]    `division_name`
  - [Team data] Team current division name (not unique)
* [STRING]    `division_alias`
  - [Team data] Team current division alias (not unique)
* [STRING]    `logo_large`
  - [Team data] Team logo 200x200
* [STRING]    `logo_medium`
  - [Team data] Team logo 70x70
* [STRING]    `logo_small`
  - [Team data] Team logo 24x24
* [STRING]    `opp_name`
  - [Opponent data] Opponent name
* [STRING]    `opp_market`
  - [Opponent data] Opponent school name
* [STRING]    `opp_id`
  - [Opponent data] Opponent school ID from SportRadar (unique)
* [STRING]    `opp_alias`
  - [Opponent data] Opponent school alias (unique)
* [STRING]    `opp_league_id`
  - [Opponent data] Opponent school league ID (not unique)
* [STRING]    `opp_league_name`
  - [Opponent data] Opponent school league name (not unique)
* [STRING]    `opp_league_alias`
  - [Opponent data] Opponent school league alias (not unique)
* [STRING]    `opp_conf_id`
  - [Opponent data] Opponent current conference ID (not unique)
* [STRING]    `opp_conf_name`
  - [Opponent data] Opponent current conference name (not unique)
* [STRING]    `opp_conf_alias`
  - [Opponent data] Opponent current conference alias (not unique)
* [STRING]    `opp_division_id`
  - [Opponent data] Opponent current division ID (not unique)
* [STRING]    `opp_division_name`
  - [Opponent data] Opponent current division name (not unique)
* [STRING]    `opp_division_alias`
  - [Opponent data] Opponent current division alias (not unique)
* [STRING]    `opp_logo_large`
  - [Opponent data] Opponent logo 200x200
* [STRING]    `opp_logo_medium`
  - [Opponent data] Opponent logo 70x70
* [STRING]    `opp_logo_small`
  - [Opponent data] Opponent logo 24x24
* [BOOLEAN]   `win`
  - [Team stats] Win
* [INTEGER]   `points_game`
  - [Team stats] Points scored
* [STRING]    `minutes`
  - [Team stats] Total minutes played
* [INTEGER]   `field_goals_made`
  - [Team stats] Field goals made
* [INTEGER]   `field_goals_att`
  - [Team stats] Field goals attempted
* [FLOAT]     `field_goals_pct`
  - [Team stats] Field goal percentage
* [INTEGER]   `three_points_made`
  - [Team stats] Three-pointers made
* [INTEGER]   `three_points_att`
  - [Team stats] Three-pointers attempted
* [FLOAT]     `three_points_pct`
  - [Team stats] Three-point shot percentage
* [INTEGER]   `two_points_made`
  - [Team stats] Two-pointers made
* [INTEGER]   `two_points_att`
  - [Team stats] Two-pointers attempted
* [FLOAT]     `two_points_pct`
  - [Team stats] Two-point shot percentage
* [INTEGER]   `blocked_att`
  - [Team stats] Number of the team's shots blocked by the opponent
* [INTEGER]   `free_throws_made`
  - [Team stats] Free throws made
* [INTEGER]   `free_throws_att`
  - [Team stats] Free throws attempted
* [FLOAT]     `free_throws_pct`
  - [Team stats] Free throw percentage
* [INTEGER]   `offensive_rebounds`
  - [Team stats] Offensive rebounds
* [INTEGER]   `defensive_rebounds`
  - [Team stats] Defensive rebounds
* [INTEGER]   `rebounds`
  - [Team stats] Total rebounds
* [INTEGER]   `assists`
  - [Team stats] Assists
* [INTEGER]   `turnovers`
  - [Team stats] Turnovers
* [INTEGER]   `steals`
  - [Team stats] Steals
* [INTEGER]   `blocks`
  - [Team stats] Blocks
* [FLOAT]     `assists_turnover_ratio`
  - [Team stats] Assist-to-turnover ratio
* [INTEGER]   `personal_fouls`
  - [Team stats] Personal fouls committed
* [INTEGER]   `ejections`
  - [Team stats] Player ejections
* [INTEGER]   `foulouts`
  - [Team stats] Player foul-outs
* [INTEGER]   `points`
  - [Team stats] Total points scored
* [INTEGER]   `fast_break_pts`
  - [Team stats] Fast-break points scored
* [INTEGER]   `second_chance_pts`
  - [Team stats] Second-chance points scored
* [INTEGER]   `team_turnovers`
  - [Team stats] Team turnovers
* [INTEGER]   `points_off_turnovers`
  - [Team stats] Points off turnovers
* [INTEGER]   `team_rebounds`
  - [Team stats] Team rebounds
* [INTEGER]   `flagrant_fouls`
  - [Team stats] Flagrant fouls committed
* [INTEGER]   `player_tech_fouls`
  - [Team stats] Technical fouls committed
* [INTEGER]   `team_tech_fouls`
  - [Team stats] Technical fouls committed by team
* [INTEGER]   `coach_tech_fouls`
  - [Team stats] Technical fouls committed by coach
* [INTEGER]   `opp_points_game`
  - [Opponent stats] Points scored
* [STRING]    `opp_minutes`
  - [Opponent stats] Total minutes played
* [INTEGER]   `opp_field_goals_made`
  - [Opponent stats] Field goals made
* [INTEGER]   `opp_field_goals_att`
  - [Opponent stats] Field goals attempted
* [FLOAT]     `opp_field_goals_pct`
  - [Opponent stats] Field goal percentage
* [INTEGER]   `opp_three_points_made`
  - [Opponent stats] Three-pointers made
* [INTEGER]   `opp_three_points_att`
  - [Opponent stats] Three-pointers attempted
* [FLOAT]     `opp_three_points_pct`
  - [Opponent stats] Three-point shot percentage
* [INTEGER]   `opp_two_points_made`
  - [Opponent stats] Two-pointers made
* [INTEGER]   `opp_two_points_att`
  - [Opponent stats] Two-pointers attempted
* [FLOAT]     `opp_two_points_pct`
  - [Opponent stats] Two-point shot percentage
* [INTEGER]   `opp_blocked_att`
  - [Opponent stats] Number of the opponent's shots blocked by the team
* [INTEGER]   `opp_free_throws_made`
  - [Opponent stats] Free throws made
* [INTEGER]   `opp_free_throws_att`
  - [Opponent stats] Free throws attempted
* [FLOAT]     `opp_free_throws_pct`
  - [Opponent stats] Free throw percentage
* [INTEGER]   `opp_offensive_rebounds`
  - [Opponent stats] Offensive rebounds
* [INTEGER]   `opp_defensive_rebounds`
  - [Opponent stats] Defensive rebounds
* [INTEGER]   `opp_rebounds`
  - [Opponent stats] Total rebounds
* [INTEGER]   `opp_assists`
  - [Opponent stats] Assists
* [INTEGER]   `opp_turnovers`
  - [Opponent stats] Turnovers
* [INTEGER]   `opp_steals`
  - [Opponent stats] Steals
* [INTEGER]   `opp_blocks`
  - [Opponent stats] Blocks
* [FLOAT]     `opp_assists_turnover_ratio`
  - [Opponent stats] Assist-to-turnover ratio
* [INTEGER]   `opp_personal_fouls`
  - [Opponent stats] Personal fouls committed
* [INTEGER]   `opp_ejections`
  - [Opponent stats] Player ejections
* [INTEGER]   `opp_foulouts`
  - [Opponent stats] Player foul-outs
* [INTEGER]   `opp_points`
  - [Opponent stats] Total points scored
* [INTEGER]   `opp_fast_break_pts`
  - [Opponent stats] Fast-break points scored
* [INTEGER]   `opp_second_chance_pts`
  - [Opponent stats] Second-chance points scored
* [INTEGER]   `opp_team_turnovers`
  - [Opponent stats] Opponent turnovers
* [INTEGER]   `opp_points_off_turnovers`
  - [Opponent stats] Points off turnovers
* [INTEGER]   `opp_team_rebounds`
  - [Opponent stats] Opponent rebounds
* [INTEGER]   `opp_flagrant_fouls`
  - [Opponent stats] Flagrant fouls committed
* [INTEGER]   `opp_player_tech_fouls`
  - [Opponent stats] Technical fouls committed
* [INTEGER]   `opp_team_tech_fouls`
  - [Opponent stats] Technical fouls committed by opponent
* [INTEGER]   `opp_coach_tech_fouls`
  - [Opponent stats] Technical fouls committed by coach
* [TIMESTAMP] `created`
  - [Table data] Box score data entry time

-------------------------------------------------------------------------------
*Do not make edits above this line.*
