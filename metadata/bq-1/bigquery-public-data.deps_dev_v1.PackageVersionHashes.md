# `deps_dev_v1.PackageVersionHashes`
`bq-1` | `bigquery-public-data`
This table can be used to find package-versions from a given hash. Each row represents a single (hash, package-version) pair.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `Hash`
  - A base64 encoded string of the hash.
* [STRING]    `HashType`
  - The type of hash, example values include 'SHA512' and 'SHA1'.
* [STRING]    `System`
  - The dependency management system of the package-version.
* [STRING]    `Name`
  - The name of the package-version.
* [STRING]    `Version`
  - The version of the package-version.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
