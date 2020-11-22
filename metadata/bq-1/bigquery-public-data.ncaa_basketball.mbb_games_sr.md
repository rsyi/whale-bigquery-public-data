# `ncaa_basketball.mbb_games_sr`
`bq-1` | `bigquery-public-data`
Team-level box scores from every men's basketball game from the 2013-14 season to the 2017-18 season. Each row shows both teams' stats for that one game.

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
  - [Game data] Indicator of whether the game was played on a neutral court
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
* [STRING]    `h_name`
  - [Home Team data] Home team name
* [STRING]    `h_market`
  - [Home Team data] Home team school name
* [STRING]    `h_id`
  - [Home Team data] Home team school ID from SportRadar (unique)
* [STRING]    `h_alias`
  - [Home Team data] Home team school alias (unique)
* [STRING]    `h_league_id`
  - [Home Team data] Home team school league ID (not unique)
* [STRING]    `h_league_name`
  - [Home Team data] Home team school league name (not unique)
* [STRING]    `h_league_alias`
  - [Home Team data] Home team school league alias (not unique)
* [STRING]    `h_conf_id`
  - [Home Team data] Home team current conference ID (not unique)
* [STRING]    `h_conf_name`
  - [Home Team data] Home team current conference name (not unique)
* [STRING]    `h_conf_alias`
  - [Home Team data] Home team current conference alias (not unique)
* [STRING]    `h_division_id`
  - [Home Team data] Home team current division ID (not unique)
* [STRING]    `h_division_name`
  - [Home Team data] Home team current division name (not unique)
* [STRING]    `h_division_alias`
  - [Home Team data] Home team current division alias (not unique)
* [STRING]    `h_logo_large`
  - [Home Team data] Home team logo 200x200
* [STRING]    `h_logo_medium`
  - [Home Team data] Home team logo 70x70
* [STRING]    `h_logo_small`
  - [Home Team data] Home team logo 24x24
* [INTEGER]   `h_points_game`
  - [Home Team stats] Home points scored
* [INTEGER]   `h_rank`
  - [Home Team stats] Home rank
* [STRING]    `h_minutes`
  - [Home Team stats] Home total minutes played
* [INTEGER]   `h_field_goals_made`
  - [Home Team stats] Home field goals made
* [INTEGER]   `h_field_goals_att`
  - [Home Team stats] Home field goals attempted
* [FLOAT]     `h_field_goals_pct`
  - [Home Team stats] Home field goal percentage
* [INTEGER]   `h_three_points_made`
  - [Home Team stats] Home three-pointers made
* [INTEGER]   `h_three_points_att`
  - [Home Team stats] Home three-pointers attempted
* [FLOAT]     `h_three_points_pct`
  - [Home Team stats] Home three-point shot percentage
* [INTEGER]   `h_two_points_made`
  - [Home Team stats] Home two-pointers made
* [INTEGER]   `h_two_points_att`
  - [Home Team stats] Home two-pointers attempted
* [FLOAT]     `h_two_points_pct`
  - [Home Team stats] Home two-point shot percentage
* [INTEGER]   `h_blocked_att`
  - [Home Team stats] Number of the home team's shots blocked by the away team
* [INTEGER]   `h_free_throws_made`
  - [Home Team stats] Home free throws made
* [INTEGER]   `h_free_throws_att`
  - [Home Team stats] Home free throws attempted
* [FLOAT]     `h_free_throws_pct`
  - [Home Team stats] Home free throw percentage
* [INTEGER]   `h_offensive_rebounds`
  - [Home Team stats] Home offensive rebounds
* [INTEGER]   `h_defensive_rebounds`
  - [Home Team stats] Home defensive rebounds
* [INTEGER]   `h_rebounds`
  - [Home Team stats] Home total rebounds
* [INTEGER]   `h_assists`
  - [Home Team stats] Home assists
* [INTEGER]   `h_turnovers`
  - [Home Team stats] Home turnovers
* [INTEGER]   `h_steals`
  - [Home Team stats] Home steals
* [INTEGER]   `h_blocks`
  - [Home Team stats] Home blocks
* [FLOAT]     `h_assists_turnover_ratio`
  - [Home Team stats] Home assist-to-turnover ratio
* [INTEGER]   `h_personal_fouls`
  - [Home Team stats] Home personal fouls committed
* [INTEGER]   `h_ejections`
  - [Home Team stats] Home player ejections
* [INTEGER]   `h_foulouts`
  - [Home Team stats] Home player foul-outs
* [INTEGER]   `h_points`
  - [Home Team stats] Home total points scored
* [INTEGER]   `h_fast_break_pts`
  - [Home Team stats] Home fast-break points scored
* [INTEGER]   `h_second_chance_pts`
  - [Home Team stats] Home second-chance points scored
* [INTEGER]   `h_team_turnovers`
  - [Home Team stats] Home team turnovers
* [INTEGER]   `h_points_off_turnovers`
  - [Home Team stats] Home points off turnovers
* [INTEGER]   `h_team_rebounds`
  - [Home Team stats] Home team rebounds
* [INTEGER]   `h_flagrant_fouls`
  - [Home Team stats] Home flagrant fouls committed
* [INTEGER]   `h_player_tech_fouls`
  - [Home Team stats] Home technical fouls committed
* [INTEGER]   `h_team_tech_fouls`
  - [Home Team stats] Home technical fouls committed by team
