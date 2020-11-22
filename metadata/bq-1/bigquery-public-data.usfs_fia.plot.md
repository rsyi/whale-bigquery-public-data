# `usfs_fia.plot`
`bq-1` | `bigquery-public-data`
Description of the plot sampled on the ground. Note that locations are not exact, please see pg 1-6 of FIA documentation for full description. 

Pages in FIA documentation: 1-6, 2-9

## Column details
* [INTEGER]   `plot_sequence_number`
  - Foreign key linking the subplot record to the plot record
* [INTEGER]   `survey_sequence_number`
  - Foreign key linking the plot record to the survey record.
* [INTEGER]   `county_sequence_number`
  - Foreign key linking the snapshot record to the county record.
* [INTEGER]   `previous_plot_sequence_number`
  - Foreign key linking the plot record to the previous inventory's plot record for this location. Only populated on remeasurement plots.
* [INTEGER]   `plot_inventory_year`
  - The year that best represents when the inventory data were collected. Under the annual inventory system, a group of plots is selected each year for sampling. The selection is based on a panel system. Inventory year is the year in which the majority of plots in that group were collected (plots in the group have the same panel and, if applicable, subpanel). Under periodic inventory, a reporting inventory year was selected, usually based on the year in which the majority of the plots were collected or the mid-point of the years over which the inventory spanned. For either annual or periodic inventory, Inventory year is not necessarily the same as measurement year.
