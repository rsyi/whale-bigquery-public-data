# `ebi_chembl.drug_indication_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `drugind_id`
  - Primary key
* [INTEGER]   `record_id`
  - Foreign key to compound_records table. Links to the drug record to which this indication applies
* [INTEGER]   `molregno`
  - Molregno corresponding to the record_id in the compound_records table
* [INTEGER]   `max_phase_for_ind`
  - The maximum phase of development that the drug is known to have reached for this particular indication
* [STRING]    `mesh_id`
  - Medical Subject Headings (MeSH) disease identifier corresponding to the indication
* [STRING]    `mesh_heading`
  - Medical Subject Heading term for the MeSH disease ID
* [STRING]    `efo_id`
  - Experimental Factor Ontology (EFO) disease identifier corresponding to the indication
* [STRING]    `efo_term`
  -  Experimental Factor Ontology term for the EFO ID

-------------------------------------------------------------------------------
*Do not make edits above this line.*
