# `covid19_vaccination_access.facility_boundary_us_drive`
`bq-1` | `bigquery-public-data`
This table represents the boundaries of areas surrounding vaccination facilities from which people can reach the facility by driving within predetermined time periods.

## Column details
* [STRING]    `facility_place_id`
  - The Google Place ID of the vaccination site. For example, ChIJV3woGFkSK4cRWP9s3-kIFGk.
* [STRING]    `facility_provider_id`
  - An identifier imported from the provider of the vaccination site information. In the US, we use the ID provided by VaccineFinder when available. For example, 7ede5bd5-44da-4a59-b4d9-b3a49c53472c.
* [STRING]    `facility_name`
  - The name of the vaccination site. For example, St. Joseph's Hospital.
* [FLOAT]     `facility_latitude`
  - The latitude of the vaccination site. For example, 36.0507
* [FLOAT]     `facility_longitude`
  - The longitude of the vaccination site. For example, 41.4356
* [STRING]    `facility_country_region`
  - The name of the country or region in English. For example, United States.
* [STRING]    `facility_country_region_code`
  - The ISO 3166-1 code for the country or region. For example, US.
* [STRING]    `facility_sub_region_1`
  - The name of a region in the country. For example, California.
* [STRING]    `facility_sub_region_1_code`
  - A country-specific ISO 3166-2 code for the region. For example, US-CA.
* [STRING]    `facility_sub_region_2`
  - The name (or type) of a region in the country. Typically a subdivision of sub_region_1. For example, Santa Clara County or municipal_borough.
* [STRING]    `facility_sub_region_2_code`
  - In the US, the FIPS code for a US county (or equivalent). For example, 06085.
* [STRING]    `facility_region_place_id`
  - The Google place ID for the most-specific region, used in Google Places API and on Google Maps. For example, ChIJd_Y0eVIvkIARuQyDN0F1LBA.
* [STRING]    `mode_of_transportation`
  - The mode of transport used to calculate the catchment boundary. For example, driving.
* [INTEGER]   `travel_time_threshold_minutes`
  - The maximum travel time, in minutes, used to calculate the catchment boundary. For example, 30.
* [GEOGRAPHY] `facility_catchment_boundary`
  - A GeoJSON representation of the catchment area boundary of the site, for a particular mode of transportation and travel time threshold. Consists of multiple latitude and longitude points.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
