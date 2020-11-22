# `usfs_fia.population`
`bq-1` | `bigquery-public-data`
Join of all the population tables, so each row has all of the information for a plot. Can be joined to the plot_tree table on plot sequence number.

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
* [INTEGER]   `estimation_unit_sequence_number`
  - Foreign key linking the stratum record to the estimation unit record."=
* [INTEGER]   `evaluation_sequence_number`
  - Foreign key linking the estimation unit record to the evaluation record.
* [STRING]    `estimation_unit_description`
  - A description of the estimation unit (e.g., name of the county).
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
* [INTEGER]   `evaluation_group_sequence_number`
  - Foreign key linking the population evaluation record to the population evaluation group record.
* [STRING]    `evaluation_description`
  - A description of the area being evaluated (often a State), the time period of the evaluation, and the type of estimates the evaluation can be used to compute (e.g., all lands, area, volume, growth, removals, mortality).
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
* [INTEGER]   `evaluation_type_sequence_number`
  - A unique sequence number used to identify a population evaluation type record.
* [STRING]    `evaluation_type`
  - Describes the type of evaluation. Evaluation type is needed to generate summary reports for an inventory. For example, a specific evaluation is associated with the evaluation for tree volume (EXPVOL). At the present time, nine types of evaluations can be produced. See also the REF_POP_EVAL_TYP_DESCR table.
* [STRING]    `eval_type_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `eval_type_created_date`
  - See SURVEY.CREATED_DATE description for definition
* [INTEGER]   `eval_type_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `eval_type_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `eval_type_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `eval_type_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.
* [STRING]    `stratum_description`
  - Strata are usually based on land use (e.g., forest or nonforest) but may also be based on other criteria such as ownership (e.g., private/public/national forest).
* [INTEGER]   `phase_1_point_count`
  - The number of basic units (pixels or points) in the stratum.
* [INTEGER]   `phase_2_point_count`
  - The number of field plots that are within the stratum.
* [FLOAT]     `expansion_factor`
  - The area, in acres, that a stratum represents divided by the number of sampled plots in that stratum: EXPNS=(POP_ESTN_UNIT.AREA_USED*P1POINTCNT/POP_ESTN_UNIT.P1PNTCNT_EU)/P 2POINTCNT. This attribute can be used to obtain estimates of population area when summed across all the plots in the population of interest. Refer to The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017) for detailed examples.
* [FLOAT]     `adjustment_factor_for_the_macroplot`
  - Adjustment factor for the macroplot. A value that adjusts the population estimates to account for partially nonsampled plots (access denied and hazardous portions). It is used with condition proportion (COND.CONDPROP_UNADJ) and area expansion (EXPNS) to provide area estimates, when COND.PROP_BASIS = ""MACR"" (indicating macroplot installed). ADJ_FACTOR_MACR is also used with EXPNS and trees per acre unadjusted (TREE.TPA_UNADJ, TREE.TPAMORT_UNADJ, TREE.TPAREMV_UNADJ, TREE.TPAGROW_UNADJ) to provide tree estimates for sampled land. If a macroplot was not installed, this attribute is left blank (null). Refer to The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017) for detailed examples.
* [FLOAT]     `adjustment_factor_for_the_subplot`
  - Adjustment factor for the subplot. A value that adjusts the population estimates to account for partially nonsampled plots (access denied and hazardous portions). It is used with condition proportion (COND.CONDPROP_UNADJ) and area expansion (EXPNS) to provide area estimates, when COND.PROP_BASIS = ""SUBP"" (indicating subplots installed). ADJ_FACTOR_SUBP is also used with EXPNS and trees per acre unadjusted (TREE.TPA_UNADJ, TREE.TPAMORT_UNADJ, TREE.TPAREMV_UNADJ, TREE.TPAGROW_UNADJ) to provide tree estimates for sampled land. Refer to The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017) for detailed examples.
* [FLOAT]     `adjustment_factor_for_the_microplot`
  - A value that adjusts population estimates to account for partially nonsampled plots (access denied and hazardous portions). It is used with POP_STRATUM.EXPNS and seedlings per acre unadjusted (SEEDLING.TPA_UNADJ) or saplings per acre unadjusted (TREE.TPA_UNADJ where TREE DIA <5.0) to provide tree estimates for sampled land. Refer to The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017) for detailed examples.
* [FLOAT]     `adjustment_factor_for_coarse_woody_debris`
  - Ratio of transect length that was sampled for coarse woody debris on all partially and fully sampled plots in stratum.
* [FLOAT]     `adjustment_factor_for_small_fine_woody_debris`
  - Ratio of transect length that was sampled for small fine woody debris on all partially and fully sampled plots in stratum.
* [FLOAT]     `adjustment_factor_for_large_fine_woody_debris`
  - Ratio of transect length that was sampled for large fine woody debris on all partially and fully sampled plots in stratum.
* [FLOAT]     `adjustment_factor_for_the_duff_and_litter_layer`
  - Ratio of points that were sampled for duff and litter to target number of points for all partially and fully sampled plots in stratum.
* [STRING]    `pop_stratum_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `pop_stratum_created_date`
  - See SURVEY.CREATED_DATE description for definition.
* [INTEGER]   `pop_stratum_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `pop_stratum_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `pop_stratum_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `pop_stratum_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.
* [FLOAT]     `pop_stratum_adjustment_factor_for_piles`
  - Ratio of target divided by sampled transect length or area for piles on all partially and fully sampled plots in stratum.
* [INTEGER]   `evaluation_group`
  - "An evaluation group identifies the evaluations that were used in producing a core set of tables. In some cases one evaluation will be used for area and volume and another evaluation for growth, removals and mortality. The value of this attribute is used to select the appropriate State and year of interest to produce a set of summary tables.
* [STRING]    `evaluation_group_description`
  - A description of the evaluation group that includes the State and range of years for the evaluation, for example, ""Minnesota: 2004;2005;2006;2007;2008"". This is useful to include in a summary report to clearly identify the source of the data.
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
