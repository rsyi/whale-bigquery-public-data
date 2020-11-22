# `github_repos.sample_files`
`bq-1` | `bigquery-public-data`
Sampled file metadata for files at HEAD, from the top 400k repositories listed in sample_repos.

This is a reduced data set from [bigquery-public-data:github_repos.files] to support query experimentation with lower IO costs.

SELECT * 
FROM [bigquery-public-data:github_repos.files]
WHERE repo_name IN (
    SELECT repo_name
    FROM [bigquery-public-data:github_repos.sample_repos]
    )

## Column details
* [STRING]    `repo_name`
* [STRING]    `ref`
* [STRING]    `path`
* [INTEGER]   `mode`
* [STRING]    `id`
* [STRING]    `symlink_target`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
