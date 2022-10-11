# `ebi_chembl.hrac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `hrac_class_id`
  - Unique numeric primary key for each level3 code
* [STRING]    `active_ingredient`
  - Name of active ingredient (herbicide) classified by HRAC
* [STRING]    `level1`
  - HRAC group code - denoting mechanism of action of herbicide
* [STRING]    `level1_description`
  - Description of mechanism of action provided by HRAC
* [STRING]    `level2`
  - Indicates a chemical family within a particular HRAC group (number not assigned by HRAC)
* [STRING]    `level2_description`
  - Description of chemical family provided by HRAC
* [STRING]    `level3`
  - A unique code assigned to each ingredient (based on the level 1 and 2 HRAC classification, but not assigned by HRAC)
* [STRING]    `hrac_code`
  - The official HRAC classification code for the ingredient

-------------------------------------------------------------------------------
*Do not make edits above this line.*
