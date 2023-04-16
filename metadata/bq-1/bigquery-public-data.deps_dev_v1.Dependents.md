# `deps_dev_v1.Dependents`
`bq-1` | `bigquery-public-data`
This table stores information about the dependency relationship between versions of packages. Each row represents a dependency of one package version importing (depending on) another. These dependencies include both direct and indirect dependencies. The table is clustered on the System, Name and Version of the imported package, allowing for efficient lookup of all versions of all packages that import a specific version of a package.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `System`
  - The dependency management system of the imported package version in the relation.
* [STRING]    `Name`
  - The name of the imported package version in the relation.
* [STRING]    `Version`
  - The version of the imported package version in the relation.
* [RECORD]    `Dependent`
  - The importing package version.
* [STRING]    `Dependent.System`
  - The system of the importing package version.
* [STRING]    `Dependent.Name`
  - The name of the importing package version.
* [STRING]    `Dependent.Version`
  - The version of the importing package version.
* [INTEGER]   `MinimumDepth`
  - The minimum depth of this dependency from the root.
* [BOOLEAN]   `DependentIsHighestReleaseWithResolution`
  - This value is true if the version of the dependent was the highest release of the respective package with a dependency resolution available at the time of snapshot.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
