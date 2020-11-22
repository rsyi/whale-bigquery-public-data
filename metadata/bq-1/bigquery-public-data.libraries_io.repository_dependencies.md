# `libraries_io.repository_dependencies`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique primary key of the repository dependency in the Libraries.io database.
* [STRING]    `host_type`
  - Which website the dependencys repository is hosted on, either GitHub, GitLab or Bitbucket.
* [STRING]    `repository_name_with_owner`
  - The repository name and owner seperated by a slash, also maps to the url slug on the given repository host e.g. librariesio/libraries.io.
* [INTEGER]   `repository_id`
  - The unique primary key of the repository for this dependency in the Libraries.io database.
* [STRING]    `manifest_platform`
  - Which package manager the dependency listed in the manifest should use.
* [STRING]    `manifest_filepath`
  - Path to the file where the dependency is declared within the repository.
* [STRING]    `git_branch`
  - Which branch was the manifest loaded from the repository.
* [STRING]    `manifest_kind`
  - Either manifest or lockfile, manifests are written by humans, lockfiles contain full resolved dependency tree.
* [STRING]    `optional`
  - Is the dependency optional?.
* [STRING]    `dependency_project_name`
  - The name of the project that the dependency specifies.
* [STRING]    `dependency_requirements`
  - The version or range of versions that the dependency specifies, resolution of that to a particular version is package manager specific.
* [STRING]    `dependency_kind`
  - The type of dependency, often declared for the phase of usage, e.g. runtime, test, development, build.
* [INTEGER]   `dependency_project_id`
  - The unique primary key of the project for this dependency in the Libraries.io database.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
