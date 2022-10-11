# `ebi_chembl.activity_properties_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `ap_id`
  - Unique ID for each record.
* [INTEGER]   `activity_id`
  - FK to ACTIVITY_ID in ACTIVITIES table.
* [STRING]    `type`
  - The parameter or property type
* [STRING]    `relation`
  - Symbol constraining the value (e.g. >, <, =)
* [FLOAT]     `value`
  - Numberical value for the parameter or property
* [STRING]    `units`
  -  Units of measurement
* [STRING]    `text_value`
  - Non-numerical value of the parameter or property
* [STRING]    `standard_type`
  -  Standardised form of the TYPE
* [STRING]    `standard_relation`
  - Standardised form of the RELATION
* [FLOAT]     `standard_value`
  - Standardised form of the VALUE
* [STRING]    `standard_units`
  -  Standardised form of the UNITS
* [STRING]    `standard_text_value`
  - Standardised form of the TEXT_VALUE
* [STRING]    `comments`
  - A Comment.
* [INTEGER]   `result_flag`
  - A flag to indicate, if set to 1, that this type is a dependent variable/result (e.g., slope) rather than an independent variable/parameter (0, the default).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
