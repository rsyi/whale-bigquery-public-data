# `ebi_chembl.component_domains_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `compd_id`
  - Primary key.
* [INTEGER]   `domain_id`
  - Foreign key to the domains table, indicating the domain that is contained in the associated molecular component.
* [INTEGER]   `component_id`
  - Foreign key to the component_sequences table, indicating the molecular_component that has the given domain.
* [INTEGER]   `start_position`
  - Start position of the domain within the sequence given in the component_sequences table.
* [INTEGER]   `end_position`
  - End position of the domain within the sequence given in the component_sequences table.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
