# `ucb_fung_patent_data.inventor_raw`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `PatentNo`
  - Patent number
* [STRING]    `Sequence`
  - Order of appearance (0 means the first inventor, 1 means the second inventor, ..., etc)
* [STRING]    `FullName`
  - Full name (in form of Last Name {semicolon} First Name {single space} Middle Name)
* [STRING]    `LastName`
  - Last Name
* [STRING]    `FirstMiddleName`
  - First Name {single space} Middle Name
* [STRING]    `Geography`
  - Raw (city, state, country) tuple of assginee
* [STRING]    `Country`
  - Country Code derived from field 'Geography'
* [STRING]    `State`
  - State Code derived from field 'Geography' (if in U.S.)
* [STRING]    `City`
  - City Code derived from field 'Geography'

-------------------------------------------------------------------------------
*Do not make edits above this line.*
