# `deps_dev_v1.Projects`
`bq-1` | `bigquery-public-data`
This table stores information about projects. Each row represents a single project.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `Type`
  - The name of the project.
* [STRING]    `Name`
  - The type of the project, example values include 'GITHUB', 'BITBUCKET', 'APACHE_JIRA' and 'GITLAB'.
* [INTEGER]   `OpenIssuesCount`
  - The number of open issues.
* [INTEGER]   `StarsCount`
  - The number of stars in the upstream source.
* [INTEGER]   `ForksCount`
  - The number of known forks.
* [STRING]    `Licenses`
  - A list of licenses for the project, presented as SPDX expressions.
* [STRING]    `Description`
  - A human readable description of the project.
* [STRING]    `Homepage`
  - A link to the homepage of the project.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
