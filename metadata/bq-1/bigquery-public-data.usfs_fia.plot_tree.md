# `usfs_fia.plot_tree`
`bq-1` | `bigquery-public-data`
Join of the plot and tree table. Joined on the plot sequence number and tree.plot_sequence_number fields. 	

Pages in FIA Documentation: 2-9, 3-3

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
* [INTEGER]   `tree_sequence_number`
  - Foreign key linking the tree regional biomass record to the tree record.
* [INTEGER]   `previous_tree_sequence_number`
  - Foreign key linking the tree to the previous inventory's tree record for this tree. Only populated on trees remeasured from a previous annual inventory.
* [INTEGER]   `tree_inventory_year`
  - The year that best represents when the inventory data were collected. Under the annual inventory system, a group of plots is selected each year for sampling. The selection is based on a panel system. Inventory year is the year in which the majority of plots in that group were collected (plots in the group have the same panel and, if applicable, subpanel). Under periodic inventory, a reporting inventory year was selected, usually based on the year in which the majority of the plots were collected or the mid-point of the years over which the inventory spanned. For either annual or periodic inventory, Inventory year is not necessarily the same as measurement year.
* [INTEGER]   `tree_state_code`
  - Bureau of the Census Federal Information Processing Standards (FIPS) two-digit code for each State. Refer to appendix B.
* [INTEGER]   `tree_survey_unit_code`
  - Forest Inventory and Analysis survey unit identification number. Survey units are usually groups of counties within each State. For periodic inventories, Survey units may be made up of lands of particular owners. Refer to appendix B for codes.
* [INTEGER]   `tree_county_code`
  - The identification number for a county, parish, watershed, borough, or similar governmental unit in a State. FIPS codes from the Bureau of the Census are used. Refer to appendix B for codes.
* [INTEGER]   `tree_phase_2_plot_number`
  - An identifier for a plot. Along with state code, inventory year, tree survey unit code, County code and/or some other combinations of variables, PLOT may be used to uniquely identify a plot.
* [INTEGER]   `subplot_number`
  - The number assigned to the subplot. The national plot design (PLOT.DESIGNCD = 1) has subplot number values of 1 through 4. Other plot designs have various subplot number values. See PLOT.DESIGNCD and appendix I for information about plot designs. For more explanation about SUBP, contact the appropriate FIA work unit (table 1-1).
* [INTEGER]   `tree_record_number`
  - A number used to uniquely identify a tree on a subplot. Tree numbers can be used to track trees when PLOT.DESIGNCD is the same between inventories.
* [INTEGER]   `condition_class_number`
  - The unique identifying number assigned to a condition on which the seedling is located. See COND.CONDID for details on the attributes which delineate a condition.
* [INTEGER]   `azimuth`
  - The direction, to the nearest degree, from subplot center to the center of the base of the tree (geographic center for multi-stemmed woodland species). Due north is represented by 360 degrees.
* [FLOAT]     `horizontal_distance`
  - The horizontal distance in feet from subplot center (microplot center for saplings) to the center of the base of the tree (geographic center for multi-stemmed woodland species). This attribute is populated for live and standing dead trees 1.0 inch DBH/DRC in a forest condition that were measured on any of the four subplots of the national plot design. It may be populated for other tree records.
* [INTEGER]   `previous_condition_number`
  - Identifies the condition within the plot on which the tree occurred at the previous inventory
* [INTEGER]   `tree_status_code`
  - A code indicating whether the sample tree is live, cut, or dead at the time of measurement. Includes dead and cut trees, which are required to estimate aboveground biomass and net annual volume for growth, mortality, and removals. This code is not used when querying data for change estimates.
* [STRING]    `tree_status_code_name`
  - A code indicating whether the sample tree is live, cut, or dead at the time of measurement. Includes dead and cut trees, which are required to estimate aboveground biomass and net annual volume for growth, mortality, and removals. This code is not used when querying data for change estimates.
* [INTEGER]   `species_code`
  - An FIA tree species code. Refer to appendix F for codes.
* [STRING]    `species_common_name`
  - An FIA tree species code. Refer to appendix F for codes.
* [STRING]    `species_scientific_name`
  - An FIA tree species code. Refer to appendix F for codes.
* [INTEGER]   `species_group_code`
  - A code assigned to each tree species in order to group them for reporting purposes on presentation tables. Codes and their associated names are shown in appendix E. Individual tree species and corresponding species group codes are shown in appendix F.
* [STRING]    `species_group_code_name`
  - A code assigned to each tree species in order to group them for reporting purposes on presentation tables. Codes and their associated names are shown in appendix E. Individual tree species and corresponding species group codes are shown in appendix F.
* [FLOAT]     `current_diameter`
  - The current diameter (in inches) of the sample tree at the point of diameter measurement. DIA is measured at either breast height (DBH) or at root collar (DRC). DBH is usually measured at 4.5 feet above the ground line on the uphill side of the tree. DRC is measured on woodland species (often multi-stemmed) at the ground line or at the stem root collar, whichever is higher. DRC is computed using the following formula: DRC = SQRT [SUM (stem diameter2)] For additional information about where the tree diameter is measured, see Diameter height code or Height to diameter measurement point. Current diameter for live trees contains the measured value. DIA for cut and dead trees presents problems associated with uncertainty of when the tree was cut or died as well as structural deterioration of dead trees. Consult individual FIA work units for explanations of how Current diameter is collected for dead and cut trees.
* [INTEGER]   `diameter_height_code`
  - A code indicating the location at which diameter was measured. For trees with code 1 (DBH), the actual measurement point may be found in Height to diameter measurement point.
* [STRING]    `diameter_height_code_name`
  - A code indicating the location at which diameter was measured. For trees with code 1 (DBH), the actual measurement point may be found in Height to diameter measurement point.
* [INTEGER]   `total_height`
  - The total length (height) of a sample tree (in feet) from the ground to the tip of the apical meristem beginning in PLOT.MANUAL = 1.1. The total length of a tree is not always its actual length. If the main stem is broken, the actual length is measured or estimated and the missing piece is added to the actual length to estimate total length. The amount added is determined by measuring the broken piece if it can be located on the ground; otherwise it is estimated. The minimum height for timber species is 5 feet and for woodland species is 1 foot. Starting with PLOT.MANUAL = 7.0, the Core minimum diameter to qualify for a standing dead tree was changed from 5.0 inches to 1.0 inch.
* [INTEGER]   `height_method_code`
  - A code indicating how length (height) was determined beginning in PLOT.MANUAL = 1.1. Starting with PLOT.MANUAL = 7.0, the Core minimum diameter to qualify for a standing dead tree was changed from 5.0 inches to 1.0 inch.
* [STRING]    `height_method_code_name`
  - A code indicating how length (height) was determined beginning in PLOT.MANUAL = 1.1. Starting with PLOT.MANUAL = 7.0, the Core minimum diameter to qualify for a standing dead tree was changed from 5.0 inches to 1.0 inch.
* [INTEGER]   `actual_height`
  - The length (height) of the tree to the nearest foot from ground level to the highest remaining portion of the tree still present and attached to the bole. If ACTUALHT = HT, then the tree does not have a broken top. If ACTUALHT <HT, then the tree does have a broken or missing top. The minimum height for timber species is 5 feet and for woodland species is 1 foot. Starting with PLOT.MANUAL = 7.0, the Core minimum diameter to qualify for a standing dead tree was changed from 5.0 inches to 1.0 inch.
* [INTEGER]   `tree_class_code`
  - A code indicating the general quality of the tree. In annual inventory, this is the tree class for both live and dead trees at the time of current measurement. In periodic inventory, for cut and dead trees, this is the tree class of the tree at the time it died or was cut. Therefore, cut and dead trees collected in periodic inventory can be coded as growing-stock trees.
* [STRING]    `tree_class_code_name`
  - A code indicating the general quality of the tree. In annual inventory, this is the tree class for both live and dead trees at the time of current measurement. In periodic inventory, for cut and dead trees, this is the tree class of the tree at the time it died or was cut. Therefore, cut and dead trees collected in periodic inventory can be coded as growing-stock trees.
* [INTEGER]   `compacted_crown_ratio`
  - The percent of the tree bole supporting live, healthy foliage (the crown is ocularly compacted to fill in gaps) when compared to actual length (Actual Height). When PLOT.MANUAL <1.0 the variable may have been a code, which was converted to the midpoint of the ranges represented by the codes, and is stored as a percentage. May not be populated for periodic inventories.
