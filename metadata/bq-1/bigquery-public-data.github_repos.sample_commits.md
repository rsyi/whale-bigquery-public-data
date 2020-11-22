# `github_repos.sample_commits`
`bq-1` | `bigquery-public-data`
Sample of [bigquery-public-data:github_repos.commits] table.

SELECT *
FROM FLATTEN([bigquery-public-data:github_repos.commits], repo_name)
WHERE repo_name IN (
    'tensorflow/tensorflow',
    'facebook/react',
    'twbs/bootstrap',
    'apple/swift',
    'Microsoft/vscode',
    'torvalds/linux')

## Column details
* [STRING]    `commit`
* [STRING]    `tree`
* [STRING]    `parent`
* [RECORD]    `author`
* [STRING]    `author.name`
* [STRING]    `author.email`
* [INTEGER]   `author.time_sec`
* [INTEGER]   `author.tz_offset`
* [TIMESTAMP] `author.date`
* [RECORD]    `committer`
* [STRING]    `committer.name`
* [STRING]    `committer.email`
* [INTEGER]   `committer.time_sec`
* [INTEGER]   `committer.tz_offset`
* [TIMESTAMP] `committer.date`
* [STRING]    `subject`
* [STRING]    `message`
* [RECORD]    `trailer`
* [STRING]    `trailer.key`
* [STRING]    `trailer.value`
* [STRING]    `trailer.email`
* [RECORD]    `difference`
* [INTEGER]   `difference.old_mode`
* [INTEGER]   `difference.new_mode`
* [STRING]    `difference.old_path`
* [STRING]    `difference.new_path`
* [STRING]    `difference.old_sha1`
* [STRING]    `difference.new_sha1`
* [STRING]    `difference.old_repo`
* [STRING]    `difference.new_repo`
* [BOOLEAN]   `difference_truncated`
* [STRING]    `repo_name`
* [STRING]    `encoding`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
