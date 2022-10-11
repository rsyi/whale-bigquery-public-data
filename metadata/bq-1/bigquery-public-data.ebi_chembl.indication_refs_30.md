# `ebi_chembl.indication_refs_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `indref_id`
  - Primary key
* [INTEGER]   `drugind_id`
  - Foreign key to the DRUG_INDICATION table, indicating the drug-indication link that this reference applies to
* [STRING]    `ref_type`
  - Type/source of reference
* [STRING]    `ref_id`
  - Identifier for the reference in the source
* [STRING]    `ref_url`
  - Full URL linking to the reference

-------------------------------------------------------------------------------
*Do not make edits above this line.*