* [INTEGER]   `crown_class_code`
  - A code indicating the amount of sunlight received and the crown position within the canopy.
* [STRING]    `crown_class_code_name`
  - A code indicating the amount of sunlight received and the crown position within the canopy.
* [INTEGER]   `tree_grade_code`
  - A code indicating the quality of sawtimber trees. This attribute is populated for live, growing-stock, sawtimber trees on subplots 1-4 where PLOT.MANUAL 1.0 for plots that are in a forest condition class. This attribute may be populated for other tree records that do not meet the above criteria. For example, it may be populated with the previous tree grade on dead and cut trees. Standards for tree grading are specific to species and differ slightly by research station. Only collected by certain FIA work units (SURVEY.RSCD = 23, 24, or 33). Tree grade codes range from 1 to 5.
* [INTEGER]   `cause_death_agent_code`
  - When PLOT.MANUAL 1.0, this variable was collected on only dead and cut trees. When PLOT.MANUAL <1.0, this variable was collected on all trees (live, dead, and cut). Cause of damage was recorded for live trees if the presence of damage or pathogen activity was serious enough to reduce the quality or vigor of the tree. When a tree was damaged by more than one agent, the most severe damage was coded. When no damage was observed on a live tree, 00 was recorded. Damage recorded for dead trees was the cause of death. Each FIA program records specific codes that may differ from one State to the next. These codes fall within the ranges listed below. For the specific codes used in a particular State, contact the FIA work unit responsible for that State (table 1-1).
* [STRING]    `cause_death_agent_code_name`
  - When PLOT.MANUAL 1.0, this variable was collected on only dead and cut trees. When PLOT.MANUAL <1.0, this variable was collected on all trees (live, dead, and cut). Cause of damage was recorded for live trees if the presence of damage or pathogen activity was serious enough to reduce the quality or vigor of the tree. When a tree was damaged by more than one agent, the most severe damage was coded. When no damage was observed on a live tree, 00 was recorded. Damage recorded for dead trees was the cause of death. Each FIA program records specific codes that may differ from one State to the next. These codes fall within the ranges listed below. For the specific codes used in a particular State, contact the FIA work unit responsible for that State (table 1-1).
* [INTEGER]   `rotten_and_missing_cull`
  - The percent of the cubic-foot volume in a live or dead tally tree that is rotten or missing. This is a calculated value that includes field-recorded cull (rotten missing cull field recorded) and any additional cull due to broken top.
* [INTEGER]   `damage_location_1`
  - A code indicating where damage (meeting or exceeding a severity threshold, as defined in the field guide) is present on the tree.
* [STRING]    `damage_location_1_name`
  - A code indicating where damage (meeting or exceeding a severity threshold, as defined in the field guide) is present on the tree
* [INTEGER]   `damage_type_1`
  - A code indicating the kind of damage (meeting or exceeding a severity threshold, as defined in the field guide) present. If Damage location 1 = 0, then Damage type 1 = blank (null).
* [STRING]    `damage_type_1_name`
  - A code indicating the kind of damage (meeting or exceeding a severity threshold, as defined in the field guide) present. If Damage location 1 = 0, then Damage type 1 = blank (null).
* [INTEGER]   `damage_severity_1`
  - A code indicating how much of the tree is affected. Valid severity codes vary by damage type and damage location and must exceed a threshold value, as defined in the field guide. If Damage Location 1 = 0, then Damage severity 1 = blank (null).
* [STRING]    `damage_severity_1_name`
  - A code indicating how much of the tree is affected. Valid severity codes vary by damage type and damage location and must exceed a threshold value, as defined in the field guide. If Damage Location 1 = 0, then Damage severity 1 = blank (null).
* [INTEGER]   `damage_location_2`
  - A code indicating where secondary damage (meeting or exceeding a severity threshold, as defined in the field guide) is present. Use same codes as Damage location 1. If Damage location 1 = 0, then Damage location 2 = blank (null) or 0.
* [STRING]    `damage_location_2_name`
  - A code indicating where secondary damage (meeting or exceeding a severity threshold, as defined in the field guide) is present. Use same codes as Damage location 1. If Damage location 1 = 0, then Damage location 2 = blank (null) or 0.
* [INTEGER]   `damage_type_2`
  - A code indicating the kind of secondary damage (meeting or exceeding a severity threshold, as defined in the field guide) present. Use same codes as Damage type 1. If Damage location 1 = 0, then Damage type 2 = blank (null).
* [STRING]    `damage_type_2_name`
  - A code indicating the kind of secondary damage (meeting or exceeding a severity threshold, as defined in the field guide) present. Use same codes as Damage type 1. If Damage location 1 = 0, then Damage type 2 = blank (null).
* [INTEGER]   `damage_severity_2`
  - A code indicating how much of the tree is affected by the secondary damage. Valid severity codes vary by damage type and damage location and must exceed a threshold value, as defined in the field guide. Use same codes as Damage severity 1. If Damage location 1 = 0, then Damage severity 2 = blank (null).
* [STRING]    `damage_severity_2_name`
  - A code indicating how much of the tree is affected by the secondary damage. Valid severity codes vary by damage type and damage location and must exceed a threshold value, as defined in the field guide. Use same codes as Damage severity 1. If Damage location 1 = 0, then Damage severity 2 = blank (null).
* [INTEGER]   `decay_class_code`
  - A code indicating the stage of decay that predominates along the recorded total length of the CWD piece. Decay class code is used to reduce biomass based on ratios stored in the REF_SPECIES table.
* [STRING]    `decay_class_code_name`
  - A code indicating the stage of decay that predominates along the recorded total length of the CWD piece. Decay class code is used to reduce biomass based on ratios stored in the REF_SPECIES table.
* [FLOAT]     `tree_stocking`
  - The stocking value computed for each live tree. Stocking values are computed using several specific species equations that were developed from normal yield tables and stocking charts. Resultant values are a function of diameter. The stocking of individual trees is used to calculate COND.GSSTK, COND.GSSTKCD, COND.ALSTK, and COND.ALSTKCD.
* [INTEGER]   `woodland_tree_species_stem_count`
  - The number of live and dead stems used to calculate diameter on a woodland tree. Woodland species are identified in the REF_SPECIES table as REF_SPECIES.WOODLAND = X. These tree species have diameter measured at the root collar. For a stem to be counted, it must have a minimum stem size of 1 inch in diameter and 1 foot in length.
* [FLOAT]     `net_cubicfoot_volume`
  - For timber species (trees where the diameter is measured at breast height [DBH]), this is the net volume of wood in the central stem of a sample tree 5.0 inches in diameter, from a 1-foot stump to a minimum 4-inch top diameter, or to where the central stem breaks into limbs all of which are <4.0 inches in diameter. For woodland species, net cubicfoot volume is the net volume of wood and bark from the DRC measurement point(s) to a 1½-inch top diameter; includes branches that are at least 1½ inches in diameter along the length of the branch. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the Tree Net Growth, Removal, and Mortality Component Table table to obtain per acre information. This attribute is blank (null) for trees with DIA <5.0 inches. All trees measured after 1998 with DIA 5.0 inches (including standing dead trees) will have entries in this field. Does not include rotten, missing, and form cull.
* [FLOAT]     `gross_cubicfoot_volume`
  - For timber species (trees where the diameter is measured at breast height [DBH]), this is the net volume of wood in the central stem of a sample tree 5.0 inches in diameter, from a 1-foot stump to a minimum 4-inch top diameter, or to where the central stem breaks into limbs all of which are <4.0 inches in diameter. For woodland species, net cubicfoot volume is the net volume of wood and bark from the DRC measurement point(s) to a 1½-inch top diameter; includes branches that are at least 1½ inches in diameter along the length of the branch. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the Tree Net Growth, Removal, and Mortality Component Table table to obtain per acre information. This attribute is blank (null) for trees with DIA <5.0 inches. All trees measured after 1998 with DIA 5.0 inches (including standing dead trees) will have entries in this field. Does not include rotten, missing, and form cull.
