# `ebi_chembl.go_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `go_id`
  - Primary key. Gene Ontology identifier for the GO slim term
* [STRING]    `parent_go_id`
  - Gene Ontology identifier for the parent of this GO term in the ChEMBL Drug Target GO slim
* [STRING]    `pref_name`
  -  Gene Ontology name
* [INTEGER]   `class_level`
  - Indicates the level of the term in the slim (L1 = highest)
* [STRING]    `aspect`
  -  Indicates which aspect of the Gene Ontology the term belongs to (F = molecular function, P = biological process, C = cellular component)
* [STRING]    `path`
  - Indicates the full path to this term in the GO slim

-------------------------------------------------------------------------------
*Do not make edits above this line.*