* [INTEGER]   `plot_state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B.
* [STRING]    `plot_state_code_name`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B.
* [INTEGER]   `plot_survey_unit_code`
  - Forest Inventory and Analysis survey unit identification number. Survey units are usually groups of counties within each State. For periodic inventories, Survey units may be made up of lands of particular owners. Refer to appendix B for codes.
* [INTEGER]   `plot_county_code`
  - The identification number for a county, parish, watershed, borough, or similar governmental unit in a State. FIPS codes from the Bureau of the Census are used. Refer to appendix B for codes.
* [INTEGER]   `plot_phase_2_plot_number`
  - An identifier for a plot. Along with tree state code, tree inventory year, tree survey unit code, Tree county code and/or some other combination of variables, tree phase 2 plot number may be used to uniquely identify a plot.
* [INTEGER]   `plot_status_code`
  - A code that describes the sampling status of the plot. Blank (null) values may be present for periodic inventories.
* [STRING]    `plot_status_code_name`
  - A code that describes the sampling status of the plot. Blank (null) values may be present for periodic inventories.
* [INTEGER]   `plot_nonsampled_reason_code`
  - For entire plots that cannot be sampled, one of the following reasons is recorded.
* [STRING]    `plot_nonsampled_reason_code_name`
  - For entire plots that cannot be sampled, one of the following reasons is recorded.
* [INTEGER]   `measurement_year`
  - The year in which the plot was completed. Measurement year may differ from plot inventory year.
* [INTEGER]   `measurement_month`
  - The month in which the plot was completed. May be blank (null) for periodic inventory or when plot status code = 3
* [STRING]    `measurement_month_name`
  - The month in which the plot was completed. May be blank (null) for periodic inventory.
* [INTEGER]   `measurement_day`
  - The day of the month in which the plot was completed. May be blank (null) for periodic inventory or when plot status code = 3.
* [FLOAT]     `remeasurement_period`
  - The number of years between measurements for remeasured plots. This attribute is null (blank) for new plots or remeasured plots that are not used for growth, removals, or mortality estimates. For data processed with NIMS, REMPER, remeasurement period, is the number of years between measurements (to the nearest 0.1 year). For data processed with systems other than NIMS, remeasurement period is based on the number of growing seasons between measurements. Allocation of parts of the growing season by month is different for each FIA work unit. Contact the appropriate FIA work unit for information on how this is done for a particular State.
* [INTEGER]   `sample_kind_code`
  - A code indicating the type of plot installation. Database users may also want to examine plot design code to obtain additional information about the kind of plot being selected.
* [STRING]    `sample_kind_code_name`
  - A code indicating the type of plot installation. Database users may also want to examine plot design code to obtain additional information about the kind of plot being selected.
* [INTEGER]   `plot_design_code`
  - A code indicating the type of plot design used to collect the data. Refer to appendix I for a list of codes and descriptions.
* [INTEGER]   `horizontal_distance_to_improved_road_code`
  - The straight-line distance from plot center to the nearest improved road, which is a road of any width that is maintained as evidenced by pavement, gravel, grading, ditching, and/or other improvements. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.0) and populated by some FIA work units for inventory plots collected where MANUAL <1.0.
* [STRING]    `horizontal_distance_to_improved_road_code_name`
  - The straight-line distance from plot center to the nearest improved road, which is a road of any width that is maintained as evidenced by pavement, gravel, grading, ditching, and/or other improvements. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.0) and populated by some FIA work units for inventory plots collected where MANUAL <1.0.
* [INTEGER]   `water_on_plot_code`
  - Water body <1 acre in size or a stream <30 feet wide that has the greatest impact on the area within the forest land portion of the four subplots. The coding hierarchy is listed in order from large permanent water to temporary water. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.0) and populated by some FIA work units for inventory plots collected where MANUAL <1.0.
* [STRING]    `water_on_plot_code_name`
  - Water body <1 acre in size or a stream <30 feet wide that has the greatest impact on the area within the forest land portion of the four subplots. The coding hierarchy is listed in order from large permanent water to temporary water. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.0) and populated by some FIA work units for inventory plots collected where MANUAL <1.0.
* [FLOAT]     `latitude`
  - The approximate latitude of the plot in decimal degrees using NAD 83 datum (these Pacific Islands plots use WSG84 datum - SURVEY.RSCD = 26 and SURVEY.STATECD = 60, 64, 66, 68, 69, or 70). Actual plot coordinates cannot be released because of a Privacy provision enacted by Congress in the Food Security Act of 1985. Therefore, this attribute is approximately +/- 1 mile and, for annual inventory data, most plots are within +/- ½ mile. Annual data have additional uncertainty for private plots caused by swapping plot coordinates for up to 20 percent of the plots. In some cases, the county centroid is used when the actual coordinate is not available.
* [FLOAT]     `longitude`
  - The approximate longitude of the plot in decimal degrees using NAD 83 datum (these Pacific Islands plots use WSG84 datum - SURVEY.RSCD = 26 and SURVEY.STATECD = 60, 64, 66, 68, 69, or 70). Actual plot coordinates cannot be released because of a Privacy provision enacted by Congress in the Food Security Act of 1985. Therefore, this attribute is approximately +/- 1 mile and, for annual inventory data, most plots are within +/- ½ mile. Annual data have additional uncertainty for private plots caused by swapping plot coordinates for up to 20 percent of the plots. In some cases, the county centroid is used when the actual coordinate is not available.
* [INTEGER]   `elevation`
  - The distance the plot is located above sea level. Rounded to the nearest 10-foot category for certain FIA work units (SURVEY.RSCD = 23 or 24), and rounded to the nearest 100-foot category for other FIA work units (SURVEY.RSCD = 22, 26, 27, or 33). Negative values indicate distance below sea level.
* [INTEGER]   `type_of_annual_volume_growth_code`
  - A code indicating how volume growth is estimated. Current annual growth is an estimate of the amount of volume that was added to a tree in the year before the tree was sampled, and is based on the measured diameter increment recorded when the tree was sampled or on a modeled diameter for the previous year. Periodic annual growth is an estimate of the average annual change in volume occurring between two measurements, usually the current inventory and the previous inventory, where the same plot is evaluated twice. Periodic annual growth is the increase in volume between inventories divided by the number of years between each inventory. This attribute is blank (null) if the plot does not contribute to the growth estimate.
* [STRING]    `type_of_annual_volume_growth_code_name`
  - A code indicating how volume growth is estimated. Current annual growth is an estimate of the amount of volume that was added to a tree in the year before the tree was sampled, and is based on the measured diameter increment recorded when the tree was sampled or on a modeled diameter for the previous year. Periodic annual growth is an estimate of the average annual change in volume occurring between two measurements, usually the current inventory and the previous inventory, where the same plot is evaluated twice. Periodic annual growth is the increase in volume between inventories divided by the number of years between each inventory. This attribute is blank (null) if the plot does not contribute to the growth estimate.
* [INTEGER]   `type_of_annual_mortality_volume_code`
  - A code indicating how mortality volume is estimated. Current annual mortality is an estimate of the volume of trees dying in the year before the plot was measured, and is based on the year of death or on a modeled estimate. Periodic annual mortality is an estimate of the average annual volume of trees dying between two measurements, usually the current inventory and previous inventory, where the same plot is evaluated twice. Periodic annual mortality is the loss of volume between inventories divided by the number of years between each inventory. Periodic average annual mortality is the most common type of annual mortality estimated. This attribute is blank (null) if the plot does not contribute to the mortality estimate.
* [STRING]    `type_of_annual_mortality_volume_code_name`
  - A code indicating how mortality volume is estimated. Current annual mortality is an estimate of the volume of trees dying in the year before the plot was measured, and is based on the year of death or on a modeled estimate. Periodic annual mortality is an estimate of the average annual volume of trees dying between two measurements, usually the current inventory and previous inventory, where the same plot is evaluated twice. Periodic annual mortality is the loss of volume between inventories divided by the number of years between each inventory. Periodic average annual mortality is the most common type of annual mortality estimated. This attribute is blank (null) if the plot does not contribute to the mortality estimate.
* [INTEGER]   `phase_2_panel_number`
  - The value for Phase 2 panel number ranges from 1 to 5 for annual inventories and is blank (null) for periodic inventories. A panel is a sample in which the same elements are measured on two or more occasions. FIA divides the plots in each State into 5 panels that can be used to independently sample the population.
* [INTEGER]   `phase_3_panel_number`
  - A panel is a sample in which the same elements are measured on two or more occasions. FIA divides the plots in each State into 5 panels that can be used to independently sample the population. The value for Phase 3 panel number ranges from 1 to 5 for those plots where Phase 3 data were collected. If the plot is not a Phase 3 plot, then this attribute is left blank (null).
* [STRING]    `ecological_subsection_code`
  - An area of similar surficial geology, lithology, geomorphic process, soil groups, subregional climate, and potential natural communities. Subsection boundaries usually correspond with discrete changes in geomorphology. Subsection information is used for broad planning and assessment. Subsection codes for the coterminous United States were developed as part of the "Ecological Subregions: Sections and Subsections for the Conterminous United States" (Cleland and others 2007). For Alaska, the ecological section codes are equivalent to the ecoregions designated by Nowacki and others in Ecoregions of Alaska: 2001. U.S. Geological Survey Open-File Report 02-297 (map). The ecological subsection code is based on fuzzed and swapped plot coordinates. This attribute is coded for the coterminous United States, southeast and south coastal Alaska, and is left blank (null) in all other instances
* [INTEGER]   `congressional_district_code`
  - A territorial division of a State from which a member of the U.S. House of Representatives is elected. The congressional district code assigned to a plot (regardless of when it was measured) is for the current Congress; the assignment is made based on the plot's approximate coordinates. CONGCD is a four-digit number. The first two digits are the State FIPS code and the last two digits are the congressional district number. If a State has only one congressional district, the congressional district number is 00. If a plot's congressional district assignment falls in a State other than the plot's actual State due to using the approximate coordinates, the congressional district code will be for the nearest congressional district in the correct State. This attribute is coded for the coterminous States and Alaska, and is left blank (null) in all other instances. For more information about the coverage used to assign this attribute, see National Atlas of the United States (2007).
* [FLOAT]     `manual_version_number`
  - Version number of the Field Guide used to describe procedures for collecting data on the plot. The National FIA Field Guide began with version 1.0; therefore data taken using the National Field procedures will have PLOT.MANUAL 1.0. Data taken according to field instructions prior to the use of the National Field Guide have PLOT.MANUAL <1.0.
* [INTEGER]   `sample_kind_code_north_central`
  - This attribute is populated through 2005 for the former North Central work unit (SURVEY.RSCD = 23) and is blank (null) for all other FIA work units.
* [INTEGER]   `quality_assurance_status`
  - A code indicating the type of plot data collected. Populated for all forested subplots using the National Field Guide protocols (MANUAL 1.0). Codes 2-6 indicate additional quality assurance data that are not included in the FIADB.
* [STRING]    `quality_assurance_status_name`
  - A code indicating the type of plot data collected. Populated for all forested subplots using the National Field Guide protocols (MANUAL 1.0). Codes 2-6 indicate additional quality assurance data that are not included in the FIADB.
* [STRING]    `plot_created_by`
  - The employee who created the record. This attribute is intentionally left blank in download files.
* [DATE]      `plot_created_date`
  - The date the record was created.
* [INTEGER]   `plot_created_in_instance`
  - The database instance in which the record was created. Each computer system has a unique database instance code and this attribute stores that information to determine on which computer the record was created.
* [STRING]    `plot_modified_by`
  - The employee who modified the record. This field will be blank (null) if the data have not been modified since initial creation. This attribute is intentionally left blank in download files.
* [DATE]      `plot_modified_date`
  - The date the record was last modified. This field will be blank (null) if the data have not been modified since initial creation.
* [INTEGER]   `plot_modified_in_instance`
  - The database instance in which the record was modified. This field will be blank (null) if the data have not been modified since initial creation.
* [STRING]    `microplot_location`
  - Values are 'OFFSET' or 'CENTER.' The offset microplot center is located 12 feet due east (90 degrees) of subplot center. The current standard is that the microplot is located in the 'OFFSET' location, but some earlier inventories, including some early panels of the annual inventory, may contain data where the microplot was located at the 'CENTER' location. Populated for annual inventory and may be populated for periodic inventory.
* [FLOAT]     `declination`
  - The azimuth correction used to adjust magnetic north to true north. All azimuths are assumed to be magnetic azimuths unless otherwise designated. The Portland FIA work unit historically has corrected all compass readings for true north. This field is to be used only in cases where FIA work units are adjusting azimuths to correspond to true north; for FIA work units using magnetic azimuths, this field will always be set = 0 in the office. This field carries a decimal place because the USGS corrections are provided to the nearest half degree. DECLINATION is defined as: DECLINATION = (TRUE NORTH - MAGNETIC NORTH)
* [INTEGER]   `emap_hexagon`
  - The identifier for the approximately 160,000 acre Environmental Monitoring and Assessment Program (EMAP) hexagon in which the plot is located. EMAP hexagons are available to the public, cover the coterminous United States, and have been used in summarizing and aggregating data about numerous natural resources. Populated for annual inventory and may be populated for periodic inventory.
* [INTEGER]   `sample_method_code`
  - A code indicating if the plot was observed in the field or remotely sensed in the office.
* [STRING]    `sample_method_code_name`
  - A code indicating if the plot was observed in the field or remotely sensed in the office.
* [INTEGER]   `subplots_examined_code`
  - A code indicating the number of subplots examined. By default, plot status code = 1 plots have all 4 subplots examined.
* [STRING]    `subplots_examined_code_name`
  - A code indicating the number of subplots examined. By default, plot status code = 1 plots have all 4 subplots examined.
* [INTEGER]   `macroplot_breakpoint_diameter`
  - A macroplot breakpoint diameter is the diameter (either DBH or DRC) above which trees are measured on the plot extending from 0.01 to 58.9 feet horizontal distance from the center of each subplot. Examples of different breakpoint diameters used by western FIA work units are 24 inches or 30 inches (Pacific Northwest), or 21 inches (Interior West). Installation of macroplots is core optional and is used to have a larger plot size in order to more adequately sample large trees. If macroplots are not being installed, this item will be left blank (null).
* [INTEGER]   `intensity`
  - A code used to identify federal base grid annual inventory plots and plots that have been added to intensify a particular sample. Under the federal base grid, one plot is collected in each theoretical hexagonal polygon, which is slightly more than 5,900 acres in size. Plots with INTENSITY = 1 are part of the federal base grid. In some instances, States and/or agencies have provided additional support to increase the sampling intensity for an area. Supplemental plots have INTENSITY set to higher numbers depending on the amount of plot intensification chosen for the particular estimation unit. Populated for annual inventory data only.
* [INTEGER]   `plot_inventory_cycle_number`
  - A number assigned to a set of plots, measured over a particular period of time from which a State estimate using all possible plots is obtained. A cycle number >1 does not necessarily mean that information for previous cycles resides in the database. A cycle is relevant for periodic and annual inventories.
* [INTEGER]   `plot_inventory_subcycle_number`
  - For an annual inventory that takes n years to measure all plots, subcycle shows in which of the n years of the cycle the data were measured. Subcycle is 0 for a periodic inventory. Subcycle 99 may be used for plots that are not included in the estimation process.
* [STRING]    `ecological_unit_pacific_northwest_research_station`
  - Plots taken by PNW FIA are assigned to the ecological unit in which they are located. Certain units have stocking adjustments made to the plots that occur on very low productivity lands, which thereby reduces the estimated potential productivity of the plot. More information can be found in MacLean (1973). Only collected by certain FIA work units (SURVEY.RSCD = 26 or 27).
* [INTEGER]   `topographic_position_pacific_northwest_research_station`
  - The topographic position that describes the plot area. Illustrations available in Plot section of the PNW field guide located at the web page for PNW FIA Field Manuals (http://www.fs.fed.us/pnw/fia/publications/fieldmanuals.shtml). Adapted from information found in Wilson (1900). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `topographic_position_pacific_northwest_research_station_name`
  - The topographic position that describes the plot area. Illustrations available in Plot section of the PNW field guide located at the web page for PNW FIA Field Manuals (http://www.fs.fed.us/pnw/fia/publications/fieldmanuals.shtml). Adapted from information found in Wilson (1900). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `nonforest_sampling_status_code`
  - A code indicating whether or not the plot is part of a nonforest inventory. If Nonforest sampling status code = 1, then the entire suite of attributes that are measured on forest lands were measured.
* [STRING]    `nonforest_sampling_status_code_name`
  - A code indicating whether or not the plot is part of a nonforest inventory. If Nonforest sampling status code = 1, then the entire suite of attributes that are measured on forest lands were measured.
* [INTEGER]   `nonforest_plot_status_code`
  - A code describing the sampling status of the nonforest plot
* [STRING]    `nonforest_plot_status_code_name`
  - A code describing the sampling status of the nonforest plot
* [INTEGER]   `nonforest_plot_nonsampled_reason_code`
  - A code indicating the reason the nonforest plot was not sampled.
* [STRING]    `nonforest_plot_nonsampled_reason_code_name`
  - A code indicating the reason the nonforest plot was not sampled.
* [INTEGER]   `p2_vegetation_sampling_status_code`
  - Level of detail (LOD). A code indicating whether data were collected for vegetation structure growth habits only, or for individual species (that qualify as most abundant) as well. If LOD = 3, then a tree species could be recorded twice, but it would have two different species growth habits.
* [STRING]    `p2_vegetation_sampling_status_code_name`
  - Level of detail (LOD). A code indicating whether data were collected for vegetation structure growth habits only, or for individual species (that qualify as most abundant) as well. If LOD = 3, then a tree species could be recorded twice, but it would have two different species growth habits.
* [INTEGER]   `p2_vegetation_sampling_level_detail_code`
  - Level of detail (LOD). A code indicating whether data were collected for vegetation structure growth habits only, or for individual species (that qualify as most abundant) as well. If LOD = 3, then a tree species could be recorded twice, but it would have two different species growth habits.
* [STRING]    `p2_vegetation_sampling_level_detail_code_name`
  - Level of detail (LOD). A code indicating whether data were collected for vegetation structure growth habits only, or for individual species (that qualify as most abundant) as well. If LOD = 3, then a tree species could be recorded twice, but it would have two different species growth habits.
* [INTEGER]   `invasive_sampling_status_code`
  - A code indicating whether Invasive plant data were recorded on the plot and the land class(es) on which the data were recorded.
* [STRING]    `invasive_sampling_status_code_name`
  - A code indicating whether Invasive plant data were recorded on the plot and the land class(es) on which the data were recorded.
* [INTEGER]   `invasive_specimen_rule_code`
  - A code indicating if specimen collection was required.
* [STRING]    `invasive_specimen_rule_code_name`
  - A code indicating if specimen collection was required.
* [INTEGER]   `design_code_periodic_to_annual`
  - The plot design for the periodic plots that were remeasured in the annual inventory (plot design code = 1). Refer to appendix I for a list of codes and descriptions.
* [FLOAT]     `manual_version_of_the_data`
  - Version of the National Field Guide used to describe procedures for collecting data on the plot. The data in the database have been standardized to this version. Versions of the national field guide are available on the FIA web site (http://www.fia.fs.fed.us/library/field-guides-methods-proc/index.php).
* [INTEGER]   `subpanel`
  - Annual inventory subpanel assignment for the plot for FIA work units using subpaneling. FIA uses a 5-panel system (see phase 2 panel number), but may further subdivide the 5 panels into subpanels. The following FIA work units subdivide each phase 2 panel number into 2 subpanels (SUBPANEL = 1 or 2), for a total of 10 subpanels. For these FIA work units, 1 subpanel is usually scheduled for measurement each year: RMRS (SURVEY.RSCD = 22); PNWRS (SURVEY.RSCD = 26 or 27); SRS (SURVEY.RSCD = 33, only for Oklahoma where UNITCD 3. Populated for all plots using the National Field Guide protocols (MANUAL 1.0).
* [STRING]    `subpanel_name`
  - Annual inventory subpanel assignment for the plot for FIA work units using subpaneling. FIA uses a 5-panel system (see phase 2 panel number), but may further subdivide the 5 panels into subpanels. The following FIA work units subdivide each phase 2 panel number into 2 subpanels (SUBPANEL = 1 or 2), for a total of 10 subpanels. For these FIA work units, 1 subpanel is usually scheduled for measurement each year: RMRS (SURVEY.RSCD = 22); PNWRS (SURVEY.RSCD = 26 or 27); SRS (SURVEY.RSCD = 33, only for Oklahoma where UNITCD 3. Populated for all plots using the National Field Guide protocols (MANUAL 1.0).
* [STRING]    `unique_plot`
  - It is a unique identifier with the combination of plot state code, plot inventory year, plot survey unit code, plot county code & plot phase 2 plot number.
* [STRING]    `colocated_code_rmrs`
* [STRING]    `condchng_code_rmrs`
* [STRING]    `futfor_code_rmrs`
* [STRING]    `manual_ncrs`
* [STRING]    `manual_ners`
* [STRING]    `manual_rmrs`
* [STRING]    `pac_island_pnwrs`
* [STRING]    `plot_season_ners`
* [STRING]    `precipitation`
* [STRING]    `prev_microplot_loc_rmrs`
* [STRING]    `prev_plot_status_code_rmrs`
* [STRING]    `reuse_code_1`
* [STRING]    `reuse_code_2`
* [STRING]    `reuse_code_3`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
