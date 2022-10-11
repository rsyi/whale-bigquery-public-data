# `ebi_chembl.compound_structural_alerts_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `cpd_str_alert_id`
  - Primary key.
* [INTEGER]   `molregno`
  - Foreign key to the molecule_dictionary. The compound for which the structural alert has been found.
* [INTEGER]   `alert_id`
  - Foreign key to the structural_alerts table. The particular alert that has been identified in this compound.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
