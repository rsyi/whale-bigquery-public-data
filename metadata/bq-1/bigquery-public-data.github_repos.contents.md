# `github_repos.contents`
`bq-1` | `bigquery-public-data`
Unique file contents of text files under 1 MiB on the HEAD branch.

Can be joined to [bigquery-public-data:github_repos.files] table using the id columns to identify the repository and file path.

## Column details
* [STRING]    `id`
* [INTEGER]   `size`
* [STRING]    `content`
* [BOOLEAN]   `binary`
* [INTEGER]   `copies`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
