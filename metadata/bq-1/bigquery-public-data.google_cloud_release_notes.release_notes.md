# `google_cloud_release_notes.release_notes`
`bq-1` | `bigquery-public-data`
This table contains release notes for the majority of generally available Google Cloud products found on cloud.google.com. You can use this BigQuery public dataset to consume release notes programmatically across all products. HTML versions of release notes are available within each product's documentation and also in a filterable format at https://console.cloud.google.com/release-notes.

## Column details
* [STRING]    `description`
  - The content of the Release Note in Hoedown markdown format.
* [STRING]    `release_note_type`
  - The type of the release note. Possible values are: FIX, ISSUE, FEATURE, DEPRECATION, BREAKING_CHANGE,  SECURITY_BULLETIN, NON_BREAKING_CHANGE, SERVICE_ANNOUNCEMENT.
* [DATE]      `published_at`
  - The date at which this release note was published.
* [INTEGER]   `product_id`
  - A unique identifier for the product associated with this release note. In case the product_name string changes, this ID will remain the same.
* [STRING]    `product_name`
  - The name of the product associated with this release note. Note that the name of a product can change over time, if you want to use this column as a filter consider using product_id that is guaranteed to remain the same.
* [STRING]    `product_version_name`
  - The name of the version of the product that is associated with this release note.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
