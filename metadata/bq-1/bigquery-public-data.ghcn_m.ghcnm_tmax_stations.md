# `ghcn_m.ghcnm_tmax_stations`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - 11 digit identifier, digits 1-3=Country Code, digits 4-8 represent the WMO id if the station is a WMO station. It is a WMO station if digits 9-11="000".
* [FLOAT]     `latitude`
  - latitude of station in decimal degrees
* [FLOAT]     `longitude`
  - longitude of station in decimal degrees
* [STRING]    `stnelev`
  - the station elevation in meters. -999.0 = missing.
* [STRING]    `name`
  - station name
* [INTEGER]   `grelev`
  - station elevation in meters estimated from gridded digital terrain data
* [STRING]    `popcls`
  - population class (U=Urban (>50,000 persons); (S=Suburban (>=10,000 and <= 50,000 persons); (R=Rural (<10,000 persons)
* [INTEGER]   `popsiz`
  - the population of the city or town the station is location in (expressed in thousands of persons).
* [STRING]    `topo`
  - type of topography in the environment surrounding the station, (Flat-FL,Hilly-HI,Mountain Top-MT,Mountainous Valley-MV).
* [STRING]    `stveg`
  - type of vegetation in environment of station if station is Rural and when it is indicated on the Operational Navigation Chart (Desert-DE,Forested-FO,Ice-IC,Marsh-MA).
* [STRING]    `stloc`
  - indicates whether station is near lake or ocean (<= 30 km of ocean-CO, adjacent to a lake at least 25 square km-LA).
* [INTEGER]   `ocndis`
  - distance to nearest ocean/lake from station (km).
* [STRING]    `airstn`
  - airport station indicator (A=station at an airport).
* [INTEGER]   `towndis`
  - distance from airport to center of associated city or town (km).
* [STRING]    `grveg`
  - vegetation type at nearest 0.5 deg x 0.5 deg gridded data point of vegetation dataset (44 total classifications).
* [STRING]    `popcss`
  - population class as determined by Satellite night lights (C=Urban, B=Suburban, A=Rural)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
