# `ncaa_basketball.mbb_historical_tournament_games`
`bq-1` | `bigquery-public-data`
Game score information from Men's Basketball games, starting with the 1984-85 tournament. Each row shows one game.

## Column details
* [INTEGER]   `season`
  - Year the game was played in. Note that this is different from the "season" values in other tables here, which use academic year.
* [INTEGER]   `round`
  - Tournament round, indicated by the number of teams playing in that round
* [INTEGER]   `days_from_epoch`
  - Days from epoch, as defined in the Kaggle competition (https://www.kaggle.com/c/mens-machine-learning-competition-2018/data)
* [DATE]      `game_date`
  - Date the game was played
* [STRING]    `day`
  - Day of the week the game was played
* [STRING]    `win_seed`
  - Seed of the winning team
* [STRING]    `win_region`
  - Region of the winning team, as defined in the Kaggle competition (https://www.kaggle.com/c/mens-machine-learning-competition-2018/data)
* [STRING]    `win_market`
  - School name (using Sportradar names) of the winning team
* [STRING]    `win_name`
  - Team name of the winning team
* [STRING]    `win_alias`
  - Team alias of the winning team
* [STRING]    `win_team_id`
  - Sportradar team ID of the winning team
* [STRING]    `win_school_ncaa`
  - School name of the winning team (see http://stats.ncaa.org/game_upload/team_codes)
* [INTEGER]   `win_code_ncaa`
  - School code of the winning team (see http://stats.ncaa.org/game_upload/team_codes)
* [INTEGER]   `win_kaggle_team_id`
  - Kaggle team ID of the winning team
* [INTEGER]   `win_pts`
  - Points scored by the winning team
* [STRING]    `lose_seed`
  - Seed of the losing team
* [STRING]    `lose_region`
  - Region of the losing team, as defined in the Kaggle competition (https://www.kaggle.com/c/mens-machine-learning-competition-2018/data)
* [STRING]    `lose_market`
  - School name (using Sportradar names) of the losing team
* [STRING]    `lose_name`
  - Team name of the losing team
* [STRING]    `lose_alias`
  - Team alias of the losing team
* [STRING]    `lose_team_id`
  - Sportradar team ID of the losing team
* [STRING]    `lose_school_ncaa`
  - School name of the losing team (see http://stats.ncaa.org/game_upload/team_codes)
* [INTEGER]   `lose_code_ncaa`
  - School code of the losing team (see http://stats.ncaa.org/game_upload/team_codes)
* [INTEGER]   `lose_kaggle_team_id`
  - Kaggle team ID of the losing team
* [INTEGER]   `lose_pts`
  - Points scored by the losing team
* [INTEGER]   `num_ot`
  - Number of overtime periods played in the game
* [INTEGER]   `academic_year`
  - The academic year the game was played in

-------------------------------------------------------------------------------
*Do not make edits above this line.*
