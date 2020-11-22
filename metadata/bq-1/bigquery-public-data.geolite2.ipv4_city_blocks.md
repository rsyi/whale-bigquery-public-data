# `geolite2.ipv4_city_blocks`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `network`
  - This is the IPv4 in CIDR format such as “2.21.92.0/29” or “2001:4b0::/80”. We offer a utility to convert this column to start/end IPs or start/end integers. See the conversion utility section of Maxmind's site for details: https://dev.maxmind.com/geoip/geoip2/geoip2-city-country-csv-databases/#Conversion_Utility
* [STRING]    `geoname_id`
  - A unique identifier for the network’s location as specified by GeoNames. This ID can be used to look up the location information in the ipv4_city_locations table.
* [STRING]    `registered_country_geoname_id`
  - The registered country is the country in which the ISP has registered the network. This column contains a unique identifier for the network’s registered country as specified by GeoNames. This ID can be used to look up the location information in the ipv4_city_locations table.
* [STRING]    `represented_country_geoname_id`
  - The represented country is the country which is represented by users of the IP address. For instance, the country represented by an overseas military base. This column contains a unique identifier for the network’s registered country as specified by GeoNames. This ID can be used to look up the location information in the ipv4_city_locations table.
* [BOOLEAN]   `is_anonymous_proxy`
  - Deprecated. Please see our GeoIP2 Anonymous IP database to determine whether the IP address is used by an anonymizing service.
* [BOOLEAN]   `is_satellite_provider`
  - Deprecated. Please see our GeoIP2 Anonymous IP database.
* [STRING]    `postal_code`
  - The postal code associated with the IP address. These are available for some IP addresses in Australia, Canada, France, Germany, Italy, Spain, Switzerland, United Kingdom, and the US. We return the first 3 characters for Canadian postal codes. We return the the first 2-4 characters (outward code) for postal codes in the United Kingdom.
* [FLOAT]     `latitude`
  - The approximate latitude of the postal code, city, subdivision or country associated with the IP address.
* [FLOAT]     `longitude`
  - The approximate longitude of the postal code, city, subdivision or country associated with the IP address.
* [INTEGER]   `accuracy_radius`
  - The approximate accuracy radius, in kilometers, around the latitude and longitude for the geographical entity (country, subdivision, city or postal code) associated with the IP address. Maxmind has a 67% confidence that the location of the end-user falls within the area defined by the accuracy radius and the latitude and longitude coordinates.
* [GEOGRAPHY] `center_point`
  - Geographic representation of the longitude and latitude columns for the postal code, city, subdivision or country associated with the IP address.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