* [FLOAT]     `net_cubicfoot_volume_sawlog_portion_sawtimber_tree`
  - The net volume of wood in the central stem of a timber species tree of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches DIA minimum for hardwoods), from a 1-foot stump to a minimum top diameter, (7.0 inches for softwoods, 9.0 inches for hardwoods) or to where the central stem breaks into limbs, all of which are less than the minimum top diameter. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the Tree Net Growth, Removal, and Mortality Component table to obtain per acre information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). All larger trees have entries in this field if they are growing-stock trees (tree class code = 2 and tree status code = 1). All rough and rotten trees (tree class code = 3 or 4) and dead and cut trees (tree status code = 2 or 3) are blank (null) in this field. Form cull and rotten/missing cull are excluded.
* [FLOAT]     `gross_cubicfoot_volume_sawlog_portion_sawtimber_tree`
  - This is the total volume of wood in the central stem of a timber species tree of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches DIA minimum for hardwoods), from a 1-foot stump to a minimum top diameter (7.0 inches for softwoods, 9.0 inches for hardwoods), or to where the central stem breaks into limbs, all of which are less than the minimum top diameter. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per acre information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). All larger trees have entries in this field if they are growing-stock trees (tree class code = 2 and tree status code = 1). All rough and rotten trees (tree class code = 3 or 4) and dead and cut trees (tree status code = 2 or 3) are blank (null) in this field.
* [FLOAT]     `net_boardfoot_volume_sawlog_portion_sawtimber_tree`
  - This is the net volume (International ¼-inch rule) of wood in the central stem of a timber species tree of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches DIA minimum for hardwoods), from a 1-foot stump to a minimum top diameter (7.0 inches for softwoods, 9.0 inches for hardwoods), or to where the central stem breaks into limbs all of which are less than the minimum top diameter. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per unit area information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). All larger trees should have entries in this field if they are growing-stock trees (tree class code = 2 and tree status code = 1). All rough and rotten trees (tree class code = 3 or 4) and dead and cut trees (tree status code = 2 or 3) are blank (null) in this field. Form cull and rotten/missing cull are excluded.
* [FLOAT]     `gross_boardfoot_volume_sawlog_portion_sawtimber_tree`
  - This is the total volume (International ¼-inch rule) of wood in the central stem of a timber species tree of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches DIA minimum for Chapter 3 (revision: 03.2017) Tree Table FIA Database Description and User Guide for Phase 2 (version: 7.0) 3-19 hardwoods), from a 1-foot stump to a minimum top diameter (7.0 inches for softwoods, 9.0 inches for hardwoods), or to where the central stem breaks into limbs all of which are less than the minimum top DIA. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per unit area information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). All larger trees should have entries in this field if they are growing-stock trees (tree class code = 2 and tree status code = 1). All rough and rotten trees (tree class code = 3 or 4) and dead and cut trees (tree status code = 2 or 3) are blank (null) in this field.
* [FLOAT]     `sound_cubicfoot_volume`
  - For timber species (trees where the diameter is measured at breast height [DBH]), the volume of sound wood in the central stem of a sample tree 5.0 inches in diameter from a 1-foot stump to a minimum 4-inch top diameter or to where the central stem breaks into limbs all of which are <4.0 inches in diameter. For woodland species (woodland species can be identified by REF_SPECIES.WOODLAND = X), sound cubicfoot volume is the net volume of wood and bark from the DRC measurement point(s) to a minimum 1½-inch top diameter; includes branches that are at least 1½ inches in diameter along the length of the branch. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per acre information. This attribute is blank (null) for trees with DIA <5.0 inches. All trees with DIA 5.0 inches (including dead trees) have entries in this field. Does not include rotten and missing cull (volume loss due to rotten and missing cull defect has been deducted).
* [FLOAT]     `net_annual_merchantable_cubicfoot_growth_growingstock_tree_timberland`
  - The net change in cubic-foot volume (net cubicfoot volume) per year of this tree (for trees on remeasured plots, (V2 - V1)/(T2 - T1)where 1 and 2 denote the past and current measurement, respectively, V is volume, and T indicates year of measurement, and T2 - T1 = PLOT.REMPER). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `net_annual_merchantable_boardfoot_growth_sawtimber_tree_timberland`
  - The net change in merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume per year of this tree (for trees on remeasured plots, (V2 - V1)/(T2 -T1)). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `net_annual_sound_cubicfoot_growth_live_tree_timberland`
  - The net change in sound cubic-foot volume (sound cubicfoot volume) per year of the tree (for trees on remeasured plots, (V2 -V1)/(T2 -T1)). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `merchantable_cubicfoot_volume_growingstock_tree_timberland_mortality_purposes`
  - The merchantable cubic-foot volume (Net cubic-foot volume at the midpoint) of the tree at the time of mortality. To obtain estimates of annual per acre mortality, multiply by Mortality trees per acre per year unadjusted.
* [FLOAT]     `merchantable_boardfoot_volume_sawtimber_tree_timberland_mortality_purposes`
  - The merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume of the tree at the time of mortality. To obtain estimates of annual per acre mortality, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `sound_cubicfoot_volume_tree_timberland_mortality_purposes`
  - The sound cubic-foot volume (sound cubicfoot volume) of the tree at the time of mortality. To obtain estimates of annual per acre mortality, multiply by mortality trees per acre per year unadjusted.
* [FLOAT]     `merchantable_cubicfoot_volume_growingstock_tree_timberland_removal_purposes`
  - The merchantable cubic-foot volume (Net cubic-foot volume at the midpoint) of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `merchantable_boardfoot_volume_sawtimber_tree_timberland_removal_purposes`
  - The merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `sound_cubicfoot_volume_live_tree_timberland_removal_purposes`
  - The sound cubic-foot volume (sound cubicfoot volume) of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [INTEGER]   `diameter_check_code`
  - A code indicating the reliability of the diameter measurement.
* [STRING]    `diameter_check_code_name`
  - A code indicating the reliability of the diameter measurement.
* [INTEGER]   `mortality_year`
  - The estimated year in which a remeasured tree died or was cut. Populated where PLOT.MANUAL 1.0 and populated by some FIA work units where PLOT.MANUAL <1.0.
* [INTEGER]   `salvable_dead_code`
  - A standing or down dead tree considered merchantable by regional standards. Contact the appropriate FIA work unit for information on how this code is assigned for a particular State (table 1-1).
* [STRING]    `salvable_dead_code_name`
  - A standing or down dead tree considered merchantable by regional standards. Contact the appropriate FIA work unit for information on how this code is assigned for a particular State (table 1-1).
* [INTEGER]   `uncompacted_live_crown_ratio`
  - Percentage determined by dividing the live crown length by the actual tree length. When PLOT.MANUAL <3.0 the variable was a code, which was converted to the midpoint of the ranges represented by the codes, and is stored as a percentage.
* [INTEGER]   `crown_position_code`
  - The relative position of each tree in relation to the overstory canopy.
* [STRING]    `crown_position_code_name`
  - The relative position of each tree in relation to the overstory canopy.
* [INTEGER]   `crown_light_exposure_code`
  - A code indicating the amount of light being received by the tree crown. Collected for all live trees at least 5 inches DBH/DRC. Trees with Uncompacted Live Crown Ratio <35 have a maximum Crown Light Exposure Code of 1.
* [STRING]    `crown_light_exposure_code_name`
  - A code indicating the amount of light being received by the tree crown. Collected for all live trees at least 5 inches DBH/DRC. Trees with Uncompacted Live Crown Ratio <35 have a maximum Crown Light Exposure Code of 1.
* [INTEGER]   `crown_vigor_code_sapling`
  - A code indicating the vigor of sapling crowns. Collected for live trees between 1 and 4.9 inches DBH/DRC.
* [STRING]    `crown_vigor_code_sapling_name`
  - A code indicating the vigor of sapling crowns. Collected for live trees between 1 and 4.9 inches DBH/DRC.
* [INTEGER]   `crown_density_code`
  - A code indicating how dense the tree crown is, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC. Crown density is the amount of crown branches, foliage and reproductive structures that blocks light visibility through the crown.
* [STRING]    `crown_density_code_name`
  - A code indicating how dense the tree crown is, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC. Crown density is the amount of crown branches, foliage and reproductive structures that blocks light visibility through the crown.
* [INTEGER]   `crown_dieback_code`
  - A code indicating the amount of recent dead material in the upper and outer portion of the crown, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC.
* [STRING]    `crown_dieback_code_name`
  - A code indicating the amount of recent dead material in the upper and outer portion of the crown, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC.
* [INTEGER]   `foliage_transparency_code`
  - A code indicating the amount of light penetrating the foliated portion of the crown, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC.
