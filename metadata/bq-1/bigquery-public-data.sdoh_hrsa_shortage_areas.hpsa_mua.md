# `sdoh_hrsa_shortage_areas.hpsa_mua`
`bq-1` | `bigquery-public-data`
Metadata on the table is available here: https://data.hrsa.gov//DataDownload/DD_Files/MUA_DATAMART_METADATA.XLSX

## Column details
* [STRING]    `MUA_SOURCE_ID`
  - MUA/P ID; MUA/P Source ID; MUA/P Source Identification Number
* [STRING]    `MUA_AREA_CD`
  - MUA/P Area Code; MUA/P Area Code (Component); MUA/P Service Area
* [STRING]    `MCD_FIPS_Cd`
  - Minor Civil Division FIPS Code; MCD Code
* [STRING]    `MCD_CENSUS_CD`
  - Minor Civil Division Census Code; MCD_Cd; Minor Civil Division Code
* [STRING]    `MCD_NM`
  - Minor Civil Division Name; MCD Name
* [STRING]    `MUA_DESIGNATION_TYP_CD`
  - Designation Type Code; MUA/P Designation Type Code
* [STRING]    `MUA_DESIGNATION_TYP_DESC`
  - Designation Type; MUA/P Designation Type; MUA/P Designation Type Description
* [STRING]    `MUA_STATUS_CD`
  - MUA/P Status Code
* [STRING]    `MUA_STATUS_DESC`
  - MUA/P Status Description; MUA/P Status; Status
* [STRING]    `CENSUS_TRACT`
  - Census Tract
* [DATE]      `MUA_DESIGNATION_DT`
  - Designation Date; MUA/P Designation Date
* [STRING]    `MUA_DESIGNATION_DT_TXT`
  - Designation Date; MUA/P Designation Date; MUA/P Designation Date String
* [STRING]    `MUA_SCORE`
  - IMU Score; Index of Medical Underservice Score; MUA/P Score
* [STRING]    `MUA_SERVICE_AREA_NM`
  - MUA/P Service Area Name; MUA/P Name; Service Area; Service Area Name
* [DATE]      `MUA_UPDATE_DT`
  - MUA/P Update Date; Update Date
* [STRING]    `MUA_UPDATE_DT_TXT`
  - MUA/P Update Date; MUA/P Update Date String; Update Date
* [STRING]    `US_MEXICO_BORDER_100KM_IND`
  - U.S. - Mexico Border 100 Kilometer Indicator; La Paz Agreement; Primary Care Service Area U.S. - Mexico Border Indicator; U.S. - Mexico Border 100 Kilometer Status Indicator
* [STRING]    `US_MEXICO_BORDER_COUNTY_IND`
  - U.S. - Mexico Border County Indicator; Primary Care Service Area U.S. - Mexico Border County Indicator
* [STRING]    `STATE_COUNTY_FIPS_CD`
  - State and County Federal Information Processing Standard Code; State and County FIPS Code; State County FIPS Code
* [STRING]    `COUNTY_FIPS_CD`
  - County or County Equivalent Federal Information Processing Standard Code; County FIPS; County FIPS Code; CountyFIPS
* [STRING]    `LIST_BOX_COUNTY_NM`
  - Complete County Name; County; County Name; County, County Name; List Box County Name
* [STRING]    `COUNTY_NM`
  - County Equivalent Name; Component County Name; County; County (Component); County Equivalent; County Name; County or County Equivalent; County or County Equivalent Name; County, County Equivalent; Grantee County Name
* [STRING]    `COUNTY_DESC`
  - County Description
* [STRING]    `REGION_CD`
  - HHS Region Code; Region Code
* [STRING]    `REGION_NM`
  - HHS Region Name; Component HHS Region; HHS Region; Region Name; Site HHS Region
* [STRING]    `STATE_FIPS_CD`
  - State FIPS Code; State Federal Information Processing Standard Code; State FIPS
