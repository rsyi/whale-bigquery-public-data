# `ebi_chembl.cell_dictionary_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `cell_id`
  - Primary key. Unique identifier for each cell line in the target_dictionary.
* [STRING]    `cell_name`
  - Name of each cell line (as used in the target_dicitonary pref_name).
* [STRING]    `cell_description`
  -  Longer description (where available) of the cell line.
* [STRING]    `cell_source_tissue`
  - Tissue from which the cell line is derived, where known.
* [STRING]    `cell_source_organism`
  -  Name of organism from which the cell line is derived.
* [INTEGER]   `cell_source_tax_id`
  - NCBI tax ID of the organism from which the cell line is derived.
* [STRING]    `clo_id`
  - ID for the corresponding cell line in Cell Line Ontology
* [STRING]    `efo_id`
  - ID for the corresponding cell line in Experimental Factory Ontology
* [STRING]    `cellosaurus_id`
  - ID for the corresponding cell line in Cellosaurus Ontology
* [STRING]    `cl_lincs_id`
  -  Cell ID used in LINCS (Library of Integrated Network-based Cellular Signatures)
* [STRING]    `chembl_id`
  - ChEMBL identifier for the cell (used in web interface etc)
* [STRING]    `cell_ontology_id`
  - ID for the corresponding cell type in the Cell Ontology

-------------------------------------------------------------------------------
*Do not make edits above this line.*
