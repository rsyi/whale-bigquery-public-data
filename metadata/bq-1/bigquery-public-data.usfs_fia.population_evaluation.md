# `usfs_fia.population_evaluation`
`bq-1` | `bigquery-public-data`
Describes the evaluation area, which is often a State. 
Pages in FIA Documentation:	7-7

## Column details
* [INTEGER]   `evaluation_sequence_number`
  - Foreign key linking the estimation unit record to the evaluation record.
* [INTEGER]   `evaluation_group_sequence_number`
  - Foreign key linking the population evaluation record to the population evaluation group record.
* [INTEGER]   `region_or_station_code`
  - Identification number of the Forest Service National Forest System Region or Station (FIA work unit) that provided the inventory data (see appendix B for more information).
* [INTEGER]   `evaluation_identifier`
  - The EVALID code and the RSCD code together uniquely identify a set of field plots and associated Phase 1 summary data used to make population estimates.
* [STRING]    `evaluation_description`
  - A description of the area being evaluated (often a State), the time period of the evaluation, and the type of estimates the evaluation can be used to compute (e.g., all lands, area, volume, growth, removals, mortality).
* [INTEGER]   `state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B. For evaluations that do not conform to the boundaries of a single State the value of STATECD should be set to 99.
* [STRING]    `location_name`
  - Geographic area as it would appear in the title of a report.
* [STRING]    `report_year_name`
  - The data collection years that would appear in the title of a report.
* [STRING]    `start_inventory_year`
  - The starting year for the data included in the evaluation.
* [STRING]    `end_inventory_year`
  - The ending year for the data included in the evaluation.
* [STRING]    `land_only`
  - A code indicating area used in stratifying evaluations. See POP_ESTN_UNIT.AREA_SOURCE for more information.
* [STRING]    `timberland_only`
  - A code indicting if the estimate can be made for timberland or for timberland and forest land. Timberland is a subset of forest land defined as nonreserved forest land capable of producing at least 20 cubic feet of wood volume per acre per year (COND.COND_STATUS_CD = 1, COND.RESERVCD = 0, COND.SITECLCD <7).
* [STRING]    `growth_accounting`
  - A code indicating whether the evaluation can be used for growth accounting. This attribute is blank (null) when the POP_EVAL_TYP.EVAL_TYP is not 'EXPGROW' evaluation type. See The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017) for examples of the growth accounting method.
* [STRING]    `estimation_method`
  - Describes the method of estimation. Post-stratification is used for most inventories where PLOT.MANUAL ≥1.0.
* [STRING]    `notes`
  - Population evaluation group notes.
* [STRING]    `pop_evaluation_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `pop_evaluation_created_date`
  - See SURVEY.CREATED_DATE description for definition.
* [INTEGER]   `pop_evaluation_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `pop_evaluation_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `pop_evaluation_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `pop_evaluation_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
