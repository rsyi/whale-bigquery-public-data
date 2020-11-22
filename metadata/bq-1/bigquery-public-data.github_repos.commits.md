# `github_repos.commits`
`bq-1` | `bigquery-public-data`
Unique Git commits from open source repositories on GitHub, pre-grouped by repositories they appear in.

## Column details
* [STRING]    `commit`
* [STRING]    `tree`
* [STRING]    `parent`
* [RECORD]    `author`
* [STRING]    `author.name`
* [STRING]    `author.email`
* [INTEGER]   `author.time_sec`
* [INTEGER]   `author.tz_offset`
* [RECORD]    `author.date`
* [INTEGER]   `author.date.seconds`
* [INTEGER]   `author.date.nanos`
* [RECORD]    `committer`
* [STRING]    `committer.name`
* [STRING]    `committer.email`
* [INTEGER]   `committer.time_sec`
* [INTEGER]   `committer.tz_offset`
* [RECORD]    `committer.date`
* [INTEGER]   `committer.date.seconds`
* [INTEGER]   `committer.date.nanos`
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
