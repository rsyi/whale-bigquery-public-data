# `ebi_chembl.frac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `frac_class_id`
  - Unique numeric primary key for each level5 code
* [STRING]    `active_ingredient`
  - Name of active ingredient (fungicide) classified by FRAC
* [STRING]    `level1`
  - Mechanism of action code assigned by FRAC
* [STRING]    `level1_description`
  - Description of mechanism of action
* [STRING]    `level2`
  - Target site code assigned by FRAC
* [STRING]    `level2_description`
  - Description of target provided by FRAC
* [STRING]    `level3`
  - Group number assigned by FRAC
* [STRING]    `level3_description`
  - Description of group provided by FRAC
* [STRING]    `level4`
  - Number denoting the chemical group (number not assigned by FRAC)
* [STRING]    `level4_description`
  - Chemical group name provided by FRAC
* [STRING]    `level5`
  - A unique code assigned to each ingredient (based on the level 1-4 FRAC classification, but not assigned by IRAC)
* [STRING]    `frac_code`
  - The official FRAC classification code for the ingredient

-------------------------------------------------------------------------------
*Do not make edits above this line.*
