# `usfs_fia.population_estimation_unit`
`bq-1` | `bigquery-public-data`
Describes the estimation unit.	

Pages in FIA Documentation: 7-3

## Column details
* [INTEGER]   `estimation_unit_sequence_number`
  - Foreign key linking the stratum record to the estimation unit record."=
* [INTEGER]   `evaluation_sequence_number`
  - Foreign key linking the estimation unit record to the evaluation record.
* [INTEGER]   `region_or_station_code`
  - Identification number of the Forest Service National Forest System Region or Station (FIA work unit) that provided the inventory data (see appendix B for more information).
* [INTEGER]   `evaluation_identifier`
  - The EVALID code and the RSCD code together uniquely identify a set of field plots and associated Phase 1 summary data used to make population estimates.
* [INTEGER]   `estimation_unit`
  - The specific geographic area that is stratified. Estimation units are often determined by a combination of geographical boundaries, sampling intensity and ownership.
* [STRING]    `estimation_unit_description`
  - A description of the estimation unit (e.g., name of the county).
* [INTEGER]   `state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B. For evaluations that do not conform to the boundaries of a single State the value of STATECD should be set to 99.
* [FLOAT]     `land_area_within_the_estimation_unit`
  - The area of land in acres enclosed by the estimation unit. Census water is excluded.
* [FLOAT]     `total_area_within_the_estimation_unit`
  - This includes land and census water enclosed by the estimation unit.
* [FLOAT]     `area_used_to_calculate_all_expansion_factors`
  - This value is equivalent to AREATOT_EU when estimates are for all area, including census water; and this value is equivalent to AREALAND_EU when estimates are for land area only.
* [STRING]    `area_source`
  - Identifies the source of the area numbers. Usually, the area source is either the U.S. Census Bureau or area estimates based on pixel counts. Example values are "US CENSUS 2000" or "PIXEL COUNT."
* [INTEGER]   `phase_1_point_count_for_the_estimation_unit`
  - For remotely sensed data, this will be the total number of pixels in the estimation unit.
* [STRING]    `phase_1_source`
  - Identifies the Phase 1 data source used for this stratification. Examples are NLCD and AERIAL PHOTOS.
* [STRING]    `eval_unit_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `eval_unit_created_date`
  - See SURVEY.CREATED_DATE description for definition.
* [INTEGER]   `eval_unit_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `eval_unit_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `eval_unit_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `eval_unit_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