* [STRING]    `foliage_transparency_code_name`
  - A code indicating the amount of light penetrating the foliated portion of the crown, estimated in percent classes. Collected for all live trees at least 5 inches DBH/DRC.
* [INTEGER]   `tree_history_code`
  - Identifies the tree with detailed information as to whether the tree is live, dead, cut, removed due to land use change, etc. Contact the appropriate FIA work unit for the definitions (table 1-1). Only collected by certain FIA work units (SURVEY.RSCD = 23, 24, or 33).
* [FLOAT]     `current_diameter_calculated`
  - If the diameter is unmeasurable (e.g., the tree is cut or dead), the diameter is calculated (in inches) and stored in this attribute.
* [INTEGER]   `breast_height_age`
  - The age of a live tree derived from counting tree rings from an increment core sample extracted at a height of 4.5 feet above ground. Breast height age is collected for a subset of trees and only for trees that the diameter is measured at breast height (DBH). This data item is used to calculate classification attributes such as stand age. For PNWRS, one tree is sampled for BHAGE for each species, within each crown class, and for each condition class present on a plot. Age of saplings (<5.0 inches DBH) may be aged by counting branch whorls above 4.5 feet. No timber hardwood species other than red alder are bored for age. For RMRS, one tree is sampled for each species and broad diameter class present on a plot. Only collected by certain FIA work units (SURVEY.RSCD = 22 or 26) and is left blank (null) when it is not collected.
* [INTEGER]   `total_age`
  - The age of a live tree derived either from counting tree rings from an increment core sample extracted at the base of a tree where diameter is measured at root collar (DRC), or for small saplings (1.0 to 2.9 inches DBH) by counting all branch whorls, or by adding a species-dependent number of years to breast height age. Total age is collected for a subset of trees and is used to calculate classification attributes such as stand age. Only collected by certain FIA work units (SURVEY.RSCD = 22 or 26) and is left blank (null) when it is not collected.
* [INTEGER]   `dead_cull`
  - The percent of the gross cubic-foot volume that is cull due to sound dead material. Recorded for all trees that are at least 5.0 inches in diameter. Only collected by certain FIA work units (SURVEY.RSCD = 22). This attribute is blank (null) for trees smaller than 5 inches and is always null for the other FIA work units.
* [INTEGER]   `form_cull`
  - The percent of the gross cubic-foot volume that is cull due to form defect. Recorded for live trees that are at least 5.0 inches DBH. Only collected by certain FIA work units (SURVEY.RSCD = 22). This attribute is blank (null) for dead trees, trees smaller than 5 inches DBH, for all trees where the diameter is measured at root collar (DRC), and is always null for the other FIA work units.
* [INTEGER]   `missing_top_cull_field_recorded`
  - The percent of the gross cubic-foot volume that is cull due to a missing (broken) merchantable top. Recorded for trees that are at least 5.0 inches in diameter. The volume estimate does not include any portion of the missing top that is <4.0 inches DOB (diameter outside bark). Many broken top trees may have 0 percent missing top cull because no merchantable volume was lost. Only collected by certain FIA work units (SURVEY.RSCD = 22). This attribute is blank (null) for trees smaller than 5 inches diameter and is always null for the other FIA work units.
* [INTEGER]   `boardfoot_cull`
  - The percent of the gross board-foot volume that is cull due to rot or form. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `cubicfoot_cull`
  - The percent of the gross cubic-foot volume that is cull due to rot or form. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `boardfootcull_soundness`
  - The percent of the board-foot cull that is sound (due to form). Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `cubicfootcull_soundness`
  - The percent of the cubic-foot cull that is sound (due to form). Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `sawlog_height`
  - The length (height) of a tree, recorded to a 7-inch top (9-inch for hardwoods), where at least one 8-foot log, merchantable or not, is present. On broken topped trees, sawlog length is recorded to the point of the break. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `bole_height`
  - The length between the 1-foot stump and the 4.0-inch top diameter of outside bark (DOB), where at least one 4-foot section is present. In periodic inventories, this attribute was measured in the field. For annual inventories, this attribute is a calculated, modeled value. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `form_class`
  - A code used in calculating merchantable bole net volume. Recorded for all live hardwood trees tallied that are 5.0 inch DBH/DRC. Also recorded for conifers 5.0 inch DBH in Region 5 National Forests. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `form_class_name`
  - A code used in calculating merchantable bole net volume. Recorded for all live hardwood trees tallied that are 5.0 inch DBH/DRC. Also recorded for conifers 5.0 inch DBH in Region 5 National Forests. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `current_height_calculated`
  - If the height is unmeasurable (e.g., the tree is cut or dead), the height is calculated (in feet) and stored in this attribute. Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [INTEGER]   `hardwood_clump_code`
  - A code sequentially assigned to each hardwood clump within each species as they are found on a subplot. Up to 9 hardwood clumps can be identified and coded within each species on each subplot. A clump is defined as having 3 or more live stems originating from a common point on the root system. Woodland hardwood species are not evaluated for clump code. Clump code data are used to adjust stocking estimates since trees growing in clumps contribute less to stocking than do individual trees. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `calculated_site_index`
  - Site index is calculated for dominant and co-dominant trees using one of several methods (see METHOD). It is expressed as height in feet that the tree is expected to attain at a base- or reference age (see SIBASE). Most commonly, site index is calculated using a family of curves that show site index as a function of total length and either breast-height age or total age. The height-intercept (or growth-intercept) method is commonly used for young trees or species that produce conspicuous annual branch whorls; using this method, site index is calculated with the height growth attained for a short period (usually 3 to 5 years) after the tree has reached breast height. Neither age nor total length determination are necessary when using the height-intercept method, so one or more of those variables may be null for a site tree on which the height-intercept method was used.
* [INTEGER]   `tree_created_by`
  - The employee who created the record. This attribute is intentionally left blank in download files.
* [DATE]      `tree_created_date`
  - The date the record was created.
* [INTEGER]   `tree_created_in_instance`
  - The database instance in which the record was created. Each computer system has a unique database instance code and this attribute stores that information to determine on which computer the record was created.
* [INTEGER]   `tree_modified_by`
  - The employee who modified the record. This field will be blank (null) if the data have not been modified since initial creation. This attribute is intentionally left blank in download files.
* [DATE]      `tree_modified_date`
  - The date the record was last modified. This field will be blank (null) if the data have not been modified since initial creation.
* [INTEGER]   `tree_modified_in_instance`
  - The database instance in which the record was modified. This field will be blank (null) if the data have not been modified since initial creation.
* [INTEGER]   `mortality_code`
  - Used for a tree that was alive within past 5 years, but has died. Not populated for standing dead trees <5.0 inches in diameter when PLOT.MANUAL <7.0.
* [STRING]    `mortality_code_name`
  - Used for a tree that was alive within past 5 years, but has died. Not populated for standing dead trees <5.0 inches in diameter when PLOT.MANUAL <7.0.
* [FLOAT]     `height_to_diameter_measurement_point`
  - For trees measured directly at 4.5 feet above ground, this item is blank (null). If the diameter is not measured at 4.5 feet, the actual length from the ground, to the nearest 0.1 foot, at which the diameter was measured for each tally tree, 1.0-inch DBH and larger.
* [INTEGER]   `rough_cull`
  - Percentage of sound dead cull, as a percent of the merchantable bole/portion of the tree.
* [INTEGER]   `mistletoe_class_code`
  - A rating of dwarf mistletoe infection. Recorded on all live conifer species except juniper. Using the Hawksworth (1979) six-class rating system, the live crown is divided into thirds, and each third is rated using the following scale: 0 is for no visible infection, 1 for <50 percent of branches infected, 2 for >50 percent of branches infected. The ratings for each third are summed together to yield the Hawksworth rating.
* [STRING]    `mistletoe_class_code_name`
  - A rating of dwarf mistletoe infection. Recorded on all live conifer species except juniper. Using the Hawksworth (1979) six-class rating system, the live crown is divided into thirds, and each third is rated using the following scale: 0 is for no visible infection, 1 for <50 percent of branches infected, 2 for >50 percent of branches infected. The ratings for each third are summed together to yield the Hawksworth rating.
