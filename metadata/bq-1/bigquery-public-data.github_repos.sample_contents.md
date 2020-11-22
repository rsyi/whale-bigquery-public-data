# `github_repos.sample_contents`
`bq-1` | `bigquery-public-data`
Randomly sampled 10% of text file contents from [bigquery-public-data:github_repos.contents].

This sample set can be joined to [bigquery-public-data:github_repos.sample_files] on the id column.

SELECT
    c.id id,
    FIRST(c.size) size,
    FIRST(c.content) content,
    FIRST(c.binary) binary,
    FIRST(c.copies) copies,
    FIRST(f.repo_name) sample_repo_name,
    FIRST(f.ref) sample_ref,
    FIRST(f.path) sample_path,
    FIRST(f.mode) sample_mode,
    FIRST(f.symlink_target) sample_symlink_target
FROM [bigquery-public-data:github_repos.sample_files] f
JOIN (
    SELECT * 
    FROM [bigquery-public-data:github_repos.contents] 
    WHERE RAND() < 0.1
  ) c
ON f.id = c.id
GROUP BY 1

## Column details
* [STRING]    `id`
* [INTEGER]   `size`
* [STRING]    `content`
* [BOOLEAN]   `binary`
* [INTEGER]   `copies`
* [STRING]    `sample_repo_name`
* [STRING]    `sample_ref`
* [STRING]    `sample_path`
* [INTEGER]   `sample_mode`
* [STRING]    `sample_symlink_target`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
