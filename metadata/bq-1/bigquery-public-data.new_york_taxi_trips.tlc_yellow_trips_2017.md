# `new_york_taxi_trips.tlc_yellow_trips_2017`
`bigquery`| `bigquery-public-data`

## Column details
* [STRING]    `vendor_id`
 - A code indicating the TPEP provider that provided the record. 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc
* [DATETIME]  `pickup_datetime`
 - The date and time when the meter was engaged.
* [DATETIME]  `dropoff_datetime`
 - The date and time when the meter was disengaged.
* [INTEGER]   `passenger_count`
 - The number of passengers in the vehicle. This is a driver-entered value
* [NUMERIC]   `trip_distance`
 - The elapsed trip distance in miles reported by the taximeter.
* [NUMERIC]   `pickup_longitude`
 - Longitude where the meter was engaged.
* [NUMERIC]   `pickup_latitude`
 - Latitude where the meter was engaged.
* [STRING]    `rate_code`
 - The final rate code in effect at the end of the trip. 1= Standard rate 2=JFK 3=Newark 4=Nassau or Westchester 5=Negotiated fare 6=Group ride
* [STRING]    `store_and_fwd_flag`
 - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server. Y= store and forward trip N= not a store and forward trip
* [NUMERIC]   `dropoff_longitude`
 - Longitude where the meter was disengaged
* [NUMERIC]   `dropoff_latitude`
 - Latitude where the meter was disengaged.
* [STRING]    `payment_type`
 - A numeric code signifying how the passenger paid for the trip. 1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided trip
* [NUMERIC]   `fare_amount`
 - The time-and-distance fare calculated by the meter
* [NUMERIC]   `extra`
 - Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.
* [NUMERIC]   `mta_tax`
 - $0.50 MTA tax that is automatically triggered based on the metered rate in use
* [NUMERIC]   `tip_amount`
 - Tip amount – This field is automatically populated for credit card tips. Cash tips are not included
* [NUMERIC]   `tolls_amount`
 - Total amount of all tolls paid in trip.
* [NUMERIC]   `imp_surcharge`
 - $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.
* [NUMERIC]   `total_amount`
 - The total amount charged to passengers. Does not include cash tips
* [STRING]    `pickup_location_id`
* [STRING]    `dropoff_location_id`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