* [INTEGER]   `rotten_missing_cull_field_recorded`
  - The percentage rotten or missing cubic-foot cull volume, estimated to the nearest 1 percent. This estimate does not include any cull estimate above actual length; therefore volume lost from a broken top is not included (see CULL for percent cull including cull from broken top). When field crews estimate volume loss (tree cull), they only consider the cull on the merchantable bole/portion of the tree, from a 1-foot stump to a 4-inch top diameter outside bark (DOB). For woodland species, the merchantable portion is between the point of DRC measurement to a 1.5-inch top DOB
* [INTEGER]   `reconcile_code`
  - Recorded for remeasurement locations only. A code indicating the reason a tree either enters or is no longer a part of the inventory.
* [STRING]    `reconcile_code_name`
  - Recorded for remeasurement locations only. A code indicating the reason a tree either enters or is no longer a part of the inventory.
* [FLOAT]     `previous_diameter`
  - The previous diameter (in inches) of the sample tree at the point of diameter measurement. Populated for remeasured trees.
* [FLOAT]     `net_annual_merchantable_cubicfoot_growth_growingstock_tree_forest_land`
  - The net change in merchantable cubic-foot volume (net cubicfoot volume) per year of the tree (for trees on remeasured plots, (V2 - V1)/(T2 - T1) where 1 and 2 denote the past and current measurement, respectively, V is volume, T indicates date of measurement, and T2 - T1 = PLOT.REMPER). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `net_annual_merchantable_boardfoot_growth_sawtimber_tree_forest_land`
  - The net change in merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume per year of the tree (for trees on remeasured plots, (V2 - V1)/(T2 - T1)). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `net_annual_sound_cubicfoot_growth_live_tree_forest_land`
  - The net change in sound cubic-foot volume (sound cubicfoot volume) per year of the tree (for trees on remeasured plots (V2 - V1)/(T2 -T1)). Because this value is net growth, it may be a negative number. Negative growth values are usually due to mortality (V2 = 0) but can also occur on live trees that have a net loss in volume because of damage, rot, broken top, or other causes. To expand to a per acre value, multiply by growth trees per acre unadjusted.
* [FLOAT]     `merchantable_cubicfoot_volume_growingstock_tree_forest_land_mortality_purposes`
  - The merchantable cubic-foot volume (Net cubic-foot volume at the midpoint) of the tree at the time of mortality. To obtain estimates of annual per acre mortality, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `merchantable_boardfoot_volume_sawtimber_tree_forest_land_mortality_purposes`
  - The merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume of the tree at time of mortality. To obtain estimates of annual per acre mortality, multiply by mortality trees per acre per year unadjusted.
* [FLOAT]     `sound_cubicfoot_volume_tree_forest_land_mortality_purposes`
  - The sound cubic-foot volume (sound cubicfoot volume) of the tree at the time of mortality. To obtain estimates of annual per acre mortality, multiply by mortality trees per acre per year unadjusted.
* [FLOAT]     `merchantable_cubicfoot_volume_growingstock_tree_forest_land_removal_purposes`
  - The merchantable cubic-foot volume of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `merchantable_boardfoot_volume_sawtimber_tree_forest_land_removal_purposes`
  - The merchantable board-foot (net boardfoot volume sawlog portion sawtimber tree, International ¼-inch rule) volume of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [FLOAT]     `sound_cubicfoot_volume_live_tree_forest_land_removal_purposes`
  - The sound cubic-foot volume (sound cubicfoot volume) of the tree at the time of removal. To obtain estimates of annual per acre removals, multiply by removal trees per acre per year unadjusted.
* [STRING]    `periodic_annual_growth_removal_mortality_flag`
  - A code indicating if this subplot is part of a periodic inventory (usually from a variable-radius plot design) that is only included for the purposes of computing growth, removals and/or mortality estimates. Tree data associated with this subplot does not contribute to current estimates of such attributes as volume, biomass or number of trees. The flag is set to Y for those subplots that are needed for estimation and otherwise is left blank (null).
* [INTEGER]   `tree_class_code_northeastern_research_station`
  - In annual inventory, this code represents a classification of the overall quality of a tree that is 5.0 inches DBH and larger. It classifies the quality of a sawtimber tree based on the present condition, or it classifies the quality of a poletimber tree as a prospective determination (i.e., a forecast of potential quality when and if the tree becomes sawtimber size). For more detailed description, see the regional field guide. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [STRING]    `tree_class_code_northeastern_research_station_name`
  - In annual inventory, this code represents a classification of the overall quality of a tree that is 5.0 inches DBH and larger. It classifies the quality of a sawtimber tree based on the present condition, or it classifies the quality of a poletimber tree as a prospective determination (i.e., a forecast of potential quality when and if the tree becomes sawtimber size). For more detailed description, see the regional field guide. Only collected by certain FIA work units (SURVEY.RSCD = 24).
* [INTEGER]   `tree_class_code_southern_research_station`
  - A code indicating the general quality of the tree. Prior to the merger of the Southern and Southeastern Research Stations (INVYR 1997), a growing-stock classification (code 2) was only assigned to species that were considered to have commercial value. Since the merger (INVYR >1997), code 2 has been applied to all tree species meeting the growing-stock form, grade, size and soundness requirements, regardless of commercial value. Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [STRING]    `tree_class_code_southern_research_station_name`
  - A code indicating the general quality of the tree. Prior to the merger of the Southern and Southeastern Research Stations (INVYR 1997), a growing-stock classification (code 2) was only assigned to species that were considered to have commercial value. Since the merger (INVYR >1997), code 2 has been applied to all tree species meeting the growing-stock form, grade, size and soundness requirements, regardless of commercial value. Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [INTEGER]   `tree_class_code_north_central_research_station`
  - In annual inventory, a code indicating tree suitability for timber products, or the extent of decay in the butt section of down-dead trees. It is recorded on live standing, standing-dead, and down dead trees that are 1.0 inches DBH and larger. Tree class is basically a check for the straightness and soundness of the sawlog portion on a sawtimber tree or the potential sawlog portion on a poletimber tree or sapling. "Sawlog portion" is defined as the length between the 1-foot stump and the 9.0-inch top diameter of outside bark, DOB, for hardwoods, or the 7.0-inch top DOB for softwoods. For more detailed description, see the regional field guide located at the NRS Data Collection web page (http://www.nrs.fs.fed.us/fia/data-collection/). Only collected by certain FIA work units (SURVEY.RSCD = 23).
* [STRING]    `tree_class_code_north_central_research_station_name`
  - In annual inventory, a code indicating tree suitability for timber products, or the extent of decay in the butt section of down-dead trees. It is recorded on live standing, standing-dead, and down dead trees that are 1.0 inches DBH and larger. Tree class is basically a check for the straightness and soundness of the sawlog portion on a sawtimber tree or the potential sawlog portion on a poletimber tree or sapling. "Sawlog portion" is defined as the length between the 1-foot stump and the 9.0-inch top diameter of outside bark, DOB, for hardwoods, or the 7.0-inch top DOB for softwoods. For more detailed description, see the regional field guide located at the NRS Data Collection web page (http://www.nrs.fs.fed.us/fia/data-collection/). Only collected by certain FIA work units (SURVEY.RSCD = 23).
* [INTEGER]   `tree_class_code_rocky_mountain_research_station`
  - A code indicating the general quality of the tree. Only collected by certain FIA work units (SURVEY.RSCD = 22).
* [STRING]    `tree_class_code_rocky_mountain_research_station_name`
  - A code indicating the general quality of the tree. Only collected by certain FIA work units (SURVEY.RSCD = 22).
* [INTEGER]   `standing_dead_code`
  - A code indicating if a tree qualifies as standing dead. To qualify as a standing dead tally tree, the dead tree must be at least 1.0 inch in diameter, have a bole that has an unbroken actual length of at least 4.5 feet, and lean less than 45 degrees from vertical as measured from the base of the tree to 4.5 feet. Populated where PLOT.MANUAL 2.0; may be populated using information collected on dead trees in earlier inventories for dead trees. For woodland species with multiple stems, a tree is considered down if more than 2/3 of the volume is no longer attached or upright; cut and removed volume is not considered. For woodland species with single stems to qualify as a standing dead tally tree, dead trees must be at least 1.0 inch in diameter, be at least 1.0 foot in unbroken ACTUAL LENGTH, and lean less than 45 degrees from vertical.
* [STRING]    `standing_dead_code_name`
  - A code indicating if a tree qualifies as standing dead. To qualify as a standing dead tally tree, the dead tree must be at least 1.0 inch in diameter, have a bole that has an unbroken actual length of at least 4.5 feet, and lean less than 45 degrees from vertical as measured from the base of the tree to 4.5 feet. Populated where PLOT.MANUAL 2.0; may be populated using information collected on dead trees in earlier inventories for dead trees. For woodland species with multiple stems, a tree is considered down if more than 2/3 of the volume is no longer attached or upright; cut and removed volume is not considered. For woodland species with single stems to qualify as a standing dead tally tree, dead trees must be at least 1.0 inch in diameter, be at least 1.0 foot in unbroken ACTUAL LENGTH, and lean less than 45 degrees from vertical.
* [INTEGER]   `previous_tree_status_code`
  - Tree status that was recorded at the previous inventory on all tally trees 1.0 inch in diameter.
* [STRING]    `previous_tree_status_code_name`
  - Tree status that was recorded at the previous inventory on all tally trees 1.0 inch in diameter.
* [STRING]    `previous_woodland_stem_count`
  - Woodland tree species stem count that was recorded at the previous inventory.
* [FLOAT]     `trees_per_acre_unadjusted`
  - The number of seedlings per acre that the seedling count theoretically represents based on the sample design. For fixed-radius plots taken with the mapped plot design (PLOT.DESIGNCD =1), TPA_UNADJ equals 74.965282 times the number of seedlings counted. For plots taken with other sample designs, this attribute may be blank (null). Based on the procedures described in Bechtold and Patterson (2005), this attribute can be adjusted using factors stored in the POP_STRATUM table to derive population estimates. Examples of estimating population totals are shown in The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017).
* [FLOAT]     `mortality_trees_per_acre_per_year_unadjusted`
  - The number of mortality trees per acre per year that the sample tree theoretically represents based on the sample design. For fixed-radius plots taken with the mapped plot design (PLOT.DESIGNCD =1), TPAMORT_UNADJ is set to a constant derived from the plot size divided by PLOT.REMPER. Variable-radius plots were often used in earlier inventories, so the value in TPAMORT_UNADJ decreases as the tree diameter increases. This attribute will be blank (null) if the tree does not contribute to mortality estimates. Based on the procedures described in Bechtold and Patterson (2005), this attribute must be adjusted using factors stored in the POP_STRATUM table to derive population estimates. Examples of estimating population totals are shown in The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017).
