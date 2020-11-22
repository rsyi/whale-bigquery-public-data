# `libraries_io.projects`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique primary key of the project in the Libraries.io database.
* [STRING]    `platform`
  - The name of the Package manager the project is available on.
* [STRING]    `name`
  - The name of the project, unique by Platform (case sensitive).
* [TIMESTAMP] `created_timestamp`
  - The timestamp of when Libraries.io first discovered the project.
* [TIMESTAMP] `updated_timestamp`
  - The timestamp of when Libraries.io last saved a change to the project.
* [STRING]    `description`
  - Description provided by the package manager, falling back to description from repository if empty.
* [STRING]    `keywords`
  - Comma separated array of keywords if supported by package manager.
* [STRING]    `homepage_url`
  - URL of webpage or repository as provided by package managers that support it.
* [STRING]    `licenses`
  - Comma separated array of SPDX identifiers for licenses declared in package manager meta data or submitted manually by Libraries.io user via "project suggection" feature.
* [STRING]    `repository_url`
  - URL of source code repository declared in package manager metadata or submitted manually by Libraries.io user via "project suggection" feature.
* [INTEGER]   `versions_count`
  - Number of published versions of the project found by Libraries.io.
* [INTEGER]   `sourcerank`
  - Libraries.io defined score based on quality, popularity and community metrics.
* [TIMESTAMP] `latest_release_publish_timestamp`
  - Time of the latest release detected by Libraries.io (ordered by semver, falling back to publish date for invalid semver).
* [STRING]    `latest_release_number`
  - Version number of the latest release detected by Libraries.io (ordered by semver, falling back to publish date for invalid semver).
* [INTEGER]   `package_manager_id`
  - Unique ID of project from package manager API, only currently used by PlatformIO.
* [INTEGER]   `dependent_projects_count`
  - Number of other projects that declare the project as a dependency in one or more of their versions.
* [STRING]    `language`
  - Primary programming language the project is written in, pulled from the repository if source is hosted on GitHub.
* [STRING]    `status`
  - Either Active, Deprecated, Unmaintained, Help Wanted, Removed, no value also means active. Updated when detected by Libraries.io or submitted manually by Libraries.io user via "project suggection" feature.
* [TIMESTAMP] `last_synced_timestamp`
  - Timestamp of when Libraries.io last synced the project from it's package manager API.
* [INTEGER]   `dependent_repositories_count`
  - The total count of open source repositories that list the project as a dependency as detected by Libraries.io.
* [INTEGER]   `repository_id`
  - The unique primary key of the repository for this project in the Libraries.io database.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
