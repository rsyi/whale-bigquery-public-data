# `github_repos.sample_repos`
`bq-1` | `bigquery-public-data`
Top 400k GitHub repositories with more than 2 stars received during Jan-May 2016.

This set is used to select entries for sample_files and sample_contents.

SELECT
    repo_name,
    COUNT(*) watch_count
FROM
  [githubarchive:month.201605],
  [githubarchive:month.201604],
  [githubarchive:month.201603],
  [githubarchive:month.201602],
  [githubarchive:month.201601]
WHERE type="WatchEvent"
GROUP BY 1
HAVING watch_count >= 2
ORDER BY watch_count DESC
LIMIT 400000

## Column details
* [STRING]    `repo_name`
* [INTEGER]   `watch_count`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
