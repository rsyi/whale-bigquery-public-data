# `ebi_chembl.assay_parameters_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `assay_param_id`
  - Numeric primary key
* [INTEGER]   `assay_id`
  - Foreign key to assays table. The assay to which this parameter belongs
* [STRING]    `type`
  - The type of parameter being described, according to the original data source
* [STRING]    `relation`
  - The relation symbol for the parameter being described, according to the original data source
* [FLOAT]     `value`
  - The value of the parameter being described, according to the original data source. Used for numeric data
* [STRING]    `units`
  -  The units for the parameter being described, according to the original data source
* [STRING]    `text_value`
  - The text value of the parameter being described, according to the original data source. Used for non-numeric/qualitative data
* [STRING]    `standard_type`
  -  Standardized form of the TYPE
* [STRING]    `standard_relation`
  - Standardized form of the RELATION
* [FLOAT]     `standard_value`
  - Standardized form of the VALUE
* [STRING]    `standard_units`
  -  Standardized form of the UNITS
* [STRING]    `standard_text_value`
  - Standardized form of the TEXT_VALUE
* [STRING]    `comments`
  - Additional comments describing the parameter

-------------------------------------------------------------------------------
*Do not make edits above this line.*