* [STRING]    `STATE_NM`
  - State Name; Component State; Component State Name; Site State; State; State Label; State/Territory
* [STRING]    `STATE_ABBR`
  - State Abbreviation; State; State Code; State_Cd
* [FLOAT]     `POVERTY_100_PCT_NUM`
  - Percent of Population with Incomes at or Below 100 Percent of the U.S. Federal Poverty Level; % of Population with Incomes at or Below 100% of the U.S. FPL; Percent of Population with Incomes at or Below 100 Percent of the USFPL
* [FLOAT]     `POP_AGE_65_OVER_PCT`
  - Percentage of Population Age 65 and Over; % of Population Age 65 and Over
* [FLOAT]     `INFANT_MORTALITY_RATE`
  - Infant Mortality Rate
* [STRING]    `PROVIDER_1000_POP_RATIO`
  - Ratio of Providers per 1000 Population
* [FLOAT]     `POVERTY_100_PCT_NUM_IMU`
  - Percent of Population with Incomes at or Below 100 Percent of the U.S. Federal Poverty Level Index of Medical Underservice Score; % of Population with Incomes at or Below 100% of the U.S. FPL IMU Score; Percent of Population with Incomes at or Below 100 Percent of the USFPL IMU Score
* [FLOAT]     `POP_AGE_65_OVER_PCT_IMU`
  - Percentage of Population Age 65 and Over IMU Score; % of Population Age 65 and Over IMU Score; Percentage of Population Age 65 and Over Index of Medical Underservice Score
* [FLOAT]     `INFANT_MORTALITY_RATE_IMU`
  - Infant Mortality Rate IMU Score; Infant Mortality Rate Index of Medical Underservice Score
* [FLOAT]     `PROVIDER_1000_POP_RATIO_IMU`
  - Ratio of Providers per 1000 Population IMU Score; Ratio of Providers per 1000 Population IMU; Ratio of Providers per 1000 Population Index of Medical Underservice Score
* [DATE]      `DW_RECORD_CREATE_DT`
  - Data Warehouse Record Create Date; Data As-of-Date; HRSA Data Warehouse Processing Date; SNAP; Snapshot; Snapshot Date
* [STRING]    `DW_RECORD_CREATE_DT_TXT`
  - Data Warehouse Record Create Date Text; HDW Processing Date; HRSA Data Warehouse Processing Date; SNAP; Snapshot Date; Snapshot Date String; Snapshot Date Text
* [STRING]    `PRIMARY_STATE_FIPS_CD`
  - Primary State FIPS Code; HPSA Primary State FIPS Code; MUA/P Primary State FIPS Code
* [STRING]    `PRIMARY_STATE_ABBR`
  - HPSA Primary State Abbreviation; MUA/P Primary State Abbreviation; Primary State Abbreviation; State
* [STRING]    `PRIMARY_STATE_NM`
  - Primary State Name; HPSA Primary State Name; MUA/P Primary State; Primary State; State
* [STRING]    `PRIMARY_REGION_CD`
  - Primary HHS Region Code; HHS Region Code; HPSA Primary Region Code; MUA/P Primary Region Code; Primary Region Code; Region Code
* [STRING]    `PRIMARY_REGION_NM`
  - Primary HHS Region Name; HHS Region; HPSA Primary Region Name; MUA/P Primary Region Name; Primary Region
* [STRING]    `CMN_REGION_CD`
  - Common Region Code; Common HHS Region Code; HHS Region Code
* [STRING]    `CMN_REGION_NM`
  - Common Region Name; Common HHS Region Name; HHS Region; HHS Region Name; Region Name
* [STRING]    `CMN_STATE_NM`
  - Common State Name; State; State (Component); State Name
* [STRING]    `CMN_STATE_ABBR`
  - Common State Abbreviation; Common State Name; State; State Abbreviation
