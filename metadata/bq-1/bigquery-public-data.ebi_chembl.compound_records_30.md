# `ebi_chembl.compound_records_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `record_id`
  - Unique ID for a compound/record
* [INTEGER]   `molregno`
  - Foreign key to compounds table (compound structure)
* [INTEGER]   `doc_id`
  - Foreign key to documents table
* [STRING]    `compound_key`
  -  Key text identifying this compound in the scientific document
* [STRING]    `compound_name`
  - Name of this compound recorded in the scientific document
* [INTEGER]   `src_id`
  - Foreign key to source table
* [STRING]    `src_compound_id`
  -  Identifier for the compound in the source database (e.g., pubchem SID)
* [STRING]    `cidx`
  - The Depositor Defined Compound Identifier.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
