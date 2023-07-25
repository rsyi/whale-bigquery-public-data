# `libraries_io.versions`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique primary key of the version in the Libraries.io database.
* [STRING]    `platform`
  - The name of the Package manager the version is available on.
* [STRING]    `project_name`
  - The name of the project the version belongs to.
* [INTEGER]   `project_id`
  - The unique primary key of the project for this version in the Libraries.io database.
* [STRING]    `number`
  - The number of the release often confirms to semantic versioning.
* [TIMESTAMP] `published_timestamp`
  - The timestamp of when the version was published.
* [TIMESTAMP] `created_timestamp`
  - The timestamp of when the version was first detected by Libraries.io.
* [TIMESTAMP] `updated_timestamp`
  - The timestamp of when the version was last saved by Libraries.io.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
