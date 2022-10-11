# `ebi_chembl.structural_alerts_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `alert_id`
  - Primary key. Unique identifier for the structural alert
* [INTEGER]   `alert_set_id`
  - Foreign key to structural_alert_sets table indicating which set this particular alert comes from
* [STRING]    `alert_name`
  - A name for the structural alert
* [STRING]    `smarts`
  - SMARTS defining the structural feature that is considered to be an alert

-------------------------------------------------------------------------------
*Do not make edits above this line.*
