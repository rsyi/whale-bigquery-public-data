# `sdoh_hrsa_shortage_areas.hpsa_dental_health`
`bq-1` | `bigquery-public-data`
Metadata on the table is available here: https://data.hrsa.gov//DataDownload/DD_Files/HPSA_DATAMART_METADATA.XLSX

## Column details
* [STRING]    `Source_ID`
  - Primary identifier for a Health Professional Shortage Area (HPSA) as a complete unit in the source data system.
* [STRING]    `Source_Name`
  - The name of the Health Professional Shortage Area (HPSA). This data element comes directly from the source system in the most recent data refresh. For further information about HPSA refer to the http://www.hrsa.gov/shortage/ website.
* [STRING]    `Status_Code`
  - One character identifier that designates the current status of the HPSA designation. For further information about Health Professional Shortage Areas (HPSA) refer to the http://www.hrsa.gov/shortage/ website.
* [STRING]    `Status_Description`
  - Textual description of the current status of the Health Professional Shortage Area (HPSA) designation.
* [STRING]    `Type_Code`
  - Geography or facility type code characterizing the Health Professional Shortage Area (HPSA).
* [STRING]    `Type_Desc`
  - Textual description of the Health Professional Shortage Area (HPSA) type.
* [STRING]    `Address`
  - Standardized version of the street address of a Health Professional Shortage Area (HPSA) facility.
* [STRING]    `City`
  - Standardized version of the city name in which a Health Professional Shortage Areas (HPSA) facility is located.
* [STRING]    `State_Abbr`
  - U.S. Postal Service (USPS) code for the state in which the Health Professional Shortage Area (HPSA) entity is located.
* [STRING]    `Postal_Code`
  - Health Professional Shortage Area (HPSA) U.S. Postal Service (USPS) Zoning Improvement Plan (ZIP) Code. In the context of HPSA data, this field only applies to facilities.
* [STRING]    `Degree_of_Shortage`
  - Degree of practitioner shortage for the Health Professional Shortage Area (HPSA) based on population to provider ratio.
* [DATE]      `Designation_Date`
  - Date on which the Health Professional Shortage Area (HPSA) was originally designated as a shortage area.
* [DATE]      `Designation_Last_Update_Date`
  - Date on which the Health Professional Shortage Area (HPSA) information was last updated in the source system.
* [INTEGER]   `Designation_Pop`
  - Number of persons which have been identified by the HRSA, Bureau of Health Workforce (BHW), Division of Policy and Shortage Designation (DPSD) as being affected by the Health Professional Shortage Area (HPSA).
* [INTEGER]   `Estimated_Underserved_Pop`
  - Estimated underserved population served by the full-time equivalent (FTE) health care practitioners within a Health Professional Shortage Area (HPSA).
* [INTEGER]   `Estimated_Served_Pop`
  - Estimated total population served by the full-time equivalent (FTE) Health care practitioners within a Health Professional Shortage Area (HPSA).
* [STRING]    `Formal_Ratio`
  - Ratio of the Health Professional Shortage Area (HPSA) Designation Population to HPSA provider full-time equivalents displayed in ratio format (for example, 3500:1), where the population and the designation share the same discipline class (for example, Primary Care, Dental Care, and Mental Health).
* [FLOAT]     `Total_FTE_Clinicians`
  - Number of practitioners providing ambulatory patient care in the Health Professional Shortage Area (HPSA) expressed as full-time equivalents.
* [STRING]    `Metropolitan_Indicator_Code`
  - Single character indicating whether a Health Professional Shortage Area (HPSA) is considered to be in a metropolitan, non-metropolitan, or frontier area.
* [STRING]    `Metropolitan_Indicator_Desc`
  - Description indicating whether a Health Professional Shortage Area (HPSA) is either Metropolitan, Non-Metropolitan, or Frontier in nature.
* [STRING]    `Provider_Ratio_Goal`
  - Health Professional Shortage Area (HPSA) Provider Ratio Goal that is the target population per provider (physician) for the HPSA in a Discipline Class. Federal regulations stipulate that, in order to be considered as having a shortage of providers, an area must have a population-to-provider ratio of a certain threshold. For primary medical care, the population to provider ratio must be at least 3,500 to 1 (3,000 to 1 if there are unusually high needs in the community). For dental, the ratio must be at least 5,000 to 1 (4,000 to 1 in high-need communities). For mental health, the area must have a population to psychiatrist ratio of 30,000 to 1 (20,000 to 1 in high-need communities). For further information about Health Professional Shortage Areas (HPSA) refer to the http://www.hrsa.gov/shortage/ website.
* [FLOAT]     `Percent_Pop_Below_Poverty`
  - Percent of the population in the Health Professional Shortage Area (HPSA) living below the U.S. Federal Poverty Level (USFPL).
* [INTEGER]   `HPSA_Score`
  - Health Professional Shortage Area (HPSA) Score developed by the National Health Service Corps (NHSC) in determining priorities for assignment of clinicians. The scores range from 0 to 26 where the higher the score, the greater the priority.
