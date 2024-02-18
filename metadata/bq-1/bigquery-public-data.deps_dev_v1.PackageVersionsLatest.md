# `deps_dev_v1.PackageVersionsLatest` [view]
`bq-1` | `bigquery-public-data`
This view contains the most recent snapshot in the PackageVersions table.

## Column details
* [TIMESTAMP] `SnapshotAt`
* [STRING]    `System`
* [STRING]    `Name`
* [STRING]    `Version`
* [STRING]    `Licenses`
* [RECORD]    `Links`
* [STRING]    `Links.Label`
* [STRING]    `Links.URL`
* [RECORD]    `Advisories`
* [STRING]    `Advisories.Source`
* [STRING]    `Advisories.SourceID`
* [RECORD]    `VersionInfo`
* [BOOLEAN]   `VersionInfo.IsRelease`
* [INTEGER]   `VersionInfo.Ordinal`
* [RECORD]    `Hashes`
* [STRING]    `Hashes.Type`
* [STRING]    `Hashes.Hash`
* [BOOLEAN]   `DependenciesProcessed`
* [BOOLEAN]   `DependencyError`
* [TIMESTAMP] `UpstreamPublishedAt`
* [STRING]    `Registries`
* [RECORD]    `SLSAProvenance`
* [STRING]    `SLSAProvenance.SourceRepository`
* [STRING]    `SLSAProvenance.Commit`
* [STRING]    `SLSAProvenance.URL`
* [BOOLEAN]   `SLSAProvenance.Verified`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