* [STRING]    `CMN_STATE_FIPS_CD`
  - Common State FIPS Code; State FIPS Code
* [STRING]    `CMN_STATE_COUNTY_FIPS_CD`
  - Common State County FIPS Code; State County FIPS; State County FIPS Code
* [STRING]    `CMN_COUNTY_NM_STATE_ABBR`
  - Common County Name; Common County Name with State Abbreviation; County; County Name; Proper County Name and State Abbreviation
* [STRING]    `BREAK_DESIGNATION_IND`
  - Break in Designation; Break Designation
* [DATE]      `MUA_COMP_DESIGNATION_DT`
  - Medically Underserved Area/Population (MUA/P) Component Designation Date
* [STRING]    `MUA_COMP_DESIGNATION_DT_TXT`
  - Medically Underserved Area/Population (MUA/P) Component Designation Date
* [STRING]    `MUA_COMP_GEO_NM`
  - Medically Underserved Area/Population (MUA/P) Component Geographic Name; Component Name
* [STRING]    `MUA_COMP_GEO_TYP_CD`
  - Medically Underserved Area/Population (MUA/P) Component Geographic Type Code
* [STRING]    `MUA_COMP_GEO_TYP_DESC`
  - Medically Underserved Area/Population (MUA/P) Component Geographic Type Description
* [INTEGER]   `MUA_COMP_GEO_TYP_ID`
  - Medically Underserved Area Geography Type Surrogate Key
* [DATE]      `MUA_COMP_LAST_UPDATE_DT`
  - Medically Underserved Area/Population (MUA/P) Component Last Update Date
* [STRING]    `MUA_COMP_STATUS_CD`
  - Medically Underserved Area/Population (MUA/P) Component Status Code
* [STRING]    `MUA_COMP_STATUS_DESC`
  - Medically Underserved Area/Population (MUA/P) Component Status Description
* [STRING]    `MUA_COMP_UPDATE_DT_TXT`
  - Medically Underserved Area/Population (MUA/P) Component Update Date
* [FLOAT]     `MUA_DESIGNATION_POP`
  - Designation Population in a Medically Underserved Area/Population (MUA/P); MUA/P Population
* [STRING]    `MUA_METRO_IND_CD`
  - Medically Underserved Area/Population (MUA/P) Metropolitan Indicator
* [STRING]    `MUA_METRO_IND_DESC`
  - Medically Underserved Area/Population (MUA/P) Metropolitan Description
* [INTEGER]   `MUA_METRO_IND_ID`
  - Medically Underserved Area/Population (MUA/P) Metropolitan Indicator
* [STRING]    `MUA_POPULATION_TYP_CD`
  - Medically Underserved Area/Population (MUA/P) Population Type Code; MUA/P Population Type Code
* [STRING]    `MUA_POPULATION_TYP_DESC`
  - Medically Underserved Area/Population (MUA/P) Population Type; MUA/P Sub-Type; Population Type
* [INTEGER]   `MUA_POPULATION_TYP_ID`
  - Medically Underserved Area/Population (MUA/P) Population Type ID
* [INTEGER]   `MUA_RES_CIV_POP`
  - Medically Underserved Area/Population (MUA/P) Total Resident Civilian Population
* [DATE]      `MUA_WITHDRAWAL_DT`
  - Medically Underserved Area/Population (MUA/P) Withdrawal Date; Withdrawn Date
* [STRING]    `MUA_WITHDRAWAL_DT_TXT`
  - Medically Underserved Area/Population (MUA/P) Withdrawal Date in Text Format
* [STRING]    `RURAL_STATUS_CD`
  - Rural Status Code
* [STRING]    `RURAL_STATUS_DESC`
  - Rural Status Description; Component Rural Status; Rural Status
* [FLOAT]     `PROVIDER_1000_POP`
  - Providers per 1000 Population; Number of Providers per 1000 Population

-------------------------------------------------------------------------------
*Do not make edits above this line.*
