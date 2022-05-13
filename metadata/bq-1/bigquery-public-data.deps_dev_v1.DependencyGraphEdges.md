# `deps_dev_v1.DependencyGraphEdges`
`bq-1` | `bigquery-public-data`
This table stores the full dependency graph for each version of each package. Each row represents one edge in a dependency graph.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `System`
  - The dependency management system of the package-version at the root of the dependency graph.
* [STRING]    `Name`
  - The name of the package-version at the root of the dependency graph.
* [STRING]    `Version`
  - The version of the package-version at the root of the dependency graph.
* [STRING]    `Requirement`
  - A string to represent how this particular dependency was required. Its format is system specific.
* [RECORD]    `From`
  - The system, name and version of the importing package.
* [STRING]    `From.System`
* [STRING]    `From.Name`
* [STRING]    `From.Version`
* [RECORD]    `To`
  - The system, name and version of the imported package.
* [STRING]    `To.System`
* [STRING]    `To.Name`
* [STRING]    `To.Version`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
