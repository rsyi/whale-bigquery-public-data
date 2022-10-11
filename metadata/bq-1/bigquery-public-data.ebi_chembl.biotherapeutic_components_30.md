# `ebi_chembl.biotherapeutic_components_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `biocomp_id`
  - Primary key.
* [INTEGER]   `molregno`
  - Foreign key to the biotherapeutics table, indicating which biotherapeutic the component is part of.
* [INTEGER]   `component_id`
  - Foreign key to the bio_component_sequences table, indicating which component is part of the biotherapeutic.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
