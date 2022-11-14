# `hacker_news.full`
`bq-1` | `bigquery-public-data`
A full daily update of all the stories and comments in Hacker News.

## Column details
* [STRING]    `title`
  - Story title
* [STRING]    `url`
  - Story url
* [STRING]    `text`
  - Story or comment text
* [BOOLEAN]   `dead`
  - Is dead?
* [STRING]    `by`
  - The username of the item's author.
* [INTEGER]   `score`
  - Story score
* [INTEGER]   `time`
  - Unix time
* [TIMESTAMP] `timestamp`
  - Timestamp for the unix time
* [STRING]    `type`
  - type of details (comment comment_ranking poll story job pollopt)
* [INTEGER]   `id`
  - The item's unique id.
* [INTEGER]   `parent`
  - Parent comment ID
* [INTEGER]   `descendants`
  - Number of story or poll descendants
* [INTEGER]   `ranking`
  - Comment ranking
* [BOOLEAN]   `deleted`
  - Is deleted?

-------------------------------------------------------------------------------
*Do not make edits above this line.*
