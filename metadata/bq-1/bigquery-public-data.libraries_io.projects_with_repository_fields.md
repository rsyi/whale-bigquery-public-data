# `libraries_io.projects_with_repository_fields`
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
* [STRING]    `repository_host_type`
  - Which website the repository is hosted on, either GitHub, GitLab or Bitbucket.
* [STRING]    `repository_name_with_owner`
  - The repository name and owner seperated by a slash, also maps to the url slug on the given repository host e.g. librariesio/libraries.io.
* [STRING]    `repository_description`
  - Description of repository.
* [BOOLEAN]   `repository_fork`
  - Is the repository a fork of another.
* [TIMESTAMP] `repository_created_timestamp`
  - Timestamp of when the repository was created on the host.
* [TIMESTAMP] `repository_updated_timestamp`
  - Timestamp of when the repository was last saved by Libraries.io.
* [TIMESTAMP] `repository_last_pushed_timestamp`
  - Timestamp of when the repository was last pushed to, only available for GitHub repositories.
* [STRING]    `repository_homepage_url`
  - URL of a declared homepage or other website for the repository.
* [INTEGER]   `repository_size`
  - Size of the repository in kilobytes, only available for GitHub and Bitbucket.
* [INTEGER]   `repository_stars_count`
  - Number of stars on the repository, only available for GitHub and GitLab.
* [STRING]    `repository_language`
  - Primary programming language the project is written in, only available for GitHub and Bitbucket.
* [BOOLEAN]   `repository_issues_enabled`
  - Is the bug tracker enabled for this repository?.
* [BOOLEAN]   `repository_wiki_enabled`
  - Is the wiki enabled for this repository?.
* [BOOLEAN]   `repository_pages_enabled`
  - Is GitHub pages enabled for this repository? only possible for GitHub.
* [INTEGER]   `repository_forks_count`
  - Number of forks of this repository.
* [STRING]    `repository_mirror_url`
  - URL of the repositroy of which this is a mirror of, only present if this repository is a mirror of another.
* [INTEGER]   `repository_open_issues_count`
  - Number of open issues on the repository bug tracker, only available for GitHub and GitLab.
* [STRING]    `repository_default_branch`
  - Primary branch of the repository.
* [INTEGER]   `repository_watchers_count`
  - Number of subscribers to all notifications for the repository, only available for GitHub and Bitbucket.
* [STRING]    `repository_uuid`
  - ID of the repository on the remote host, not unique between GitLab and GitHub repositories.
* [STRING]    `repository_fork_source_name_with_owner`
  - If the repository is a fork, the repository name and owner seperated by a slash of the repository if was forked from.
* [STRING]    `repository_license`
  - SPDX identifier of the license of the repository, only available for GitHub repositories.
* [INTEGER]   `repository_contributors_count`
  - Number of unique contributors that have committed to the default branch.
* [STRING]    `repository_readme_filename`
  - If a readme file has been detected, the full name of the readme file, e.g README.md.
* [STRING]    `repository_changelog_filename`
  - If a changelog file has been detected, the full name of the changelog file, e.g changelog.txt.
* [STRING]    `repository_contributing_guidelines_filename`
  - If a contributing guidelines file has been detected, the full name of the contributing guidelines file, e.g contributing.md.
* [STRING]    `repository_license_filename`
  - If a license file has been detected, the full name of the license file, e.g LICENSE.
* [STRING]    `repository_code_of_conduct_filename`
  - If a code of conduct file has been detected, the full name of the code of conduct file, e.g code_of_conduct.md.
* [STRING]    `repository_security_threat_model_filename`
  - If a Security Threat Model file has been detected, the full name of the Security Threat Model file, e.g threatmodel.md.
* [STRING]    `repository_security_audit_filename`
  - If a Security Audit file has been detected, the full name of the Security Audit file, e.g security.md.
* [STRING]    `repository_status`
  - Either Active, Deprecated, Unmaintained, Help Wanted, Removed, no value also means active. Updated when detected by Libraries.io or su. manually by Libraries.io user via "repo suggection" feature.
* [STRING]    `repository_last_synced_timestamp`
  - Timestamp of when Libraries.io last synced the repository from the host API.
* [INTEGER]   `repository_sourcerank`
  - Libraries.io defined score based on quality, popularity and community metrics.
* [STRING]    `repository_display_name`
  - Display name for the repository, only available for GitLab repositories.
* [STRING]    `repository_scm_type`
  - Type of source control repository uses, always "git" for GitHub and GitLab.
* [STRING]    `repository_pull_requests_enabled`
  - Are pull requests enabled for this repository? Only available for GitLab repositories.
* [STRING]    `repository_logo_url`
  - Custom logo url for repository, only available for GitLab repositories.
* [STRING]    `repository_keywords`
  - Comma separated array of keywords, called "topics" on GitHub, only available for GitHub and GitLab.
* [STRING]    `bh`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
