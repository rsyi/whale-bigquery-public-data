# `ebi_chembl.protein_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `protein_class_id`
  - Primary key. Unique identifier for each protein family classification.
* [INTEGER]   `parent_id`
  - Protein_class_id for the parent of this protein family.
* [STRING]    `pref_name`
  -  Preferred/full name for this protein family.
* [STRING]    `short_name`
  - Short/abbreviated name for this protein family (not necessarily unique).
* [STRING]    `protein_class_desc`
  - Concatenated description of each classification for searching purposes etc.
* [STRING]    `definition`
  - Definition of the protein family.
* [INTEGER]   `class_level`
  - Level of the class within the hierarchy (level 1 = top level classification)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
