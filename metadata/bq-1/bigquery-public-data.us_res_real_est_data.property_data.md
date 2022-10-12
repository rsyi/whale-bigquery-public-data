# `us_res_real_est_data.property_data`
`bq-1` | `bigquery-public-data`
Sample of Residential property data

## Column details
* [STRING]    `address_slug`
  - Unique identifier for full address
* [STRING]    `address`
  - Address line 1
* [STRING]    `city`
  - City
* [STRING]    `state`
  - 2 character State code
* [STRING]    `zipcode`
  - 5 digit Zipcode
* [STRING]    `msa`
  - 5 digit Metropolitan Statistical Area code
* [STRING]    `fips`
  - 5 digit County code
* [STRING]    `block_id`
  - Census designated 15 digit code
* [STRING]    `apn`
  - Assessor parcel number
* [FLOAT]     `lat`
  - Latitude
* [FLOAT]     `lon`
  - Longitude
* [STRING]    `geo_precision`
  - Precision of geocoding for address location with values: rooftop,parcel,zip9,zip8,zip7,zip6,zip5
* [STRING]    `property_type`
  - Designated as single family residential (SFD) condominium (CND) or townhouse (TH)
* [INTEGER]   `hc_value_lwr`
  - Lower bound of HouseCanary property valuation
* [INTEGER]   `hc_value_mean`
  - HouseCanary property value estimate
* [INTEGER]   `hc_value_upr`
  - Upper bound of HouseCanary property valuation
* [FLOAT]     `hc_value_fsd`
  - Forecast standard deviation of HouseCanary property value estimate
* [INTEGER]   `hc_rental_value_lwr`
  - Lower bound of HouseCanary property rental valuation
* [INTEGER]   `hc_rental_value_mean`
  - HouseCanary property rental value estimate
* [INTEGER]   `hc_rental_value_upr`
  - Upper bound of HouseCanary property rental valuation
* [FLOAT]     `hc_rental_value_fsd`
  - Forecast standard deviation of HouseCanary property rental value estimate

-------------------------------------------------------------------------------
*Do not make edits above this line.*
