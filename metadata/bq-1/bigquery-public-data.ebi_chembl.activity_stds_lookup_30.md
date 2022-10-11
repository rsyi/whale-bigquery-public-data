# `ebi_chembl.activity_stds_lookup_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `std_act_id`
  - Primary key.
* [STRING]    `standard_type`
  - The standard_type that other published_types in the activities table have been converted to.
* [STRING]    `definition`
  -  A description/definition of the standard_type.
* [STRING]    `standard_units`
  - The units that are applied to this standard_type and to which other published_units are converted. Note a standard_type may have more than one allowable standard_unit and therefore multiple rows in this table.
* [FLOAT]     `normal_range_min`
  - The lowest value for this activity type that is likely to be genuine. This is only an approximation, so lower genuine values may exist, but it may be desirable to validate these before using them. For a given standard_type/units, values in the activities table below this threshold are flagged with a data_validity_comment of 'Outside typical range'.
* [FLOAT]     `normal_range_max`
  - The highest value for this activity type that is likely to be genuine. This is only an approximation, so higher genuine values may exist, but it may be desirable to validate these before using them. For a given standard_type/units, values in the activities table above this threshold are flagged with a data_validity_comment of 'Outside typical range'.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
