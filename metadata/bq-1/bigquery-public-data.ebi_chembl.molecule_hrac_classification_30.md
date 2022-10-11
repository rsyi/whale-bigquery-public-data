# `ebi_chembl.molecule_hrac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `mol_hrac_id`
  - Primary key
* [INTEGER]   `hrac_class_id`
  - Foreign key to hrac_classification table showing the classification for the compound.
* [INTEGER]   `molregno`
  - Foreign key to molecule_dictionary, showing the compound to which this classification applies.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
