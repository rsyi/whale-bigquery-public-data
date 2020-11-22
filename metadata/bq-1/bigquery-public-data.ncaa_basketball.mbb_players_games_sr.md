# `ncaa_basketball.mbb_players_games_sr`
`bq-1` | `bigquery-public-data`
Player-level box scores from every men's basketball game from the 2013-14 season to the 2017-18 season. Each row shows a single player's stats in one game.

Data provided by Sportradar LLC, see www.sportradar.com for more details.

## Column details
* [STRING]    `game_id`
  - [Game data] Unique identifier for the game
* [INTEGER]   `season`
  - [Game data] Season the game was played in
* [BOOLEAN]   `neutral_site`
  - [Game data] Indicator of whether the game was played on a neutral court
* [DATE]      `scheduled_date`
  - [Game data] Date the game was played
* [TIMESTAMP] `gametime`
  - [Game data] Date and time the game was played
* [STRING]    `tournament`
  - [Game data] Whether the game was played in a post-season tournament
* [STRING]    `tournament_type`
  - [Game data] Type of post-season tournament a game was in played
* [STRING]    `tournament_round`
  - [Game data] Tournament round
* [STRING]    `tournament_game_no`
  - [Game data] Tournament game number
* [STRING]    `player_id`
  - [Player info] Player Sportradar player ID
* [STRING]    `last_name`
  - [Player info] Player last name
* [STRING]    `first_name`
  - [Player info] Player first name
* [STRING]    `full_name`
  - [Player info] Player full name
* [STRING]    `abbr_name`
  - [Player info] Player abbreviated name ("F.Last")
* [STRING]    `status`
  - [Player info] Player status as of 2017-18 season
* [INTEGER]   `jersey_number`
  - [Player info] Player jersey number
* [INTEGER]   `height`
  - [Player info] Player height
* [INTEGER]   `weight`
  - [Player info] Player weight
* [STRING]    `birth_place`
  - [Player info] Player birth place or home (Note: this information comes from the school's website, via Sportradar. While many of these entries indicate the player's birthplace, some of them may instead indicate the town that the players most identifies with.)
* [STRING]    `birthplace_city`
  - [Player info] Player's home city (Note: this information comes from the school's website, via Sportradar. While many of these entries indicate the player's birthplace, some of them may instead indicate the town that the players most identifies with.)
* [STRING]    `birthplace_state`
  - [Player info] Player's home state (Note: this information comes from the school's website, via Sportradar. While many of these entries indicate the player's birthplace, some of them may instead indicate the town that the players most identifies with.)
* [STRING]    `birthplace_country`
  - [Player info] Player's home country (Note: this information comes from the school's website, via Sportradar. While many of these entries indicate the player's birthplace, some of them may instead indicate the town that the players most identifies with.)
* [STRING]    `class`
  - [Player info] Player's class at game time (Note: this information comes from the school's website, via Sportradar.)
* [STRING]    `team_name`
  - [Team info] Team name
* [STRING]    `team_market`
  - [Team info] Team school name (using Sportradar names)
* [STRING]    `team_id`
  - [Team info] Sportradar team ID
* [STRING]    `team_alias`
  - [Team info] Team alias
* [STRING]    `conf_name`
  - [Team info] Team current conference name
* [STRING]    `conf_alias`
  - [Team info] Team current conference alias
* [STRING]    `division_name`
  - [Team info] Team current division name
* [STRING]    `division_alias`
  - [Team info] Team current division alias
* [STRING]    `league_name`
  - [Team info] Team current league name
* [BOOLEAN]   `home_team`
  - [Team info] Indicator of whether the team was the home team
* [BOOLEAN]   `active`
  - [Player stats] Indicator of whether the player was active for the game
* [BOOLEAN]   `played`
  - [Player stats] Indicator of whether the player played in the game
* [BOOLEAN]   `starter`
  - [Player stats] Indicator of whether the player started the game
* [STRING]    `minutes`
  - [Player stats] Minutes played
* [INTEGER]   `minutes_int64`
  - [Player stats] Minutes played (as integer)
* [STRING]    `position`
  - [Player stats] Position
* [STRING]    `primary_position`
  - [Player stats] Primary position
* [INTEGER]   `field_goals_made`
  - [Player stats] Field goals made
* [INTEGER]   `field_goals_att`
  - [Player stats] Field goals attempted
* [FLOAT]     `field_goals_pct`
  - [Player stats] Field goal percentage
* [INTEGER]   `three_points_made`
  - [Player stats] Three-pointers made
* [INTEGER]   `three_points_att`
  - [Player stats] Three-pointers attempted
* [FLOAT]     `three_points_pct`
  - [Player stats] Three-point shot percentage
* [INTEGER]   `two_points_made`
  - [Player stats] Two-pointers made
* [INTEGER]   `two_points_att`
  - [Player stats] Two-pointers attempted
* [FLOAT]     `two_points_pct`
  - [Player stats] Two-point shot percentage
* [INTEGER]   `blocked_att`
  - [Player stats] Number of shots blocked by the other team
* [INTEGER]   `free_throws_made`
  - [Player stats] Free throws made
* [INTEGER]   `free_throws_att`
  - [Player stats] Free throws attempted
* [FLOAT]     `free_throws_pct`
  - [Player stats] Free throw percentage
* [INTEGER]   `offensive_rebounds`
  - [Player stats] Offensive rebounds
* [INTEGER]   `defensive_rebounds`
  - [Player stats] Defensive rebounds
* [INTEGER]   `rebounds`
  - [Player stats] Total rebounds
* [INTEGER]   `assists`
  - [Player stats] Assists
* [INTEGER]   `turnovers`
  - [Player stats] Turnovers
* [INTEGER]   `steals`
  - [Player stats] Steals
* [INTEGER]   `blocks`
  - [Player stats] Blocks
* [FLOAT]     `assists_turnover_ratio`
  - [Player stats] Assist-to-turnover ratio
* [INTEGER]   `personal_fouls`
  - [Player stats] Personal fouls committed
* [INTEGER]   `tech_fouls`
  - [Player stats] Technical fouls committed
* [INTEGER]   `flagrant_fouls`
  - [Player stats] Flagrant fouls committed
* [INTEGER]   `points`
  - [Player stats] Points scored
* [TIMESTAMP] `sp_created`
  - [Table data] Box score data entry time

-------------------------------------------------------------------------------
*Do not make edits above this line.*
