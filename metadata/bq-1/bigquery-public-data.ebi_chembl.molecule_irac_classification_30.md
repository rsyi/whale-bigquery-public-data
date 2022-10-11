# `ebi_chembl.molecule_irac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `mol_irac_id`
  - Primary key.
* [INTEGER]   `irac_class_id`
  - Foreign key to the irac_classification table showing the mechanism of action classification for the compound.
* [INTEGER]   `molregno`
  - Foreign key to the molecule_dictionary table, showing the compound to which the classification applies.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
