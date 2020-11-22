# `census_utility.lsad_codes`
`bq-1` | `bigquery-public-data`
The legal/statistical area description (LSAD) codes describe the particular typology for each geographic entity. For legal entities, the LSAD reflects the term that appears in legal documentation pertaining to the entity, such as a treaty, charter, legislation, resolution, or ordinance. For statistical entities, the LSAD is the term assigned by the Census Bureau or other agency defining the entity. The LSAD code is a two-character field that corresponds to a description of the legal or statistical type of entity and identifies whether the LSAD term should be capitalized and should precede or follow the name of the geographic entity. Note that the same LSAD code is assigned to entities at different levels of the geographic hierarchy when they share the same LSAD. For example, the Census Bureau assigns the same LSAD code ("21") to boroughs in New York and Connecticut, although they are county subdivisions in the former and incorporated places in the latter.

These codes can be found in the TIGER/Line products, gazetteer files, and other products. The table below describes each code and which geographic entities each code is valid for.

## Column details
* [STRING]    `lsad_code`
* [STRING]    `lsad_description`
* [STRING]    `associated_geographic_entities`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
