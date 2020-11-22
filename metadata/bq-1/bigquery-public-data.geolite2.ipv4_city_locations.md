# `geolite2.ipv4_city_locations`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `geoname_id`
  - A unique identifier for the network’s location as specified by GeoNames. This ID can be used to look up the location information in the ipv4_city_locations table.
* [STRING]    `locale_code`
  - The locale that the names in this row are in. This will always correspond to the locale name of the table.
* [STRING]    `continent_code`
  - The continent code for this location. Possible codes are: AF – Africa AN – Antarctica AS – Asia EU – Europe NA – North America OC – Oceania SA – South America
* [STRING]    `continent_name`
  - The continent name for this location in the file’s locale.
* [STRING]    `country_iso_code`
  - A two-character ISO 3166-1 country code for the country associated with the location. For more information on country codes, see: http://en.wikipedia.org/wiki/ISO_3166-1
* [STRING]    `country_name`
  - The country name for this location in the table's locale.
* [STRING]    `subdivision_1_iso_code`
  - A string of up to three characters containing the region-portion of the ISO 3166-2 code for the first level region associated with the IP address. Some countries have two levels of subdivisions, in which case this is the least specific. For example, in the United Kingdom this will be a country like “England”, not a county like “Devon”. For more information on subdivision codes, see: http://en.wikipedia.org/wiki/ISO_3166-2
* [STRING]    `subdivision_1_name`
  - The subdivision name for this location in the file’s locale. As with the subdivision code, this is the least specific subdivision for the location.
* [STRING]    `subdivision_2_iso_code`
  - A string of up to three characters containing the region-portion of the ISO 3166-2 code for the second level region associated with the IP address. Some countries have two levels of subdivisions, in which case this is the most specific. For example, in the United Kingdom this will be a a county like “Devon”, not a country like “England”. For more information on subdivision codes, see: http://en.wikipedia.org/wiki/ISO_3166-2
* [STRING]    `subdivision_2_name`
  - The subdivision name for this location in the file’s locale. As with the subdivision code, this is the most specific subdivision for the location.
* [STRING]    `city_name`
  - The city name for this location in the file’s locale.
* [STRING]    `metro_code`
  - The metro code associated with the location. These are only available for networks in the US. These match the metro codes as used by Google Marketing Platform, which can be found here: https://support.google.com/richmedia/answer/2745487?hl=en
* [STRING]    `time_zone`
  - The time zone associated with location, as specified by the IANA Time Zone Database, e.g., “America/New_York”. See more on the IANA Time Zone database: http://www.iana.org/time-zones
* [STRING]    `is_in_european_union`
  - This is 1 if the country associated with the location is a member state of the European Union. It is 0 otherwise.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
