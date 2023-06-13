# `hacker_news.comments_restore`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - Unique comment ID
* [STRING]    `by`
  - Username of commenter
* [STRING]    `author`
  - Username of author
* [INTEGER]   `time`
  - Unix time
* [TIMESTAMP] `time_ts`
  - Human readable time in UTC (format: YYYY-MM-DD hh:mm:ss)
* [STRING]    `text`
  - Comment text
* [INTEGER]   `parent`
  - Parent comment ID
* [BOOLEAN]   `deleted`
  - Is deleted?
* [BOOLEAN]   `dead`
  - Is dead?
* [INTEGER]   `ranking`
  - Comment ranking

-------------------------------------------------------------------------------
*Do not make edits above this line.*