* [FLOAT]     `removal_trees_per_acre_per_year_unadjusted`
  - The number of removal trees per acre per year that the sample tree theoretically represents based on the sample design. Forfixed-radius plots taken with the mapped plot design (PLOT.DESIGNCD =1), Removal trees per acre per year unadjusted is set to a constant derived from the plot size divided by PLOT.REMPER. Variable-radius plots were often used in earlier inventories, so the value in removal trees per acre per year unadjusted decreases as the tree diameter increases. This attribute will be blank(null) if the tree does not contribute to removals estimates. Based on the procedures described in Bechtold and Patterson (2005), this attribute must be adjusted using factors stored in the Population Stratum Table table to derive population estimates. Examples of estimating population totals are shown in The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017).
* [FLOAT]     `growth_trees_per_acre_unadjusted`
  - The number of growth trees per acre that the sample tree theoretically represents based on the sample design. For fixed-radius plots taken with the mapped plot design (PLOT.DESIGNCD = 1), Growth trees per acre unadjusted is set to a constant derived from the plot size. Variable-radius plots were often used in earlier inventories, so the value in Growth trees per acre unadjusted decreases as the tree diameter increases. This attribute will be blank (null) if the tree does not contribute to growth estimates. Based on the procedures described in Bechtold and Patterson (2005), this attribute must be adjusted using factors stored in the Population Stratum Table table to derive population estimates. Examples of estimating population totals are shown in The Forest Inventory and Analysis Database: Population Estimation User Guide (Edition: March, 2017).
* [FLOAT]     `dry_biomass_in_the_merchantable_bole`
  - The oven-dry biomass (pounds) in the merchantable bole of timber species [trees where diameter is measured at breast height (DBH)] 5.0 inches in diameter. This is the biomass of sound wood in live and dead trees, including bark, from a 1-foot stump to a minimum 4-inch top diameter of the central stem. This is a per tree value and must be multiplied by Trees per acre unadjusted to obtain per acre information. This attribute is blank (null) for timber species with DIA <5.0 inches and for woodland species. See Aboveground dry biomass woodland tree species for biomass of woodland species and Aboveground dry biomass of saplings for biomass of timber species with DIA <5.0 inches. For dead or cut timber trees, this number represents the biomass at the time of death or last measurement. Dry biomass in the merchantable bole is based on Sound cubic-foot volume at the midpoint and specific gravity information derived by the Forest Products Lab and others (values stored in the Reference Species table).
* [FLOAT]     `dry_biomass_top_limbs_tree`
  - The oven-dry biomass (pounds) in the top and branches (combined) of timber species [trees where diameter is measured at breast height (DBH)] 5.0 inches in diameter. Dry biomass top limbs tree includes the tip, the portion of the stem above the merchantable bole (i.e., above the 4-inch top diameter), and all branches; excludes foliage. Estimated for live and dead trees. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the Tree Net Growth, Removal, and Mortality Component Table  table to obtain per acre information. For dead or cut trees, this number represents the biomass at the time of death or last measurement. This attribute is blank for timber species with DIA <5.0 inches and for woodland species. See aboveground dry biomass woodland tree species for biomass of woodland species, and aboveground dry biomass saplings for biomass of timber species with DIA <5.0 inches. Appendix M contains equations used to estimate biomass components in the FIADB.
* [FLOAT]     `dry_biomass_tree_stump_at_T_1`
  - The oven-dry biomass (pounds) in the top and branches (combined) of timber species [trees where diameter is measured at breast height (DBH)] 5.0 inches in diameter. Dry biomass top limbs tree includes the tip, the portion of the stem above the merchantable bole (i.e., above the 4-inch top diameter), and all branches; excludes foliage. Estimated for live and dead trees. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the Tree Net Growth, Removal, and Mortality Component Table  table to obtain per acre information. For dead or cut trees, this number represents the biomass at the time of death or last measurement. This attribute is blank for timber species with DIA <5.0 inches and for woodland species. See aboveground dry biomass woodland tree species for biomass of woodland species, and aboveground dry biomass saplings for biomass of timber species with DIA <5.0 inches. Appendix M contains equations used to estimate biomass components in the FIADB.
* [FLOAT]     `aboveground_dry_biomass_saplings`
  - The oven-dry biomass (pounds) of the aboveground portion, excluding foliage, of live trees with a diameter from 1.0 to 4.9 inches. Calculated for timber species only. The biomass of saplings is based on biomass computed from Jenkins and others (2003), using the observed diameter and an adjustment factor. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the TREE_GRM_COMPONENT table to obtain per acre information. Appendix M contains equations used to estimate biomass components in the FIADB.
* [FLOAT]     `aboveground_dry_biomass_woodland_tree_species`
  - The oven-dry biomass (pounds) of the aboveground portion of a live or dead tree, excluding foliage, the tree tip Tree Net Growth, Removal, and Mortality Begin Table Chapter 3 (revision: 03.2017) 3-94 FIA Database Description and User Guide for Phase 2 (version: 7.0) (top of the tree above 1½ inches in diameter), and a portion of the stump from ground to diameter at root collar (DRC). Calculated for woodland species (trees where diameter is measured at DRC) with a diameter 1.0 inch. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the TREE_GRM_COMPONENT table to obtain per acre information. This attribute is blank (null) for woodland species with DIA <1.0 inch and for all timber species. Appendix M contains equations used to estimate biomass components in the FIADB.
* [FLOAT]     `belowground_dry_biomass`
  - The oven-dry biomass (pounds) of the aboveground portion of a tree. This is a modeled estimate, calculated on live trees with a diameter of 1.0 inch, for both timber and woodland species. This is a per tree value and must be multiplied by the appropriate trees per acre expansion factor found in the TREE_GRM_COMPONENT table to obtain per acre information. Appendix M contains equations used to estimate biomass components in the FIADB.
* [FLOAT]     `aboveground_carbon`
  - The carbon (pounds) in the aboveground portion, excluding foliage, of live trees with a diameter 1.0 inch, and dead trees with a diameter 5.0 inches. Calculated for both timber and woodland species. This is a per tree value and must be multiplied by TPA_UNADJ to obtain per acre information. Carbon is assumed to be one-half the value of biomass and is derived by summing the aboveground biomass estimates and multiplying by 0.5 as follows: CARBON_AG = 0.5 * (DRYBIO_BOLE + DRYBIO_STUMP + DRYBIO_TOP + DRYBIO_SAPLING + DRYBIO_WDLD_SPP)
