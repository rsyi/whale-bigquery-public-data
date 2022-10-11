# `ebi_chembl.chembl_id_lookup_30`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `chembl_id`
  - ChEMBL identifier
* [STRING]    `entity_type`
  - Type of entity (e.g., COMPOUND, ASSAY, TARGET)
* [INTEGER]   `entity_id`
  - Primary key for that entity in corresponding table (e.g., molregno for compounds, tid for targets)
* [STRING]    `status`
  - Indicates whether the status of the entity within the database - ACTIVE, INACTIVE (downgraded), OBS (obsolete/removed).
* [INTEGER]   `last_active`
  - indicates the last ChEMBL version where the CHEMBL_ID was active

-------------------------------------------------------------------------------
*Do not make edits above this line.*
