# `ebi_chembl.metabolism_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `met_id`
  - Primary key
* [INTEGER]   `drug_record_id`
  - Foreign key to compound_records. Record representing the drug or other compound for which metabolism is being studied (may not be the same as the substrate being measured)
* [INTEGER]   `substrate_record_id`
  - Foreign key to compound_records. Record representing the compound that is the subject of metabolism
* [INTEGER]   `metabolite_record_id`
  - Foreign key to compound_records. Record representing the compound that is the result of metabolism
* [INTEGER]   `pathway_id`
  - Identifier for the metabolic scheme/pathway (may be multiple pathways from one source document)
* [STRING]    `pathway_key`
  - Link to original source indicating where the pathway information was found (e.g., Figure 1, page 23)
* [STRING]    `enzyme_name`
  -  Name of the enzyme responsible for the metabolic conversion
* [INTEGER]   `enzyme_tid`
  - Foreign key to target_dictionary. TID for the enzyme responsible for the metabolic conversion
* [STRING]    `met_conversion`
  -  Description of the metabolic conversion
* [STRING]    `organism`
  -  Organism in which this metabolic reaction occurs
* [INTEGER]   `tax_id`
  - NCBI Tax ID for the organism in which this metabolic reaction occurs
* [STRING]    `met_comment`
  - Additional information regarding the metabolism (e.g., organ system, conditions under which observed, activity of metabolites)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
