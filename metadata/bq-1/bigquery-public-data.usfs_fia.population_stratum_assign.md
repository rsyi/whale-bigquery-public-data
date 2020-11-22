# `usfs_fia.population_stratum_assign`
`bq-1` | `bigquery-public-data`
Links plot to stratum information and basic information about the stratum. 	

Pages in FIA Documentation: 7-17

## Column details
* [STRING]    `stratum_assign_sequence_number`
  - A unique sequence number used to identify a population plot stratum assignment record.
* [INTEGER]   `stratum_sequence_number`
  - Foreign key linking the condition down woody material calculation record to the population stratum record.
* [INTEGER]   `plot_sequence_number`
  - Foreign key linking the condition down woody material calculation record to the plot record.
* [INTEGER]   `state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B. For evaluations that do not conform to the boundaries of a single State the value of STATECD should be set to 99.
* [INTEGER]   `inventory_year`
  - See SURVEY.INVYR description for definition.
* [INTEGER]   `survey_unit_code`
  - Forest Inventory and Analysis survey unit identification number. Survey units are usually groups of counties within each State. For periodic inventories, Survey units may be made up of lands of particular owners. Refer to appendix B for codes.
* [INTEGER]   `county_code`
  - The identification number for a county, parish, watershed, borough, or similar governmental unit in a State. FIPS codes from the Bureau of the Census are used. Refer to appendix B for codes.
* [INTEGER]   `phase_2_plot_number`
  - An identifier for a plot. Along with STATECD, INVYR, UNITCD, COUNTYCD and/or some other combinations of variables, PLOT may be used to uniquely identify a plot.
* [INTEGER]   `region_or_station_code`
  - Identification number of the Forest Service National Forest System Region or Station (FIA work unit) that provided the inventory data (see appendix B for more information).
* [INTEGER]   `evaluation_identifier`
  - The EVALID code and the RSCD code together uniquely identify a set of field plots and associated Phase 1 summary data used to make population estimates.
* [INTEGER]   `estimation_unit`
  - The specific geographic area that is stratified. Estimation units are often determined by a combination of geographical boundaries, sampling intensity and ownership.
* [INTEGER]   `stratum_code`
  - The code used for a particular stratum, which is unique within an RSCD, EVALID, ESTN_UNIT.
* [STRING]    `stratum_assign_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `stratum_assign_created_date`
  - See SURVEY.CREATED_DATE description for definition.
* [INTEGER]   `stratum_assign_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `stratum_assign_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `stratum_assign_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `stratum_assign_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
