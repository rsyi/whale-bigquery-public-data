# `idc_v17.original_collections_metadata`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `collection_name`
  - Collection name as used externally by IDC webapp
* [STRING]    `collection_id`
  - Collection ID as used internally by IDC webapp
* [STRING]    `Program`
  - Program to which this collection belongs
* [STRING]    `Status`
  - Collection status: Ongoing or Complete
* [DATE]      `Updated`
  - Date of ost recent update
* [STRING]    `Access`
  - Limited or Public
* [STRING]    `ImageTypes`
  - Enumeration of image type/modality
* [INTEGER]   `Subjects`
  - Number of subjects in collection
* [STRING]    `DOI`
  - DOI that can be resolved at doi.org to a wiki page
* [STRING]    `URL`
  - URL of collection information page
* [STRING]    `CancerType`
  - Cancer type of this collection 
* [STRING]    `SupportingData`
  - Type(s) of addional available data
* [STRING]    `Species`
  -  Species of collection subjects
* [STRING]    `Location`
  - Body location that was studies
* [RECORD]    `licenses`
* [STRING]    `licenses.license_url`
  - URL of license of this analysis result
* [STRING]    `licenses.license_long_name`
  - Long name of license of this analysis result
* [STRING]    `licenses.license_short_name`
  - Short name of license of this analysis result
* [STRING]    `Description`
  - Description of collection (HTML format)
* [STRING]    `idc_webapp_collection_id`
  - DEPRECATED:Collection ID as used internally by IDC webapp
* [STRING]    `tcia_api_collection_id`
  - DEPRECATED: Collection ID as accepted by TCIA APIs
* [STRING]    `tcia_wiki_collection_id`
  - DEPRECATED: Collection ID as on TCIA wiki page

-------------------------------------------------------------------------------
*Do not make edits above this line.*
