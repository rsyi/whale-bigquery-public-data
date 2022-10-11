# `ebi_chembl.formulations_30`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `product_id`
  - Unique identifier of the product. FK to PRODUCTS
* [STRING]    `ingredient`
  -  Name of the approved ingredient within the product
* [STRING]    `strength`
  -  Dose strength
* [INTEGER]   `record_id`
  - Foreign key to the compound_records table.
* [INTEGER]   `molregno`
  - Unique identifier of the ingredient FK to MOLECULE_DICTIONARY
* [INTEGER]   `formulation_id`
  - Primary key.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
