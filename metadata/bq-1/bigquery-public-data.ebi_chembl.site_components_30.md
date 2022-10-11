# `ebi_chembl.site_components_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `sitecomp_id`
  - Primary key.
* [INTEGER]   `site_id`
  - Foreign key to binding_sites table.
* [INTEGER]   `component_id`
  - Foreign key to the component_sequences table, indicating which molecular component of the target is involved in the binding site.
* [INTEGER]   `domain_id`
  - Foreign key to the domains table, indicating which domain of the given molecular component is involved in the binding site (where not known, the domain_id may be null).
* [STRING]    `site_residues`
  - List of residues from the given molecular component that make up the binding site (where not know, will be null).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
