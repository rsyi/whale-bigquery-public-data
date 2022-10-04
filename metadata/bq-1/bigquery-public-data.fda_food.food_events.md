# `fda_food.food_events`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `report_number`
  - The report number
* [STRING]    `reactions`
  - Information on the reactions or symptoms experienced by the individual involved
* [STRING]    `outcomes`
  - Information on known outcomes or consequences of the adverse event. For more info, refer: https://open.fda.gov/food/event/reference/
* [STRING]    `products_brand_name`
  - The reported brand name of the product.
* [STRING]    `products_industry_code`
  - The FDA industry code for the product. Results in this endpoint are generally limited to products tagged with industry codes related to human food and nutritional supplements or cosmetics.  For more info, refer: https://open.fda.gov/food/event/reference/
* [STRING]    `products_role`
* [STRING]    `products_industry_name`
  - The FDA industry name associated with the product.
* [DATE]      `date_created`
  - Date the report was received by FDA.
* [DATE]      `date_started`
  - Date of the adverse event (when it was considered to have started).
* [STRING]    `consumer_gender`
  - The reported gender of the consumer. Female = Female Male = Male Not Available = Unknown
* [FLOAT]     `consumer_age`
  - The reported age of the consumer at the time of the adverse event report, expressed in the unit in the field age_unit
* [STRING]    `consumer_age_unit`
  - Encodes the unit in which the age of the consumer is expressed.  Day(s) = age is expressed in days Week(s) = age is expressed in weeks Month(s) = age is expressed in months Year(s) = age is expressed in years Decade(s) = age is expressed in decades Not Available = Unknown

-------------------------------------------------------------------------------
*Do not make edits above this line.*
