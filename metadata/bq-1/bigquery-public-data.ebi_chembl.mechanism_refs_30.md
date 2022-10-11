# `ebi_chembl.mechanism_refs_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `mecref_id`
  - Primary key
* [INTEGER]   `mec_id`
  - Foreign key to drug_mechanism table - indicating the mechanism to which the references refer
* [STRING]    `ref_type`
  - Type/source of reference (e.g., 'PubMed','DailyMed')
* [STRING]    `ref_id`
  -  Identifier for the reference in the source (e.g., PubMed ID or DailyMed setid)
* [STRING]    `ref_url`
  -  Full URL linking to the reference

-------------------------------------------------------------------------------
*Do not make edits above this line.*
