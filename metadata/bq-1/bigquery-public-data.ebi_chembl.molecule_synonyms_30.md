# `ebi_chembl.molecule_synonyms_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `molregno`
  - Foreign key to molecule_dictionary
* [STRING]    `syn_type`
  - Type of name/synonym (e.g., TRADE_NAME, RESEARCH_CODE, USAN)
* [INTEGER]   `molsyn_id`
  - Primary key.
* [INTEGER]   `res_stem_id`
  - Foreign key to the research_stem table. Where a synonym is a research code, this links to further information about the company associated with that code.
* [STRING]    `synonyms`
  -  Synonym for the compound

-------------------------------------------------------------------------------
*Do not make edits above this line.*
