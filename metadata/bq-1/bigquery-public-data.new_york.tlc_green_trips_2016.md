# `new_york.tlc_green_trips_2016`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `vendor_id`
  - A code indicating the LPEP provider that provided the record. 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.
* [TIMESTAMP] `pickup_datetime`
  - The date and time when the meter was engaged
* [TIMESTAMP] `dropoff_datetime`
  - The date and time when the meter was disengaged
* [STRING]    `store_and_fwd_flag`
  - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server. Y= store and forward trip N= not a store and forward trip
* [INTEGER]   `rate_code`
  - The final rate code in effect at the end of the trip. 1= Standard rate 2=JFK 3=Newark 4=Nassau or Westchester 5=Negotiated fare 6=Group ride
* [FLOAT]     `pickup_longitude`
  - Longitude where the meter was engaged
* [FLOAT]     `pickup_latitude`
  - Latitude where the meter was engaged.
* [FLOAT]     `dropoff_longitude`
  - Longitude where the meter was timed off.
* [FLOAT]     `dropoff_latitude`
  - Latitude where the meter was timed off.
* [INTEGER]   `passenger_count`
  - The number of passengers in the vehicle. This is a driver-entered value.
* [FLOAT]     `trip_distance`
  - The elapsed trip distance in miles reported by the taximeter.
* [FLOAT]     `fare_amount`
  - The time-and-distance fare calculated by the meter
* [FLOAT]     `extra`
  - Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges
* [FLOAT]     `mta_tax`
  - $0.50 MTA tax that is automatically triggered based on the metered rate in use
* [FLOAT]     `tip_amount`
  - Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.
* [FLOAT]     `tolls_amount`
  - Total amount of all tolls paid in trip.
* [FLOAT]     `ehail_fee`
* [FLOAT]     `total_amount`
  - The total amount charged to passengers. Does not include cash tips.
* [INTEGER]   `payment_type`
  - A numeric code signifying how the passenger paid for the trip. 1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided trip
* [FLOAT]     `distance_between_service`
* [INTEGER]   `time_between_service`
* [INTEGER]   `trip_type`
  - A code indicating whether the trip was a street-hail or a dispatch that is automatically assigned based on the metered rate in use but can be altered by the driver. 1= Street-hail 2= Dispatch
* [FLOAT]     `imp_surcharge`
  - $0.30 improvement surcharge assessed on hailed trips at the flag drop. The improvement surcharge began being levied in 2015.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