* [FLOAT]     `HPSA_Shortage`
  - Number of full-time equivalent (FTE) practitioners needed in the Health Professional Shortage Area (HPSA) so that it will achieve the population to practitioner target ratio. The target ratio is determined by the type (discipline) of the HPSA.
* [INTEGER]   `Discipline_Class_Num`
  - Single character code used by the HRSA Data Warehouse (HDW) to indicate the Discipline Class identification number (ID) values associated with health related discipline classes.
* [STRING]    `Discipline_Class_Desc`
  - Health Professional Shortage Area (HPSA) discipline class description. HPSA disciplines may be listed as Primary Care, Dental Health, or Mental Health.
* [STRING]    `Component_Source_ID`
  - Identification number linking a Health Professional Shortage Area (HPSA) component to its "parent" HPSA.
* [STRING]    `Component_Source_Name`
  - Name assigned to the Health Professional Shortage Area (HPSA) component as identified in the most recent data refresh.
* [STRING]    `Component_Status_Code`
  - One-character code that indicates the designation status for the component part of the Health Professional Shortage Areas (HPSA).
* [STRING]    `Component_Status_Desc`
  - Health Professional Shortage Area (HPSA) Component Status Description which is the English-language expansion of the HPSA Component Status Code. This text description identifies the current status of the HPSA component and is subject to change during the life span of the HPSA.
* [STRING]    `Component_Type_Code`
  - Geography or facility type code which characterizes the Health Professional Shortage Area (HPSA) component.
* [STRING]    `Component_Type_Desc`
  - Health Professional Shortage Area (HPSA) Component Type Description which identifies in words the type of the HPSA for the component.
* [STRING]    `Component_State_Abbr`
  - U.S. Postal Service (USPS) two alphabetic character code for a U.S. state or U.S. territory that is associated with the county or county equivalent in which the Health Professional Shortage Area (HPSA) component is located.
* [STRING]    `Component_Postal_Code`
  - U.S. Postal Service Zone Improvement Plan (ZIP) associated with a Health Professional Shortage Area (HPSA) Component.
* [DATE]      `Component_Designation_Date`
  - Date when the HPSA was designated as a shortage area as represented in the most recent data refresh from the source data. For further information about Health Professional Shortage Areas (HPSA) refer to the http://www.hrsa.gov/shortage/ website.
* [STRING]    `Component_Designation_Date_String`
  - Date when the Health Professional Shortage Area (HPSA) was designated as a shortage area as represented in the most recent data-refresh from the source data and stored as a text string.
* [DATE]      `Component_Designation_Last_Update_Date`
  - Date when the HPSA component was last updated, as represented in the most recent HPSA source data refresh. For further information about Health Professional Shortage Areas (HPSA) refer to the http://www.hrsa.gov/shortage/ website.
* [STRING]    `Geography_ID`
  - Health Professional Shortage Area (HPSA) geography code which identifies the specific geographic area (county, minor civil division (MCD), or Census Tract) associated with the HPSA.
* [INTEGER]   `CountyFIPS`
  - Numeric character string assigned by the National Institute of Standards and Technology to the counties and/or county equivalents for the states, the District of Columbia, and U.S. territories.
* [STRING]    `County_Name`
  - Name of the county or county equivalent in which the associated address is located, displayed as a text string.
* [STRING]    `StateCountyFIPS`
  - Concatenation (combination) of the Federal Information Processing Standard (FIPS) state and county codes.
* [STRING]    `State_FIPS`
  - State Federal Information Processing Standard (FIPS) code identifying the two numeric character string assigned by the National Institute of Standards and Technology (NIST) to states, the District of Columbia, and U.S. territories.
* [STRING]    `State_Abbr_2`
  - U.S. Postal Service (USPS) two alphabetic character code for a U.S. state or U.S. territory associated with a location where an entity is situated.
* [STRING]    `State_Name`
  - State or territory name.
* [STRING]    `Primary_State_Name`
  - Formal, official U.S. state or U.S. territory name associated with the location or address for the entity (record). With respect to a Health Professional Shortage Area (HPSA) or a Medically Underserved Area/Population (MUA/P), the physical land area associated with the entity may cross state boundaries, which means a HPSA or MUA/P may consist of components or parts from one or more states. Therefore, the primary state for one of these areas is the state associated with the parent or primary record. Also, the primary state is used for aggregating counts and sums at the state level.
* [INTEGER]   `Primary_State_FIPS`
  - State Federal Information Processing Standard (FIPS) code identifying the two numeric character string assigned by the National Institute of Standards and Technology (NIST) to states, the District of Columbia, and U.S. territories.
