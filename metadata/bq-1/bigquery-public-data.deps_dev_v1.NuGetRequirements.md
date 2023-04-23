# `deps_dev_v1.NuGetRequirements`
`bq-1` | `bigquery-public-data`
This table stores the requirements for NuGet package-versions.

## Column details
* [TIMESTAMP] `SnapshotAt`
  - When this row was exported.
* [STRING]    `Name`
  - The name of the package-version.
* [STRING]    `Version`
  - The version of the package-version.
* [RECORD]    `DependencyGroups`
  - The list of requirements grouped by target framework into 'dependency groups'. Dependency is defined for consistency with NuGet, it describes a single unresolved requirement.
* [STRING]    `DependencyGroups.TargetFramework`
  - The specific target framework that this dependency group is for.
* [RECORD]    `DependencyGroups.Dependencies`
  - The requirements for this dependency group. Dependencies is defined for consistency with NuGet, a dependency describes an unresolved requirement.
* [STRING]    `DependencyGroups.Dependencies.Name`
  - The name of the package.
* [STRING]    `DependencyGroups.Dependencies.Requirement`
  - The requirement on the package.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
