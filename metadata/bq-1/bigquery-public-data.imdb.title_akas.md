# `imdb.title_akas`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `title_id`
  - A tconst, an alphanumeric unique identifier of the title.
* [INTEGER]   `ordering`
  - A number to uniquely identify rows for a given title_id.
* [STRING]    `title`
  - The localized title.
* [STRING]    `region`
  - The region for this version of the title.
* [STRING]    `language`
  - The language of the title.
* [STRING]    `types`
  - Enumerated set of attributes for this alternative title. One or more of the following: 'alternative', 'dvd', 'festival', 'tv', 'video', 'working', 'original', 'imdbDisplay'. New values may be added in the future without warning.
* [STRING]    `attributes`
  - Additional terms to describe this alternative title, not enumerated
* [BOOLEAN]   `is_original_title`
  - False: not original title; True: original title.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