* [STRING]    `Primary_HHS_Region_Name`
  - Formal name for the U.S. Department of Health and Human Services (DHHS) Region associated with the location or address for the entity. With respect to a Health Professional Shortage Area (HPSA) or a Medically Underserved Area/Population (MUA/P), the physical land area associated with the entity may cross state boundaries, which means a HPSA or MUA/P may consist of components or parts from one or more states. Therefore, the primary state for one of these areas is the state associated with the parent or primary record. Also, the primary state is used for aggregating counts and sums at the state level.
* [STRING]    `US_Mexico_Border_County`
  - Indication of whether a county or a part of a county is listed in U.S. counties that the U.S. - Mexico Border Health Commission has defined as comprising the Border Health Initiative zone. For counties in the contiguous U.S., this data element may differ from the value of the U.S. - Mexico Border 100 Kilometer Indicator due to the fact that three counties in Arizona fall partially within the defined 100-kilometer boundary area, but are not listed in the list of counties that the U.S. - Mexico Border Health Commission identified as comprising the zone of interest.
* [STRING]    `US_Mexico_Border_100km`
  - Indication of whether any portion of the geographic entity cited is within 100 kilometers of the U.S. - Mexico border. The HRSA Data Warehouse generates this value by performing a geoprocessing analysis against the 100 kilometer U.S. - Mexico border region as defined by the HRSA Office of Rural Health Policy, Border Health Program.
* [DATE]      `Data_Warehouse_Record_Create_Date`
  - Date on which the data was processed by the HRSA Data Warehouse.
* [STRING]    `Data_Warehouse_Record_Create_Date_Text`
  - Date on which the data was processed by the HRSA Data Warehouse.
* [STRING]    `HPSA_Name`
  - Title case format, user friendly name which is generated by decoding the Health Professional Shortage Area (HPSA) name which came directly from the source system.
* [STRING]    `HPSA_Component_Name`
  - Name of the Health Professional Shortage Area (HPSA) component, as identified in the source data system. For area HPSAs, a component may be a county, census tract, or minor civil division (MCD).
* [STRING]    `Break_in_Designation`
  - Indication of whether the Health Professional Shortage Area (HPSA) or Medically Underserved Area/Population (MUA/P) has been continuously designated since the original designation date.
* [FLOAT]     `Geocoding_Primary_X`
  - Primary longitude in decimal degrees (x coordinate) of an entity based on its address.
* [FLOAT]     `Geocoding_Primary_Y`
  - Primary latitude in decimal degrees (y coordinate) of an entity based on its address.
* [STRING]    `HPSA_Pop_Type_Code`
  - Code of the population type in a designated Health Professional Shortage Area (HPSA).
* [STRING]    `HPSA_Pop_Type_Desc`
  - Population type description which characterizes the Health Professional Shortage Area (HPSA).
* [INTEGER]   `HPSA_Resident_Civilian_Pop`
  - Population type description for the Health Professional Shortage Area (HPSA).
* [STRING]    `Common_City_Name_with_State_Abbr`
  - City name in which the entity is physically located.
* [INTEGER]   `Common_Postal_Code`
  - Postal code associated with an entity address. For the purposes of the HRSA Data Warehouse this value is a five character U.S. Postal Service (USPS) Zone Improvement Plan (ZIP) code.
* [STRING]    `Common_County_Name`
  - HRSA Data Warehouse (HDW) concatenation of the complete county name and the state abbreviation.
* [STRING]    `Common_StateCounty_FIPS`
  - Combination of the state and county Federal Information Processing Standard (FIPS) codes.
* [STRING]    `Common_State_Abbr`
  - U.S. Postal Service (USPS) two alphabetic character code for a U.S. state or U.S. territory associated with a location where an entity is situated.
* [STRING]    `Common_State_Name`
  - State or territory name.
* [STRING]    `Common_State_FIPS`
  - State Federal Information Processing Standard (FIPS) code identifying the two numeric character string assigned by the National Institute of Standards and Technology (NIST) to states, the District of Columbia, and U.S. territories.
* [STRING]    `Common_Region_Name`
  - Formal name for the U.S. Department of Health and Human Services (HHS) region associated with the entity location or address.
* [DATE]      `HPSA_Withdrawn_Date`
  - Date on which the designation status was changed from designated to withdrawn.
* [STRING]    `HPSA_Withdrawn_Date_String`
  - Date on which the designation status was changed from designated to withdrawn.
* [STRING]    `Provider_Type`
  - Type of mental health providers used in the full-time equivalent (FTE) calculations for the specified Health Professional Shortage Area (HPSA) designation.
* [STRING]    `Rural_Status_Code`
  - Status code indicating rural status of an entity (such as a facility or a geographic area).
* [STRING]    `Rural_Status_Desc`
  - Rural status description for the entity (such as a facility or a geographic area).
* [STRING]    `HPSA_Designation_Pop_Type_Desc`
  - This attribute represents Health Professional Shortage Area (HPSA) designation population type description.
* [STRING]    `BHCMIS_OrgID`
  - Organization source identification number from the HRSA, Bureau of Primary Health Care (BPHC) Health Center Management Information System (BHCMIS).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
