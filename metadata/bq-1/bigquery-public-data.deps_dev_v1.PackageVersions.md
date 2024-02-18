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
  - A label for the corresponding URL value. Example values include 'DOCUMENTATION', 'ISSUE_TRACKER', 'HOMEPAGE' and 'SOURCE_REPO'.
* [STRING]    `Links.URL`
  - The URL value.
* [RECORD]    `Advisories`
  - An array of Advisories that affect this package-version directly. This can be used to join against the Advisories table.
* [STRING]    `Advisories.Source`
  - The upstream source of this advisory, example values include 'OSV', 'GHSA' and 'NSWG'.
* [STRING]    `Advisories.SourceID`
  - The id of this advisory within its upstream source.
* [RECORD]    `VersionInfo`
  - Information extracted from the string value in the Version column of this row.
* [BOOLEAN]   `VersionInfo.IsRelease`
  - The value is true if the version is considered a release, as opposed to a pre-release. 
* [INTEGER]   `VersionInfo.Ordinal`
  - The value allows the versions of a package to be sorted in semantic order without parsing the version string. If a package has its versions sorted in ascending order by VersionInfo.Ordinal, the order will correspond to the order of the version strings as determined by the package management system.
* [RECORD]    `Hashes`
  - An array of hashes that have been observed from this package-version.
* [STRING]    `Hashes.Type`
  - The type of hash, example values include 'SHA512' and 'SHA1'.
* [STRING]    `Hashes.Hash`
  - A base64 encoded string of the hash.
* [BOOLEAN]   `DependenciesProcessed`
  - True if this version's dependency requirements have been processed.
* [BOOLEAN]   `DependencyError`
  - True if an error was encountered while processing this version's dependency requirements.
* [TIMESTAMP] `UpstreamPublishedAt`
  - The time at which this package-version was published, as reported by the upstream source.
* [STRING]    `Registries`
  - An array of the package management registries this package-version is available from.
* [RECORD]    `SLSAProvenance`
  - Provenance information for this package version. Extracted from a SLSA provenance attestation.
* [STRING]    `SLSAProvenance.SourceRepository`
  - The source code repository used to build this version.
* [STRING]    `SLSAProvenance.Commit`
  - The commit of the source code repository the version was built from.
* [STRING]    `SLSAProvenance.URL`
  - The URL of the provenance statement.
* [BOOLEAN]   `SLSAProvenance.Verified`
  - The Sigstore bundle containing this attestation was verified using the [sigstore-go](https://github.com/sigstore/sigstore-go) library.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
