# `idc_current.original_collections_metadata` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

## Column details
* [STRING]    `collection_name`
  - Collection name as used externally by IDC webapp
* [STRING]    `collection_id`
  - Collection ID as used internally by IDC webapp
* [STRING]    `Access`
  - Limited or Public
* [STRING]    `source_doi`
  - DOI that can be resolved at doi.org to a wiki page
* [STRING]    `source_url`
  - URL of collection information page
* [STRING]    `CancerTypes`
  - Cancer type of this collection 
* [STRING]    `TumorLocations`
  - Body location that was studied
* [INTEGER]   `Subjects`
  - Number of subjects in collection
* [STRING]    `Species`
  - Species of collection subjects
* [STRING]    `ImageTypes`
  - Enumeration of image type/modality
* [STRING]    `SupportingData`
  - Type(s) of addional available data
* [STRING]    `Program`
  - Program to which this collection belongs
* [STRING]    `Status`
  - Collection status: Ongoing or Complete
* [DATE]      `Updated`
  - Date of ost recent update
* [RECORD]    `licenses`
* [STRING]    `licenses.license_url`
* [STRING]    `licenses.license_long_name`
* [STRING]    `licenses.license_short_name`
* [STRING]    `Description`
  - Description of collection (HTML format)
* [STRING]    `DOI`
  - DEPRECATED: Duplicate of source_doi
* [STRING]    `URL`
  - DEPRECATED: Duplicate of source_url
* [STRING]    `CancerType`
  - DEPRECATED: Duplicate of CancerTypes 
* [STRING]    `Location`
  - DEPRECATED: Duplicate of TumorLocations

-------------------------------------------------------------------------------
*Do not make edits above this line.*
