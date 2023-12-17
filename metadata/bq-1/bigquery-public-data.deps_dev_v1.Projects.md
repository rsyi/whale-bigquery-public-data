# `deps_dev_v1.Projects`
`bq-1` | `bigquery-public-data`
This table stores information about projects. Each row represents a single project.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `Type`
  - The type of the project, example values include 'APACHE_JIRA', 'BITBUCKET', 'GITHUB' and 'GITLAB'.
* [STRING]    `Name`
  - The name of the project.
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
* [RECORD]    `OSSFuzz`
  - Details of this project’s testing by the OSS-Fuzz service. Only set if the project is tested by OSS-Fuzz.
* [INTEGER]   `OSSFuzz.LineCount`
  - The number of lines of code in the project.
* [INTEGER]   `OSSFuzz.LineCoverCount`
  - How many lines of code are covered by fuzzing.
* [TIMESTAMP] `OSSFuzz.Date`
  - The date the fuzz test that produced the coverage information was run against this project. The time portion of this field is midnight UTC.
* [STRING]    `OSSFuzz.ConfigURL`
  - The URL containing the configuration for the project in the OSS-Fuzz repository.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
