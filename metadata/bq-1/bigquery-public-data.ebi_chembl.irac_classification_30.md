# `ebi_chembl.irac_classification_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `irac_class_id`
  - Unique numeric primary key for each level4 code
* [STRING]    `active_ingredient`
  - Name of active ingredient (insecticide) classified by IRAC
* [STRING]    `level1`
  - Class of action e.g., nerve action, energy metabolism (code not assigned by IRAC)
* [STRING]    `level1_description`
  - Description of class of action, as provided by IRAC
* [STRING]    `level2`
  - IRAC main group code denoting primary site/mechanism of action
* [STRING]    `level2_description`
  - Description of site/mechanism of action provided by IRAC
* [STRING]    `level3`
  - IRAC sub-group code denoting chemical class of insecticide
* [STRING]    `level3_description`
  - Description of chemical class or exemplifying ingredient provided by IRAC
* [STRING]    `level4`
  - A unique code assigned to each ingredient (based on the level 1, 2 and 3 IRAC classification, but not assigned by IRAC)
* [STRING]    `irac_code`
  - The official IRAC classification code for the ingredient

-------------------------------------------------------------------------------
*Do not make edits above this line.*
