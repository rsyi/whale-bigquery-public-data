# `ebi_chembl.predicted_binding_domains_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `predbind_id`
  - Primary key.
* [INTEGER]   `activity_id`
  - Foreign key to the activities table, indicating the compound/assay(+target) combination for which this prediction is made.
* [INTEGER]   `site_id`
  - Foreign key to the binding_sites table, indicating the binding site (domain) that the compound is predicted to bind to.
* [STRING]    `prediction_method`
  - The method used to assign the binding domain (e.g., 'Single domain' where the protein has only 1 domain, 'Multi domain' where the protein has multiple domains, but only 1 is known to bind small molecules in other proteins).
* [STRING]    `confidence`
  - The level of confidence assigned to the prediction (high where the protein has only 1 domain, medium where the compound has multiple domains, but only 1 known small molecule-binding domain).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