* [INTEGER]   `h_coach_tech_fouls`
  - [Home Team stats] Home technical fouls committed by coach
* [STRING]    `a_name`
  - [Away Team data] Away team name
* [STRING]    `a_market`
  - [Away Team data] Away team school name
* [STRING]    `a_id`
  - [Away Team data] Away team school ID from SportRadar (unique)
* [STRING]    `a_alias`
  - [Away Team data] Away team school alias (unique)
* [STRING]    `a_league_id`
  - [Away Team data] Away team school league ID (not unique)
* [STRING]    `a_league_name`
  - [Away Team data] Away team school league name (not unique)
* [STRING]    `a_league_alias`
  - [Away Team data] Away team school league alias (not unique)
* [STRING]    `a_conf_id`
  - [Away Team data] Away team current conference ID (not unique)
* [STRING]    `a_conf_name`
  - [Away Team data] Away team current conference name (not unique)
* [STRING]    `a_conf_alias`
  - [Away Team data] Away team current conference alias (not unique)
* [STRING]    `a_division_id`
  - [Away Team data] Away team current division ID (not unique)
* [STRING]    `a_division_name`
  - [Away Team data] Away team current division name (not unique)
* [STRING]    `a_division_alias`
  - [Away Team data] Away team current division alias (not unique)
* [STRING]    `a_logo_large`
  - [Away Team data] Away team logo 200x200
* [STRING]    `a_logo_medium`
  - [Away Team data] Away team logo 70x70
* [STRING]    `a_logo_small`
  - [Away Team data] Away team logo 24x24
* [INTEGER]   `a_points_game`
  - [Away Team stats] Away points scored
* [INTEGER]   `a_rank`
  - [Away Team stats] Away rank
* [STRING]    `a_minutes`
  - [Away Team stats] Away total minutes played
* [INTEGER]   `a_field_goals_made`
  - [Away Team stats] Away field goals made
* [INTEGER]   `a_field_goals_att`
  - [Away Team stats] Away field goals attempted
* [FLOAT]     `a_field_goals_pct`
  - [Away Team stats] Away field goal percentage
* [INTEGER]   `a_three_points_made`
  - [Away Team stats] Away three-pointers made
* [INTEGER]   `a_three_points_att`
  - [Away Team stats] Away three-pointers attempted
* [FLOAT]     `a_three_points_pct`
  - [Away Team stats] Away three-point shot percentage
* [INTEGER]   `a_two_points_made`
  - [Away Team stats] Away two-pointers made
* [INTEGER]   `a_two_points_att`
  - [Away Team stats] Away two-pointers attempted
* [FLOAT]     `a_two_points_pct`
  - [Away Team stats] Away two-point shot percentage
* [INTEGER]   `a_blocked_att`
  - [Away Team stats] Number of the away team's shots blocked by the away team
* [INTEGER]   `a_free_throws_made`
  - [Away Team stats] Away free throws made
* [INTEGER]   `a_free_throws_att`
  - [Away Team stats] Away free throws attempted
* [FLOAT]     `a_free_throws_pct`
  - [Away Team stats] Away free throw percentage
* [INTEGER]   `a_offensive_rebounds`
  - [Away Team stats] Away offensive rebounds
* [INTEGER]   `a_defensive_rebounds`
  - [Away Team stats] Away defensive rebounds
* [INTEGER]   `a_rebounds`
  - [Away Team stats] Away total rebounds
* [INTEGER]   `a_assists`
  - [Away Team stats] Away assists
* [INTEGER]   `a_turnovers`
  - [Away Team stats] Away turnovers
* [INTEGER]   `a_steals`
  - [Away Team stats] Away steals
* [INTEGER]   `a_blocks`
  - [Away Team stats] Away blocks
* [FLOAT]     `a_assists_turnover_ratio`
  - [Away Team stats] Away assist-to-turnover ratio
* [INTEGER]   `a_personal_fouls`
  - [Away Team stats] Away personal fouls committed
* [INTEGER]   `a_ejections`
  - [Away Team stats] Away player ejections
* [INTEGER]   `a_foulouts`
  - [Away Team stats] Away player foul-outs
* [INTEGER]   `a_points`
  - [Away Team stats] Away total points scored
* [INTEGER]   `a_fast_break_pts`
  - [Away Team stats] Away fast-break points scored
* [INTEGER]   `a_second_chance_pts`
  - [Away Team stats] Away second-chance points scored
* [INTEGER]   `a_team_turnovers`
  - [Away Team stats] Away team turnovers
* [INTEGER]   `a_points_off_turnovers`
  - [Away Team stats] Away points off turnovers
* [INTEGER]   `a_team_rebounds`
  - [Away Team stats] Away team rebounds
* [INTEGER]   `a_flagrant_fouls`
  - [Away Team stats] Away flagrant fouls committed
* [INTEGER]   `a_player_tech_fouls`
  - [Away Team stats] Away technical fouls committed
* [INTEGER]   `a_team_tech_fouls`
  - [Away Team stats] Away technical fouls committed by team
* [INTEGER]   `a_coach_tech_fouls`
  - [Away Team stats] Away technical fouls committed by coach
* [TIMESTAMP] `created`
  - [Table data] Box score data entry time

-------------------------------------------------------------------------------
*Do not make edits above this line.*
