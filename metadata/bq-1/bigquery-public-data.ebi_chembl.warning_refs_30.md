# `ebi_chembl.warning_refs_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `warnref_id`
  - Primary key for the warning reference
* [INTEGER]   `warning_id`
  - Foreign key to the drug_warning table
* [STRING]    `ref_type`
  - Type/source of reference
* [STRING]    `ref_id`
  - Identifier for the reference in the source
* [STRING]    `ref_url`
  - Full URL linking to the reference

-------------------------------------------------------------------------------
*Do not make edits above this line.*
