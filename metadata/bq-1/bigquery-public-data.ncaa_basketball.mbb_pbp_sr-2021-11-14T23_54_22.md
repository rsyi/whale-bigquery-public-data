# `ncaa_basketball.mbb_pbp_sr-2021-11-14T23_54_22`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `game_id`
  - Unique identifier for the game
* [TIMESTAMP] `load_timestamp`
  - Time at which the data was loaded into the table
* [INTEGER]   `season`
  - Season the game was played in
* [STRING]    `status`
* [TIMESTAMP] `scheduled_date`
  - Date the game was played
* [STRING]    `venue_id`
  - Unique identifier for the venue where the game was played
* [STRING]    `venue_name`
  - Name of the venue where the game was played
* [STRING]    `venue_city`
  - City where the game was played
* [STRING]    `venue_state`
  - State where the game was played
* [STRING]    `venue_address`
  - Address of the venue where the game was played
* [STRING]    `venue_zip`
  - Zip code of the venue where the game was played
* [STRING]    `venue_country`
  - Country where the game was played
* [INTEGER]   `venue_capacity`
  - Current capacity of the venue where the game was played
* [INTEGER]   `attendance`
  - Attendance of the game
* [BOOLEAN]   `neutral_site`
  - Boolean value indicating whether the game was played at a neutral site
* [BOOLEAN]   `conference_game`
  - Boolean value indicating whether the two teams were in the same conference at the time the game was played
* [STRING]    `tournament`
  - Indicator of what type of tournament (conference or NCAA) a game was played in, if any
* [STRING]    `tournament_type`
  - Indicator of which conference tournament a game was played in, if any
* [STRING]    `round`
  - Indicator of which tournament round a game was played in, if any
* [STRING]    `game_no`
  - Indicator of which tournament game number a game was, if any
* [STRING]    `away_market`
  - Visiting team school name
* [STRING]    `away_name`
  - Visiting team name
* [STRING]    `away_id`
  - Visiting team school ID from SportRadar (unique)
To enable screen reader support, press Ctrl+Alt+Z To learn about keyboard shortcuts, press Ctrl+slash
* [STRING]    `away_alias`
  - Visiting team school alias (unique)
* [STRING]    `away_conf_name`
  - Visiting team current conference name (not unique)
* [STRING]    `away_conf_alias`
  - Visiting team current conference alias (not unique)
* [STRING]    `away_division_name`
  - Visiting team division name (not unique)
* [STRING]    `away_division_alias`
  - Visiting team division alias (not unique)
* [STRING]    `away_league_name`
  - Visiting team school league name (not unique)
* [STRING]    `home_market`
  - Home team school name
* [STRING]    `home_name`
  - Home team name
* [STRING]    `home_id`
  - Home team school ID from SportRadar (unique)
* [STRING]    `home_alias`
  - Home team school alias (unique)
* [STRING]    `home_conf_name`
  - Home team current conference name (not unique)
* [STRING]    `home_conf_alias`
  - Home team current conference alias (not unique)
* [STRING]    `home_division_name`
  - Home team current division name (not unique)
* [STRING]    `home_division_alias`
  - Home team current division alias (not unique)
* [STRING]    `home_league_name`
  - Home team school league name (not unique)
* [INTEGER]   `period`
  - This field indicates which period the event occured in. "1" is the first 20-minute half, "2" is the second 20-minute half, "3" is the first OT, "4" is the second OT, etc.
* [STRING]    `game_clock`
  - Time left in the period in minutes
* [INTEGER]   `elapsed_time_sec`
  - Total time elapsed in the game in seconds
* [STRING]    `possession_arrow`
  - The unique identifier of the team that will receive the ball the next time a jump ball is called, see https://en.wikipedia.org/wiki/Jump_ball for more information
* [STRING]    `team_name`
  - Indicator of the school name to which the event was attributed
* [STRING]    `team_market`
  - Indicator of the team name to which the event was attributed
* [STRING]    `team_id`
  - Indicator of the team school ID from SportRadar (unique) to which the event was attributed
* [STRING]    `team_alias`
  - Indicator of the team school alias (unique) to which the event was attributed
* [STRING]    `team_conf_name`
  - Indicator of the team current conference name (not unique) to which the event was attributed
* [STRING]    `team_conf_alias`
  - Indicator of the team current conference alias (not unique) to which the event was attributed
* [STRING]    `team_division_name`
  - Indicator of the team current division name (not unique) to which the event was attributed
* [STRING]    `team_division_alias`
  - Indicator of the team current division alias (not unique) to which the event was attributed
* [STRING]    `team_league_name`
  - Indicator of the team school league name (not unique) to which the event was attributed
* [STRING]    `team_basket`
  - The basket (left or right) that the team to which the event is attributed is attacking
* [STRING]    `possession_team_id`
  - The id of the team that possessed the ball at the end of the play.
* [STRING]    `player_id`
  - Unique identifier for the player to whom the event is attributed
* [STRING]    `player_full_name`
  - Name for the player to whom the event is attributed
* [INTEGER]   `jersey_num`
  - Jersey number for the player to whom the event is attributed
* [STRING]    `event_id`
  - Unique identifier for the event ("play")
* [TIMESTAMP] `timestamp`
  - The time when the event details were last updated
* [STRING]    `event_description`
  - A description of the event
* [FLOAT]     `event_coord_x`
  - The location of the play in number of inches from the "left" baseline, max 1128
* [FLOAT]     `event_coord_y`
  - The location of the play in inches from the "top" sideline, max 600
* [STRING]    `event_type`
  - Category of event
* [STRING]    `type`
  - Event subtype giving additional information about the event
* [BOOLEAN]   `shot_made`
  - Boolean value indicating whether the event was a shot made
* [STRING]    `shot_type`
  - There are 5 categories of shot types: jump shot, layup, hook shot, dunk, tip shot
* [STRING]    `shot_subtype`
  - Additional information about shot type (e.g. fadeaway, floating, pullup, step back, turnaround, alley-oop, driving, finger roll, putback, reverse)
* [BOOLEAN]   `three_point_shot`
  - Boolean value indicating whether the event was a three-point shot attempt
* [FLOAT]     `points_scored`
  - Number of points scored on the play
* [STRING]    `turnover_type`
  - Type of turnover
* [STRING]    `rebound_type`
  - Indicator of whether a rebound was offensive or defensive
* [FLOAT]     `timeout_duration`
  - Duration of timeout

-------------------------------------------------------------------------------
*Do not make edits above this line.*
