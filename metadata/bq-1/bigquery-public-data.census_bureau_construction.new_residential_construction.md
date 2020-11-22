# `census_bureau_construction.new_residential_construction`
`bq-1` | `bigquery-public-data`
Regional construction data from the Census Bureau

## Column details
* [INTEGER]   `period_id`
  - Index used to associate a data value with the time period.
* [STRING]    `period_name`
  - The name of the time period. Values for this field can  consist of the following formats depending on the  release frequency for the time series:   Frequency       per_name Format   ---------       ---------------   monthly         MMMYYYY (e.g. Jan1992, Dec2012)
* [DATE]      `period_date`
  - A date for the period. The 15th was chosen as representative of the month so the dates can be plotted easily on a chart. The 15th was not part of the original source.
* [INTEGER]   `category_id`
  - Index used to associate a data value with the category.
* [STRING]    `category_code`
  - Abbreviated category code.
* [STRING]    `category_desc`
  - Category label.
* [INTEGER]   `category_indent`
  - The hierarchy/indent level of the label when listing the categories.
* [INTEGER]   `datatype_id`
  - Index used to associate a data value with the data type.
* [STRING]    `datatype_code`
  - Abbreviated data type code
* [STRING]    `datatype_desc`
  - The name of the item and type of estimate in the time series (e.g., sales- monthly and sales- monthly percent change)
* [STRING]    `datatype_unit`
  - The unit of measure code for this data type. Below is  a list of possible codes and their meanings:   MLN$   Millions of Dollars  BLN$   Billions of Dollars   K$     Thousands of Dollars   PCT    Percent   UNITS  Units  RATIO  Ratio   MO     Number of Months   DOL    Dollars  K      Thousands of Units CP$    Cents per dollar  %PTS   Percentage Point  CENTS  Cents
* [INTEGER]   `error_type_id`
  - Index used to associate a data value with the error type.
* [STRING]    `error_type_code`
  - Abbreviated error type code
* [STRING]    `error_type_desc`
  - The name of the item and type of estimate of sampling variability in the time series (e.g., coefficients of variation of sales and standard errors of sales)
* [STRING]    `error_type_unit`
  - The unit of measure code for this data type. Below is  a list of possible codes and their meanings:   MLN$   Millions of Dollars  BLN$   Billions of Dollars   K$     Thousands of Dollars   PCT    Percent   UNITS  Units  RATIO  Ratio   MO     Number of Months   DOL    Dollars  K      Thousands of Units CP$    Cents per dollar  %PTS   Percentage Point  CENTS  Cents
* [INTEGER]   `geo_id`
  - Index used to associate a data value with the geographical level.
* [STRING]    `geo_code`
  - Abbreviated geo level code.
* [STRING]    `geo_desc`
  - Geographic level label.
* [INTEGER]   `is_adjusted`
  - Identifies whether the value is seasonally adjusted or not. A value of 1 indicates that it is adjusted, 0 means it is not.
* [FLOAT]     `value`
  - The overall new residential construction value for this period, category, location, and type.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
