# `ebi_chembl.activity_supp_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `as_id`
  - Unique ID for each record.
* [INTEGER]   `rgid`
  - Record Grouping ID, used to group together related data points in this table
* [INTEGER]   `smid`
  - FK to SMID in ACTIVITY_SMID.
* [STRING]    `type`
  - Type of end-point measurement: e.g. IC50, LD50, %inhibition etc, as it appears in the original dataset
* [STRING]    `relation`
  - Symbol constraining the activity value (e.g. >, <, =), as it appears in the original dataset
* [FLOAT]     `value`
  - Datapoint value as it appears in the original dataset.
* [STRING]    `units`
  -  Units of measurement as they appear in the original dataset
* [STRING]    `text_value`
  - Non-numeric value for measurement as in original dataset
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

-------------------------------------------------------------------------------
*Do not make edits above this line.*
