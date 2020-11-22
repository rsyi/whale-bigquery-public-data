# `usfs_fia.population_stratum`
`bq-1` | `bigquery-public-data`
Describes the stratum used in the estimation unit.	

Pages in FIA Documentation: 7-21

## Column details
* [INTEGER]   `stratum_sequence_number`
  - Foreign key linking the condition down woody material calculation record to the population stratum record.
* [INTEGER]   `estimation_unit_sequence_number`
  - Foreign key linking the stratum record to the estimation unit record."=
* [INTEGER]   `region_or_station_code`
  - Identification number of the Forest Service National Forest System Region or Station (FIA work unit) that provided the inventory data (see appendix B for more information).
* [INTEGER]   `evaluation_identifier`
  - The EVALID code and the RSCD code together uniquely identify a set of field plots and associated Phase 1 summary data used to make population estimates.
* [INTEGER]   `estimation_unit`
  - The specific geographic area that is stratified. Estimation units are often determined by a combination of geographical boundaries, sampling intensity and ownership.
* [INTEGER]   `stratum_code`
  - The code used for a particular stratum, which is unique within an RSCD, EVALID, ESTN_UNIT.
* [STRING]    `stratum_description`
  - Strata are usually based on land use (e.g., forest or nonforest) but may also be based on other criteria such as ownership (e.g., private/public/national forest).
* [INTEGER]   `state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B. For evaluations that do not conform to the boundaries of a single State the value of STATECD should be set to 99.
* [INTEGER]   `phase_1_point_count`
  - The number of basic units (pixels or points) in the stratum.
* [INTEGER]   `phase_2_point_count`
  - The number of field plots that are within the stratum.
* [FLOAT]     `expansion_factor`
  - expansion_factor
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
* [STRING]    `adj_factor_regen_micr`
* [STRING]    `adj_factor_inv_subp`
* [STRING]    `adj_factor_p2veg_subp`
* [STRING]    `adj_factor_grndlyr_quad`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
