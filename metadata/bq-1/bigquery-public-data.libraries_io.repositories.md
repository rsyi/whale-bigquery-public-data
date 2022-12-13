# `libraries_io.repositories`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - he unique primary key of the repository in the Libraries.io database.
* [STRING]    `host_type`
  - Which website the repository is hosted on either GitHub GitLab or Bitbucket.
* [STRING]    `name_with_owner`
  - The repository name and owner seperated by a slash also maps to the url slug on the given repository host e.g. librariesio/libraries.io.
* [STRING]    `description`
  - Description of repository.
* [BOOLEAN]   `fork`
  - Is the repository a fork of another.
* [TIMESTAMP] `created_timestamp`
  - Timestamp of when the repository was created on the host.
* [TIMESTAMP] `updated_timestamp`
  - Timestamp of when the repository was last saved by Libraries.io.
* [TIMESTAMP] `last_pushed_timestamp`
  - Timestamp of when the repository was last pushed to only available for GitHub repositories.
* [STRING]    `homepage_url`
  - URL of a declared homepage or other website for the repository.
* [INTEGER]   `size`
  - Size of the repository in kilobytes only available for GitHub and Bitbucket.
* [INTEGER]   `stars_count`
  - Number of stars on the repository only available for GitHub and GitLab.
* [STRING]    `language`
  - Primary programming language the project is written in only available for GitHub and Bitbucket.
* [BOOLEAN]   `issues_enabled`
  - Is the bug tracker enabled for this repository?.
* [BOOLEAN]   `wiki_enabled`
  - Is the wiki enabled for this repository?.
* [BOOLEAN]   `pages_enabled`
  - Is GitHub pages enabled for this repository? only possible for GitHub.
* [INTEGER]   `forks_count`
  - Number of forks of this repository.
* [STRING]    `mirror_url`
  - URL of the repositroy of which this is a mirror of only present if this repository is a mirror of another.
* [INTEGER]   `open_issues_count`
  - Number of open issues on the repository bug tracker only available for GitHub and GitLab.
* [STRING]    `default_branch`
  - Primary branch of the repository.
* [INTEGER]   `watchers_count`
  - Number of subscribers to all notifications for the repository only available for GitHub and Bitbucket.
* [STRING]    `uuid`
  - ID of the repository on the remote host not unique between GitLab and GitHub repositories.
* [STRING]    `fork_source_name_with_owner`
  - If the repository is a fork the repository name and owner seperated by a slash of the repository if was forked from.
* [STRING]    `license`
  - SPDX identifier of the license of the repository only available for GitHub repositories.
* [INTEGER]   `contributors_count`
  - Number of unique contributors that have committed to the default branch.
* [STRING]    `readme_filename`
  - If a readme file has been detected the full name of the readme file e.g README.md.
* [STRING]    `changelog_filename`
  - If a changelog file has been detected the full name of the changelog file e.g changelog.txt.
* [STRING]    `contributing_guidelines_filename`
  - If a contributing guidelines file has been detected the full name of the contributing guidelines file e.g contributing.md.
* [STRING]    `license_filename`
  - If a license file has been detected the full name of the license file e.g LICENSE.
* [STRING]    `code_of_conduct_filename`
  - If a code of conduct file has been detected the full name of the code of conduct file e.g code_of_conduct.md.
* [STRING]    `security_threat_model_filename`
  - If a Security Threat Model file has been detected the full name of the Security Threat Model file e.g threatmodel.md.
* [STRING]    `security_audit_filename`
  - If a Security Audit file has been detected the full name of the Security Audit file e.g security.md.
* [STRING]    `status`
  - Either Active Deprecated Unmaintained Help Wanted Removed no value also means active. Updated when detected by Libraries.io or su. manually by Libraries.io user via "repo suggection" feature.
* [TIMESTAMP] `last_synced_timestamp`
  - Timestamp of when Libraries.io last synced the repository from the host API.
* [INTEGER]   `sourcerank`
  - Libraries.io defined score based on quality popularity and community metrics.
* [STRING]    `display_name`
  - Display name for the repository only available for GitLab repositories.
* [STRING]    `scm_type`
  - Type of source control repository uses always "git" for GitHub and GitLab.
* [STRING]    `pull_requests_enabled`
  - Are pull requests enabled for this repository? Only available for GitLab repositories.
* [STRING]    `logo_url`
  - Custom logo url for repository only available for GitLab repositories.
* [STRING]    `keywords`
  - Comma separated array of keywords called "topics" on GitHub only available for GitHub and GitLab.
* [STRING]    `an`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
