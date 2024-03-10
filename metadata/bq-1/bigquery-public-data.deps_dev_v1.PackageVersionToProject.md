# `deps_dev_v1.PackageVersionToProject`
`bq-1` | `bigquery-public-data`
This table represents the relation between package-versions and project. Each row represents a single pair of package-version and project. This relation is not guaranteed to be authoritative as the owner of a package may list a link to any project and the resulting relationship is not verified.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `System`
  - The dependency management system of the package-version.
* [STRING]    `Name`
  - The name of the package-version.
* [STRING]    `Version`
  - The version of the package-version.
* [STRING]    `ProjectType`
  - The type of the project.
* [STRING]    `ProjectName`
  - The name of the project.
* [STRING]    `RelationProvenance`
  - How the mapping between project and package version was discovered.
* [STRING]    `RelationType`
  - What the relationship between the project and the package version is.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
