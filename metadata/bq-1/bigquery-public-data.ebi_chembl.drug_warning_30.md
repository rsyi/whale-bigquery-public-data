# `ebi_chembl.drug_warning_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `warning_id`
  - Primary key for the drug warning
* [INTEGER]   `record_id`
  - Foreign key to the compound_records table
* [INTEGER]   `molregno`
  - Foreign key to molecule_dictionary table
* [STRING]    `warning_type`
  - Description of the drug warning type (e.g., withdrawn vs black box warning)
* [STRING]    `warning_class`
  -  High-level class of the drug warning
* [STRING]    `warning_description`
  - Description of the drug warning
* [STRING]    `warning_country`
  - List of countries/regions associated with the drug warning
* [INTEGER]   `warning_year`
  - Year the drug was first shown the warning

-------------------------------------------------------------------------------
*Do not make edits above this line.*
