# `ucb_fung_patent_data.assignee_raw`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - System generated
* [STRING]    `PatentNo`
  - Patent number
* [STRING]    `Company`
  - Assignee name (can be companies, universities, government agencies, or simply person name)
* [STRING]    `Geography`
  - Raw (city, state, country) tuple of assginee
* [STRING]    `Country`
  - Country Code derived from field 'Geography'
* [STRING]    `State`
  - State Code derived from field 'Geography' (if in U.S.)
* [STRING]    `City`
  - City Name derived from field 'Geography'
* [STRING]    `Sequence`
  - Order of appearance (0 means the first assignee, 1 means the second assignee, ..., etc)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