* [FLOAT]     `belowground_carbon`
  - The carbon (pounds) of coarse roots >0.1 inch in root diameter. Calculated for live trees with a diameter 1.0 inch, and dead trees with a diameter 5.0 inches, for both timber and woodland species. This is a per tree value and must be multiplied by TPA_UNADJ to obtain per acre information. Carbon is assumed to be one-half the value of belowground biomass as follows: Belowground carbon = 0.5 * Belowground dry biomass
* [INTEGER]   `tree_inventory_cycle_number`
  - A number assigned to a set of plots, measured over a particular period of time from which a State estimate using all possible plots is obtained. A cycle number >1 does not necessarily mean that information for previous cycles resides in the database. A cycle is relevant for periodic and annual inventories.
* [INTEGER]   `tree_inventory_subcycle_number`
  - For an annual inventory that takes n years to measure all plots, subcycle shows in which of the n years of the cycle the data were measured. Subcycle is 0 for a periodic inventory. Subcycle 99 may be used for plots that are not included in the estimation process.
* [INTEGER]   `tree_bored_code_pacific_northwest_research_station`
  - Used in conjunction with tree age (BHAGE and TOTAGE). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `tree_bored_code_pacific_northwest_research_station_name`
  - Used in conjunction with tree age (BHAGE and TOTAGE). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_location_1_pacific_northwest_research_station`
  - The location on the tree where Damage Agent 1 is found. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `damage_location_1_pacific_northwest_research_station_name`
  - The location on the tree where Damage Agent 1 is found. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_location_2_pacific_northwest_research_station`
  - The location on the tree where Damage Agent 1 is found. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `damage_location_2_pacific_northwest_research_station_name`
  - The location on the tree where Damage Agent 1 is found. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `diameter_check_pacific_northwest_research_station`
  - A separate estimate of the diameter without the obstruction if the diameter was estimated because of moss/vine/obstruction, etc. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `diameter_check_pacific_northwest_research_station_name`
  - A separate estimate of the diameter without the obstruction if the diameter was estimated because of moss/vine/obstruction, etc. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_agent_1_pacific_northwest_research_station`
  - Primary damage agent code in PNW. Up to three damaging agents can be coded in PNW as Damage agent 1, Pacific Northwest Research Station, Damage agent 2, Pacific Northwest Research Station, and Damage agent 3, Pacific Northwest Research Station. A 2-digit code (with values from 01 to 99) indicating the tree damaging agent that is considered to be of greatest importance to predict tree growth, survival, and forest composition and structure. Additionally, there are two classes of damaging agents. Class I damage agents are considered more important than class II agents and are thus coded as a primary agent before the class II agents. For more information, see appendix K. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_agent_2_pacific_northwest_research_station`
  - Primary damage agent code in PNW. Up to three damaging agents can be coded in PNW as Damage agent 1, Pacific Northwest Research Station, Damage agent 2, Pacific Northwest Research Station, and Damage agent 3, Pacific Northwest Research Station. A 2-digit code (with values from 01 to 99) indicating the tree damaging agent that is considered to be of greatest importance to predict tree growth, survival, and forest composition and structure. Additionally, there are two classes of damaging agents. Class I damage agents are considered more important than class II agents and are thus coded as a primary agent before the class II agents. For more information, see appendix K. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_agent_3_pacific_northwest_research_station`
  - Primary damage agent code in PNW. Up to three damaging agents can be coded in PNW as Damage agent 1, Pacific Northwest Research Station, Damage agent 2, Pacific Northwest Research Station, and Damage agent 3, Pacific Northwest Research Station. A 2-digit code (with values from 01 to 99) indicating the tree damaging agent that is considered to be of greatest importance to predict tree growth, survival, and forest composition and structure. Additionally, there are two classes of damaging agents. Class I damage agents are considered more important than class II agents and are thus coded as a primary agent before the class II agents. For more information, see appendix K. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `leafy_mistletoe_class_code_pacific_northwest_research_station`
  - All juniper species, incense cedars, white fir (CA only) and oak trees are rated for leafy mistletoe infection. This item is used to describe the extent and severity of leafy mistletoe infection (see MIST_CL_CD for dwarf mistletoe information). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `leafy_mistletoe_class_code_pacific_northwest_research_station_name`
  - All juniper species, incense cedars, white fir (CA only) and oak trees are rated for leafy mistletoe infection. This item is used to describe the extent and severity of leafy mistletoe infection (see MIST_CL_CD for dwarf mistletoe information). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_1_pacific_northwest_research_station_years_2001_2004`
  - Damage severity depends on the damage agent coded (see appendix K for codes). This is a 2-digit code that indicates either percent of location damaged (01-99), or the appropriate class of damage (values vary from 0-9 depending on the specific Damage Agent). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_1_a_pacific_northwest_research_station`
  - Damage severity depends on the damage agent coded (see appendix K for codes). This is a 2-digit code indicating either percent of location damaged (01-99), or the appropriate class of damage (values vary from 0-4 depending on the specific Damage Agent). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_1_b_pacific_northwest_research_station`
  - Damage severity B is only coded when the Damage Agent is white pine blister rust (36). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `damage_severity_1_b_pacific_northwest_research_station_name`
  - Damage severity B is only coded when the Damage Agent is white pine blister rust (36). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_2_pacific_northwest_research_station_years_2001_2004`
  - Damage severity depends on the damage agent coded (see appendix K for codes). This is a 2-digit code indicating either percent of location damaged (01-99), or the appropriate class of damage (values vary from 0-9 depending on the specific Damage Agent). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_2_a_pacific_northwest_research_station_starting_2005`
  - Damage severity depends on the damage agent coded (see appendix K for codes). This is a 2-digit code indicating either percent of location damaged (01-99), or the appropriate class of damage (values vary from 0-4 depending on the specific Damage Agent). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `damage_severity_2_b_pacific_northwest_research_station_starting_2005`
  - Damage severity B is only coded when the Damage Agent is white pine blister rust (36). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `damage_severity_3_pacific_northwest_research_station_years_2001_2004`
  - Damage severity depends on the damage agent coded (see appendix K for codes). This is a 2-digit code indicating either percent of location damaged (01-99), or the appropriate class of damage (values vary from 0-9 depending on the specific Damage Agent). Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `unknown_damage_type_1_pacific_northwest_research_station`
  - A code indicating the sign or symptom recorded when UNKNOWN damage code 90 is used. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `unknown_damage_type_1_pacific_northwest_research_station_name`
  - A code indicating the sign or symptom recorded when UNKNOWN damage code 90 is used. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `unknown_damage_type_2_pacific_northwest_research_station`
  - A code indicating the sign or symptom recorded when UNKNOWN damage code 90 is used. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [STRING]    `unknown_damage_type_2_pacific_northwest_research_station_name`
  - A code indicating the sign or symptom recorded when UNKNOWN damage code 90 is used. Only collected by certain FIA work units (SURVEY.RSCD = 26).
* [INTEGER]   `previous_periodic_prism_point_tree_number_southern_research_station`
  - In some older Southeast Experiment Station states, the prism point, tree number (PNTN) of the current cycle did not match the previous cycle's prism point, tree number. Previous periodic prism point tree number southern research station is used to join the current and the previous prism plot trees.
* [INTEGER]   `disease_southern_research_station`
  - A code indicating the incidence of fusiform, commandra rust or dieback. Dieback is only recorded for live hardwood trees where DIA 5.0 inches with at least 10 percent dieback. Fusiform and comandra rust are only recorded for live pine trees 5.0 inches with the following species codes: 110, 111, 121, 126, 128, or 131. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.6 - 5.1). Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [STRING]    `disease_southern_research_station_name`
  - A code indicating the incidence of fusiform, commandra rust or dieback. Dieback is only recorded for live hardwood trees where DIA 5.0 inches with at least 10 percent dieback. Fusiform and comandra rust are only recorded for live pine trees 5.0 inches with the following species codes: 110, 111, 121, 126, 128, or 131. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.6 - 5.1). Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [INTEGER]   `dieback_severity_southern_research_station`
  - A code indicating the severity of hardwood crown dieback. Populated when Disease southern research station = 2. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.6 - 5.1). Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [STRING]    `dieback_severity_southern_research_station_name`
  - A code indicating the severity of hardwood crown dieback. Populated when Disease southern research station = 2. Populated for all forested plots using the National Field Guide protocols (MANUAL 1.6 - 5.1). Only collected by certain FIA work units (SURVEY.RSCD = 33).
