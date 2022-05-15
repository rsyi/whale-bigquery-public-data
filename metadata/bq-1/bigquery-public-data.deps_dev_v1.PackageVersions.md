# `deps_dev_v1.PackageVersions`
`bq-1` | `bigquery-public-data`
This table stores information about specific versions of packages. Each row represents a single version of a package.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `System`
  - The dependency management system of the package-version.
* [STRING]    `Name`
  - The name of the package-version.
* [STRING]    `Version`
  - The version of the package-version.
* [STRING]    `Licenses`
  - An array of the licenses used by this package-version, presented as SPDX expressions.
* [RECORD]    `Links`
  - An array of links related to this package-version, each consisting of a Label and URL.
* [STRING]    `Links.Label`
  - A label for the corresponding URL value. Example values for Label include 'ISSUE_TRACKER', 'HOMEPAGE', 'DOCUMENTATION' and 'SOURCE_REPO'.
* [STRING]    `Links.URL`
* [RECORD]    `Advisories`
  - An array of Advisory source and source IDs that affect this package-version directly. This can be used to join against the Advisories table.
* [STRING]    `Advisories.Source`
* [STRING]    `Advisories.SourceID`
* [RECORD]    `VersionInfo`
  - Information extracted from the string value in the Version column of this row.
* [BOOLEAN]   `VersionInfo.IsRelease`
  - The value is true if the version is considered a release, as opposed to a pre-release. 
* [INTEGER]   `VersionInfo.Ordinal`
  - The value allows the versions of a package to be sorted in semantic order without parsing the version string. If a package has its versions sorted in ascending order by VersionInfo.Ordinal, the order will correspond to the order of the version strings as determined by the package management system.
* [RECORD]    `Hashes`
  - An array of hash type and hash that have been observed from this package-version.
* [STRING]    `Hashes.Type`
* [STRING]    `Hashes.Hash`

-------------------------------------------------------------------------------
*Do not make edits above this line.*