# `ebi_chembl.molecule_frac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `mol_frac_id`
  - Primary key.
* [INTEGER]   `frac_class_id`
  - Foreign key to frac_classification table showing the mechanism of action classification of the compound.
* [INTEGER]   `molregno`
  - Foreign key to molecule_dictionary, showing the compound to which the classification applies.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