* [INTEGER]   `damage_agent_code_1`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [STRING]    `damage_agent_code_1_name`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [STRING]    `damage_agent_code_2`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [STRING]    `damage_agent_code_2_name`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [INTEGER]   `damage_agent_code_3`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [STRING]    `damage_agent_code_3_name`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [FLOAT]     `centroid_diameter`
  - The outside bark diameter (in inches) measured at CENTROID_DIA_HT_ACTUAL. For tree ferns, diameter is measured where the fronds emerge from the trunk. Only collected by certain FIA work units (SURVEY.RSCD = 26) for the Pacific Islands. This diameter is part of a new upper stem diameter protocol that began with remeasurement, except for Hawaii where the protocol was implemented in the first measurement.
* [FLOAT]     `calculated_centroid_diameter_height`
  - The height (in feet) to stem centroid. The stem centroid is located at 30 percent of the TOTAL LENGTH of the stem. Only collected by certain FIA work units (SURVEY.RSCD = 26) for the Pacific Islands. This height is part of a new upper stem diameter protocol that began with the first remeasurement, except for Hawaii where the protocol was implemented in the first measurement.
* [FLOAT]     `actual_centroid_diameter_height`
  - The height (in feet) to where stem centroid diameter was actually measured. It may differ from CENTROID_DIA_HT if abnormalities in the stem prevented a normal diameter measurement. Only collected by certain FIA work units (SURVEY.RSCD = 26) for the Pacific Islands. This height is part of a new upper stem diameter protocol that began with the first remeasurement, except for Hawaii where the protocol was implemented in the first measurement.
* [INTEGER]   `upper_stem_diameter`
  - The outside bark upper stem diameter (in inches), measured at least 3 feet above the point where the DIA was taken. For larger trees, UPPER_DIA was recorded at the point where the main stem was at least 4.0 inches in diameter. This diameter is used in the calculation of stem taper, needed to improve the estimation of stem volume. Only collected by certain FIA work units (SURVEY.RSCD = 26) for the Pacific Islands. This is the legacy upper stem diameter protocol and will not be collected after the first remeasurement.
* [INTEGER]   `upper_stem_diameter_height`
  - The height (in feet) to where upper stem diameter (UPPER_DIA) was measured. Only collected by certain FIA work units (SURVEY.RSCD = 26) for the Pacific Islands. This is the legacy upper stem diameter protocol and will not be collected after the first remeasurement.
* [FLOAT]     `sound_cubicfoot_volume_sawlog_portion`
  - The sound volume of wood in the central stem of a timber species tree of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches minimum DIA for hardwoods), from a 1-foot stump to a minimum top diameter (7.0 inches for softwoods, 9.0 inches for hardwoods) or to where the central stem breaks into limbs, all of which are less than the minimum top diameter. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per acre information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). All larger trees have entries in this field if they are growing-stock trees (tree class code = 2 and tree status code = 1). All rough and rotten trees (tree class code = 3 or 4) and dead and cut trees (tree status code = 2 or 3) are blank (null) in this field. Does not include rotten and missing cull (volume loss due to rotten and missing cull defect has been deducted).
* [FLOAT]     `dry_biomass_sawlog_portion_sawtimber_tree`
  - The oven-dry biomass (pounds) in the sawlog portion of timber species trees of sawtimber size (9.0 inches DIA minimum for softwoods, 11.0 inches minimum DIA for hardwoods), from a 1-foot stump to a minimum top diameter (7.0 inches for softwoods, 9.0 inches for hardwoods) or to where the central stem breaks into limbs, all of which are less than the minimum top diameter. This is a per tree value and must be multiplied by trees per acre unadjusted to obtain per acre information. This attribute is blank (null) for softwood trees with DIA <9.0 inches (11.0 inches for hardwoods). For dead or cut timber trees, this number represents the biomass at the time of death or last measurement. Dry biomass sawlog portion sawtimber tree is based on sound cubicfoot volume sawlog portion and specific gravity information derived by the Forest Products Lab and others (values stored in the Reference Species table).
* [INTEGER]   `damage_agent_code_1_southern_research_station`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [INTEGER]   `damage_agent_code_2_southern_research_station`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [STRING]    `damage_agent_code_3_southern_research_station`
  - A code indicating the first damage agent observed when inspecting the tree from bottom to top (roots, bole, branches, foliage). If more than one agent is observed, the most threatening one is listed first where agents threatening survival are listed first and agents threatening wood quality second. Up to three damage agents can be recorded, from most important to least important (Damage agent code 1, Damage agent code 2 and Damage agent code 3). The codes used for damage agents come from the January 2012 Pest Trend Impact Plot System (PTIPS) list from the Forest Health Technology Enterprise Team (FHTET) that has been modified to meet FIA's needs. The list is modified by each region to meet the specific needs of that region. The general agent codes are listed here. See appendix J for the complete list of codes.
* [FLOAT]     `aboveground_dry_biomass`
  - The oven-dry biomass (pounds) in the aboveground portion, excluding foliage, of live trees with a diameter 1 inch, and dead trees with a diameter 5 inches. Calculated for both timber and woodland species. This is a per tree value and must be multiplied by TPA_UNADJ to obtain per acre information. Appendix M contains equations used to estimate biomass components in the FIADB. DRYBIO_AG = (DRYBIO_BOLE + DRYBIO_STUMP + DRYBIO_TOP + DRYBIO_SAPLING + DRYBIO_WDLD_SPP)
* [STRING]    `unique_tree`
  - It is a unique identifier with the combination of plot sequence number, subplot number & tree record number.
* [STRING]    `actualht_calc`
* [STRING]    `actualht_calc_code`
* [STRING]    `cull_bf_rotten`
* [STRING]    `cull_bf_rotten_code`
* [STRING]    `cull_bf_rough`
* [STRING]    `cull_bf_rough_code`
* [STRING]    `prevdia_fld`
* [STRING]    `treecl_code_31_ncrs`
* [STRING]    `tree_grade_ncrs`
* [STRING]    `boughs_available_ncrs`
* [STRING]    `boughs_hrvst_ncrs`
* [STRING]    `treecl_code_31_ners`
* [STRING]    `agent_code_ners`
* [STRING]    `bfsnd_code_ners`
* [STRING]    `agechk_code_rmrs`
* [STRING]    `dia_1yrago_rmrs`
* [STRING]    `growbfscr_rmrs`
* [STRING]    `growcfsawlog_rmrs`
* [STRING]    `ht_1yrago_rmrs`
* [STRING]    `prev_actualht_rmrs`
* [STRING]    `prev_agechk_code_rmrs`
* [STRING]    `prev_bhage_rmrs`
* [STRING]    `prev_ht_rmrs`
* [STRING]    `prev_totage_rmrs`
* [STRING]    `prev_treecl_code_rmrs`
* [STRING]    `radage_code_rmrs`
* [STRING]    `radgrw_rmrs`
* [STRING]    `volbfscrgrs_rmrs`
* [STRING]    `volbfscrnet_rmrs`
* [STRING]    `volcfdeadgrs_rmrs`
* [STRING]    `volcfsawgrs_rmrs`
* [STRING]    `volcfsawnet_rmrs`
* [STRING]    `volcftotnet_rmrs`
* [STRING]    `volcfuppgrs_rmrs`
* [STRING]    `volcfuppnet_rmrs`
* [STRING]    `sapling_fusiform_srs`
* [STRING]    `epiphyte_pnwrs`
* [STRING]    `root_ht_pnwrs`
* [STRING]    `cavity_use_pnwrs`
* [STRING]    `core_length_pnwrs`
* [STRING]    `culturally_killed_pnwrs`
* [STRING]    `dia_est_pnwrs`
* [STRING]    `gst_pnwrs`
* [STRING]    `inc10yr_pnwrs`
* [STRING]    `inc5yrht_pnwrs`
* [STRING]    `inc5yr_pnwrs`
* [STRING]    `ring_count_inner_2inches_pnwrs`
* [STRING]    `ring_count_pnwrs`
* [STRING]    `snag_dis_code_pnwrs`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
