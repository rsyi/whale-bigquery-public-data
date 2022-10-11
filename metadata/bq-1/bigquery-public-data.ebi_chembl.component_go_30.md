# `ebi_chembl.component_go_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `comp_go_id`
  - Primary key
* [INTEGER]   `component_id`
  - Foreign key to COMPONENT_SEQUENCES table. The protein component this GO term applies to
* [STRING]    `go_id`
  - Foreign key to the GO_CLASSIFICATION table. The GO term that this protein is mapped to

-------------------------------------------------------------------------------
*Do not make edits above this line.*
