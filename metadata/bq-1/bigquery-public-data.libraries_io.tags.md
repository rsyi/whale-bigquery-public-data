# `libraries_io.tags`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique primary key of the tag in the Libraries.io database.
* [STRING]    `host_type`
  - Which website the tags repository is hosted on, either GitHub, GitLab or Bitbucket.
* [STRING]    `repository_name_with_owner`
  - The repository name and owner seperated by a slash, also maps to the url slug on the given repository host e.g. librariesio/libraries.io.
* [INTEGER]   `repository_id`
  - The unique primary key of the repository for this tag in the Libraries.io database.
* [STRING]    `tag_name`
  - The name of the tag often is a version number but could be any freeform string.
* [STRING]    `tag_git_sha`
  - Sha of the object that the tag is pointing at in the repository.
* [TIMESTAMP] `tag_published_timestamp`
  - The timestamp of when the tag was published.
* [TIMESTAMP] `tag_created_timestamp`
  - The timestamp of when the tag was first saved by Libraries.io.
* [TIMESTAMP] `tag_updated_timestamp`
  - The timestamp of when the tag was last saved by Libraries.io.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
