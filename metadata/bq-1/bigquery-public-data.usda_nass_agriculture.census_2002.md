# `usda_nass_agriculture.census_2002`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `source_desc`
  - Source of data (CENSUS or SURVEY). Census program includes the Census of Ag as well as follow up projects. Survey program includes national, state, and county surveys.
* [STRING]    `sector_desc`
  - Five high level, broad categories useful to narrow down choices (CROPS, ANIMALS & PRODUCTS, ECONOMICS, DEMOGRAPHICS, and ENVIRONMENTAL).
* [STRING]    `group_desc`
  - Subsets within sector (e.g., under sector = CROPS, the groups are FIELD CROPS, FRUIT & TREE NUTS, HORTICULTURE, and VEGETABLES).
* [STRING]    `commodity_desc`
  - The primary subject of interest (e.g., CORN, CATTLE, LABOR, TRACTORS, OPERATORS).
* [STRING]    `class_desc`
  - Generally a physical attribute (e.g., variety, size, color, gender) of the commodity.
* [STRING]    `prodn_practice_desc`
  - A method of production or action taken on the commodity (e.g., IRRIGATED, ORGANIC, ON FEED).
* [STRING]    `util_practice_desc`
  - Utilizations (e.g., GRAIN, FROZEN, SLAUGHTER) or marketing channels (e.g., FRESH MARKET, PROCESSING, RETAIL).
* [STRING]    `statisticcat_desc`
  - The aspect of a commodity being measured (e.g., AREA HARVESTED, PRICE RECEIVED, INVENTORY, SALES).
* [STRING]    `unit_desc`
  - The unit associated with the statistic category (e.g., ACRES, $ / LB, HEAD, $, OPERATIONS).
* [STRING]    `short_desc`
  - A concatenation of six columns: commodity_desc, class_desc, prodn_practice_desc, util_practice_desc, statisticcat_desc, and unit_desc.
* [STRING]    `domain_desc`
  - Generally another characteristic of operations that produce a particular commodity (e.g., ECONOMIC CLASS, AREA OPERATED, NAICS CLASSIFICATION, SALES). For chemical usage data, the domain describes the type of chemical applied to the commodity. The domain = TOTAL will have no further breakouts; i.e., the data value pertains completely to the short_desc.
* [STRING]    `domaincat_desc`
  - Categories or partitions within a domain (e.g., under domain = SALES, domain categories include $1,000 TO $9,999, $10,000 TO $19,999, etc).
* [STRING]    `agg_level_desc`
  - Aggregation level or geographic granularity of the data (e.g., STATE, AG DISTRICT, COUNTY, REGION, ZIP CODE).
* [INTEGER]   `state_ansi`
  - American National Standards Institute (ANSI) standard 2-digit state codes.
* [INTEGER]   `state_fips_code`
  - NASS 2-digit state codes; include 99 and 98 for US TOTAL and OTHER STATES, respectively; otherwise match ANSI codes.
* [STRING]    `state_alpha`
  - State abbreviation, 2-character alpha code.
* [STRING]    `state_name`
  - State full name.
* [INTEGER]   `asd_code`
  - NASS defined county groups, unique within a state, 2-digit ag statistics district code.
* [STRING]    `asd_desc`
  - Ag statistics district name.
* [INTEGER]   `county_ansi`
  - ANSI standard 3-digit county codes.
* [INTEGER]   `county_code`
  - NASS 3-digit county codes; includes 998 for OTHER (COMBINED) COUNTIES and Alaska county codes; otherwise match ANSI codes.
* [STRING]    `county_name`
  - County name.
* [STRING]    `region_desc`
  - NASS defined geographic entities not readily defined by other standard geographic levels. A region can be a less than a state (SUB-STATE) or a group of states (MULTI-STATE), and may be specific to a commodity.
* [INTEGER]   `zip_5`
  - US Postal Service 5-digit zip code.
* [INTEGER]   `watershed_code`
  - US Geological Survey (USGS) 8-digit Hydrologic Unit Code (HUC) for watersheds.
* [STRING]    `watershed_desc`
  - Name assigned to the HUC.
* [INTEGER]   `congr_district_code`
  - US Congressional District 2-digit code.
* [INTEGER]   `country_code`
  - US Census Bureau, Foreign Trade Division 4-digit country code, as of April, 2007.
* [STRING]    `country_name`
  - Country name.
* [STRING]    `location_desc`
  - Full description for the location dimension.
* [INTEGER]   `year`
  - The numeric year of the data.
* [STRING]    `freq_desc`
  - Length of time covered (ANNUAL, SEASON, MONTHLY, WEEKLY, POINT IN TIME). MONTHLY often covers more than one month. POINT IN TIME is as of a particular day.
* [INTEGER]   `begin_code`
  - If applicable, a 2-digit code corresponding to the beginning of the reference period (e.g., for freq_desc = MONTHLY, begin_code ranges from 01 (January) to 12 (December)).
* [INTEGER]   `end_code`
  - If applicable, a 2-digit code corresponding to the end of the reference period (e.g., the reference period of JAN THRU MAR will have begin_code = 01 and end_code = 03).
* [STRING]    `reference_period_desc`
  - The specific time frame, within a freq_desc.
* [DATE]      `week_ending`
  - Week ending date, used when freq_desc = WEEKLY.
* [TIMESTAMP] `load_time`
  - Date and time indicating when record was inserted into Quick Stats database.
* [FLOAT]     `value`
  - Published data value.
* [STRING]    `value_suppression_code`
  - Any suppression codes used to avoid displaying data that should not be disclosed or from putting out data lower than the precision level defined by NASS. Code definitions can be found in the NASS publications.
* [FLOAT]     `cv_percent`
  - Coefficient of variation. Available for the 2012 Census of Agriculture only. County-level CVs are generalized.
* [STRING]    `cv_suppression_code`
  - Any suppression codes used to avoid displaying data that should not be disclosed or from putting out data lower than the precision level defined by NASS. Code definitions can be found in the NASS publications.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
