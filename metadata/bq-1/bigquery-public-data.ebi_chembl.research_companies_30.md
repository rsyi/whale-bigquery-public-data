# `ebi_chembl.research_companies_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `co_stem_id`
  - Primary key.
* [INTEGER]   `res_stem_id`
  - Foreign key to research_stem table.
* [STRING]    `company`
  -  Name of current company associated with this research code stem.
* [STRING]    `country`
  - Country in which the company uses this research code stem.
* [STRING]    `previous_company`
  -  Previous name of the company associated with this research code stem (e.g., if the company has undergone acquisitions/mergers).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
