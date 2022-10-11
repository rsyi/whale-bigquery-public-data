# `ebi_chembl.target_dictionary_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `tid`
  - Unique ID for the target
* [STRING]    `target_type`
  - Describes whether target is a protein, an organism, a tissue etc. Foreign key to TARGET_TYPE table.
* [STRING]    `pref_name`
  - Preferred target name: manually curated
* [INTEGER]   `tax_id`
  - NCBI taxonomy id of target
* [STRING]    `organism`
  -  Source organism of molecuar target or tissue, or the target organism if compound activity is reported in an organism rather than a protein or tissue
* [STRING]    `chembl_id`
  - ChEMBL identifier for this target (for use on web interface etc)
* [INTEGER]   `species_group_flag`
  - Flag to indicate whether the target represents a group of species, rather than an individual species (e.g., 'Bacterial DHFR'). Where set to 1, indicates that any associated target components will be a representative, rather than a comprehensive set.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
