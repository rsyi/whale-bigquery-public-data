# `ebi_chembl.target_components_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `tid`
  - Foreign key to the target_dictionary, indicating the target to which the components belong.
* [INTEGER]   `component_id`
  - Foreign key to the component_sequences table, indicating which components belong to the target.
* [INTEGER]   `targcomp_id`
  - Primary key.
* [INTEGER]   `homologue`
  - Indicates that the given component is a homologue of the correct component (e.g., from a different species) when set to 1. This may be the case if the sequence for the correct protein/nucleic acid cannot be found in sequence databases. A value of 2 indicates that the sequence given is a representative of a species group, e.g., an E. coli protein to represent the target of a broad-spectrum antibiotic.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
