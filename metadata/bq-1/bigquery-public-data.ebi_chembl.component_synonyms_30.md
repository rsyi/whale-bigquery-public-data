# `ebi_chembl.component_synonyms_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `compsyn_id`
  - Primary key.
* [INTEGER]   `component_id`
  - Foreign key to the component_sequences table. The component to which this synonym applies.
* [STRING]    `component_synonym`
  -  The synonym for the component.
* [STRING]    `syn_type`
  - The type or origin of the synonym (e.g., GENE_SYMBOL).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
