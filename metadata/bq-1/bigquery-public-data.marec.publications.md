# `marec.publications`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `publication_number`
  - DOCDB-format publication number, such as 'WO-1978000002-A2'.
* [STRING]    `publication_number_original`
  - Publication number (differs for WO and US from DOCDB).
* [STRING]    `xml`
  - The publication XML content, including the metadata, title, abstract, claims and description. This is truncated at 9MB.
* [BOOLEAN]   `truncated`
  - True if the XML has been truncated at 9MB.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
