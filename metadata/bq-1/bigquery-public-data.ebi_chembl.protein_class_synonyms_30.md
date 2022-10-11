# `ebi_chembl.protein_class_synonyms_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `protclasssyn_id`
  - Primary key.
* [INTEGER]   `protein_class_id`
  - Foreign key to the PROTEIN_CLASSIFICATION table. The protein_class to which this synonym applies.
* [STRING]    `protein_class_synonym`
  - The synonym for the protein class.
* [STRING]    `syn_type`
  - The type or origin of the synonym (e.g., ChEMBL, Concept Wiki, UMLS).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
