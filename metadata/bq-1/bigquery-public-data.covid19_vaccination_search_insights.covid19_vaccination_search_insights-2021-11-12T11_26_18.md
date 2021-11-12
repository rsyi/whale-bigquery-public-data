# `covid19_vaccination_search_insights.covid19_vaccination_search_insights-2021-11-12T11_26_18`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date`
  - The first day of the week (starting on Monday) on which the searches took place. For example, in the weekly data the row labeled 2021-04-19 represents the search activity for the week of April 19 to April 25, 2021, inclusive. Calendar days start and end at midnight Pacific Standard Time.
* [STRING]    `country_region`
  - The name of the country in English. For example, United States.
* [STRING]    `country_region_code`
  - The ISO 3166-1 code for the country. For example, US.
* [STRING]    `sub_region_1`
  - The name of a region in the country. For example, California.
* [STRING]    `sub_region_1_code`
  - A country-specific ISO 3166-2 code for the region. For example, US-CA.
* [STRING]    `sub_region_2`
  - The name (or type) of a region in the country. Typically a subdivision of sub_region_1. For example, Santa Clara County or municipal_borough.
* [STRING]    `sub_region_2_code`
  - In the US, the FIPS code for a US county (or equivalent). For example, 06085.
* [STRING]    `sub_region_3`
  - The name (or type) of a region in the country. Typically a subdivision of sub_region_2. For example, Downtown or postal_code.
* [STRING]    `sub_region_3_code`
  - In the US, the ZIP code. For example 94303.
* [STRING]    `place_id`
  - The Google place ID for the most-specific subregion. Used in the Google Places API and on Google Maps. For example, ChIJd_Y0eVIvkIARuQyDN0F1LBA.
* [FLOAT]     `sni_covid19_vaccination`
  - The scaled normalized interest related to all COVID-19 vaccination for the region and date. For example, 87.02. Empty when data isn't available.
* [FLOAT]     `sni_vaccination_intent`
  - The scaled normalized interest related to vaccination intent for the region and date. For example, 22.69. Empty when data isn't available.
* [FLOAT]     `sni_safety_side_effects`
  - The scaled normalized interest related to safety and side effects of the vaccines for the region and date. For example, 17.96. Empty when data isn't available.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
