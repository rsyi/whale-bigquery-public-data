# `iowa_liquor_sales.sales-2021-11-13T14_50_01`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `invoice_and_item_number`
  - Concatenated invoice and line number associated with the liquor order. This provides a unique identifier for the individual liquor products included in the store order.
* [DATE]      `date`
  - Date of order
* [STRING]    `store_number`
  - Unique number assigned to the store who ordered the liquor.
* [STRING]    `store_name`
  - Name of store who ordered the liquor.
* [STRING]    `address`
  - Address of store who ordered the liquor.
* [STRING]    `city`
  - City where the store who ordered the liquor is located
* [STRING]    `zip_code`
  - Zip code where the store who ordered the liquor is located
* [STRING]    `store_location`
  - Location of store who ordered the liquor. The Address, City, State and Zip Code are geocoded to provide geographic coordinates. Accuracy of geocoding is dependent on how well the address is interpreted and the completeness of the reference data used.
* [STRING]    `county_number`
  - Iowa county number for the county where store who ordered the liquor is located
* [STRING]    `county`
  - County where the store who ordered the liquor is located
* [STRING]    `category`
  - Category code associated with the liquor ordered
* [STRING]    `category_name`
  - Category of the liquor ordered.
* [STRING]    `vendor_number`
  - The vendor number of the company for the brand of liquor ordered
* [STRING]    `vendor_name`
  - The vendor name of the company for the brand of liquor ordered
* [STRING]    `item_number`
  - Item number for the individual liquor product ordered.
* [STRING]    `item_description`
  - Description of the individual liquor product ordered.
* [INTEGER]   `pack`
  - The number of bottles in a case for the liquor ordered
* [INTEGER]   `bottle_volume_ml`
  - Volume of each liquor bottle ordered in milliliters.
* [FLOAT]     `state_bottle_cost`
  - The amount that Alcoholic Beverages Division paid for each bottle of liquor ordered
* [FLOAT]     `state_bottle_retail`
  - The amount the store paid for each bottle of liquor ordered
* [INTEGER]   `bottles_sold`
  - The number of bottles of liquor ordered by the store
* [FLOAT]     `sale_dollars`
  - Total cost of liquor order (number of bottles multiplied by the state bottle retail)
* [FLOAT]     `volume_sold_liters`
  - Total volume of liquor ordered in liters. (i.e. (Bottle Volume (ml) x Bottles Sold)/1,000)"
* [FLOAT]     `volume_sold_gallons`
  - Total volume of liquor ordered in gallons. (i.e. (Bottle Volume (ml) x Bottles Sold)/3785.411784)"

-------------------------------------------------------------------------------
*Do not make edits above this line.*
