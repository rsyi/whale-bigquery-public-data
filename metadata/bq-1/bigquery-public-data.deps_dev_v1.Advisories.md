# `deps_dev_v1.Advisories`
`bq-1` | `bigquery-public-data`
This table stores information about security advisories related to packages from any of npm, Go, Maven, PyPI and Cargo. Each row represents a single advisory and can be identified by Source and SourceID.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `Source`
  - The upstream source of this advisory, example values include 'GHSA', 'NSWG' and 'OSV'.
* [STRING]    `SourceID`
  - The id of this advisory within its upstream source.
* [STRING]    `SourceURL`
  - A link to this advisory in its upstream source.
* [STRING]    `Title`
  - Brief human-readable description of the advisory.
* [STRING]    `Description`
  - A description of the advisory.
* [STRING]    `ReferenceURLs`
  - URLs that elaborate on an advisory: longer descriptions, corroborating evidence, patches, issue trackers, release notes and so on.
* [NUMERIC]   `CVSS3Score`
  - A numeric measure of severity according to the CVSS3 spec. The measure ranges from 0-10 and is to 1 decimal place.
* [STRING]    `Severity`
  - A discrete scale of the severity, derived from the CVSS3Score. Example values include 'NONE', 'LOW', 'MEDIUM', 'HIGH', 'CRITICAL', 'UNKNOWN'.
* [STRING]    `GitHubSeverity`
  - The severity of this advisory as determined by GitHub. Example values include 'LOW', 'MODERATE', 'HIGH', 'CRITICAL', 'UNKNOWN'.
* [TIMESTAMP] `Disclosed`
  - The time at which this advisory was publicly disclosed.
* [RECORD]    `Packages`
  - An array of the packages affected by this advisory.
* [STRING]    `Packages.System`
  - The system of the affected package
* [STRING]    `Packages.Name`
  - The name of the affected package
* [STRING]    `Packages.AffectedVersions`
  - The versions of the package affected by the advisory
* [STRING]    `Packages.UnaffectedVersions`
  - The versions of the package unaffected by the advisory
* [STRING]    `Aliases`
  - Other identifiers used for the advisory, including CVEs.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
