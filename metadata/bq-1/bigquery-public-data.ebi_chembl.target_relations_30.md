# `ebi_chembl.target_relations_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `tid`
  - Identifier for target of interest (foreign key to target_dictionary table)
* [STRING]    `relationship`
  - Relationship between two targets (e.g., SUBSET OF, SUPERSET OF, OVERLAPS WITH)
* [INTEGER]   `related_tid`
  - Identifier for the target that is related to the target of interest (foreign key to target_dicitionary table)
* [INTEGER]   `targrel_id`
  - Primary key

-------------------------------------------------------------------------------
*Do not make edits above this line.*
