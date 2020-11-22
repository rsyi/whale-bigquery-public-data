# `usfs_fia.population_evaluation_group`
`bq-1` | `bigquery-public-data`
Contains information about types of evaluations used, also includes information to select the appropriate state and inventory year for summary reports. 	

Pages in FIA Documentation: 7-13

## Column details
* [INTEGER]   `evaluation_group_sequence_number`
  - Foreign key linking the population evaluation record to the population evaluation group record.
* [INTEGER]   `region_or_station_code`
  - Identification number of the Forest Service National Forest System Region or Station (FIA work unit) that provided the inventory data (see appendix B for more information).
* [INTEGER]   `evaluation_group`
  - "An evaluation group identifies the evaluations that were used in producing a core set of tables. In some cases one evaluation will be used for area and volume and another evaluation for growth, removals and mortality. The value of this attribute is used to select the appropriate State and year of interest to produce a set of summary tables.
* [STRING]    `evaluation_group_description`
  - A description of the evaluation group that includes the State and range of years for the evaluation, for example, ""Minnesota: 2004;2005;2006;2007;2008"". This is useful to include in a summary report to clearly identify the source of the data.
* [INTEGER]   `state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B. For evaluations that do not conform to the boundaries of a single State the value of STATECD should be set to 99.
* [STRING]    `notes`
  - Population evaluation group notes.
* [STRING]    `pop_evaluation_group_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `pop_evaluation_group_created_date`
  - See SURVEY.CREATED_DATE description for definition.
* [INTEGER]   `pop_evaluation_group_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `pop_evaluation_group_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `pop_evaluation_group_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `pop_evaluation_group_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
