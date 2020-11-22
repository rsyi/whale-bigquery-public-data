# `libraries_io.dependencies`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique primary key of the dependency in the Libraries.io database.
* [STRING]    `platform`
  - The name of the Package manager the dependency is available on.
* [STRING]    `project_name`
  - The name of the project the dependency belongs to.
* [INTEGER]   `project_id`
  - The unique primary key of the project for this dependency in the Libraries.io database.
* [STRING]    `version_number`
  - The number of the version that the dependency belongs to.
* [INTEGER]   `version_id`
  - The unique primary key of the version for this dependency in the Libraries.io database.
* [STRING]    `dependency_name`
  - The name of the project that the dependency specifies.
* [STRING]    `dependency_platform`
  - The name of the package manager that the project that the dependency specifies is available from (only different for Atom).
* [STRING]    `dependency_kind`
  - The type of dependency, often declared for the phase of usage, e.g. runtime, test, development, build.
* [STRING]    `optional_dependency`
  - Is the dependency optional?.
* [STRING]    `dependency_requirements`
  - The version or range of versions that the dependency specifies, resolution of that to a particular version is package manager specific.
* [INTEGER]   `dependency_project_id`
  - The unique primary key of the project for this dependency in the Libraries.io database.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
