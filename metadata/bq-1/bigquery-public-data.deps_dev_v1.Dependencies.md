# `deps_dev_v1.Dependencies`
`bq-1` | `bigquery-public-data`
This table stores information about the dependency relationship between versions of packages. Each row represents a dependency of one package-version importing (depending) on another. These dependencies include both direct and indirect dependencies.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `System`
  - The dependency management system of the importing package-version in the relation.
* [STRING]    `Name`
  - The name of the importing package-version in the relation.
* [STRING]    `Version`
  - The version of the importing package-version in the relation.
* [RECORD]    `Dependency`
  - The imported package-version.
* [STRING]    `Dependency.System`
  - The system of the imported package-version.
* [STRING]    `Dependency.Name`
  - The name of the imported package-version.
* [STRING]    `Dependency.Version`
  - The version of the imported package-version.
* [INTEGER]   `MinimumDepth`
  - The minimum depth of this dependency from the root.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
