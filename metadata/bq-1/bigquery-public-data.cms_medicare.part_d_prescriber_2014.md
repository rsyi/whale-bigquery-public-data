# `cms_medicare.part_d_prescriber_2014`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `npi`
  - National Provider Identifier
* [STRING]    `nppes_provider_last_org_name`
  - Last Name/Organization Name of the Provider
* [STRING]    `nppes_provider_first_name`
  - First Name of the Provider
* [STRING]    `nppes_provider_city`
  - City of the Provider
* [STRING]    `nppes_provider_state`
  - State Code of the Provider
* [STRING]    `specialty_description`
  - Provider Specialty Type
* [STRING]    `description_flag`
  - Source of Provider Specialty
* [STRING]    `drug_name`
  - Name of the drug
* [STRING]    `generic_name`
  - Generic name of the drug
* [INTEGER]   `bene_count`
  - Number of Medicare Beneficiaries
* [INTEGER]   `total_claim_count`
  - Number of Medicare Part D Claims, Including Refills
* [INTEGER]   `total_day_supply`
  - Number of Day's Supply for All Claims
* [FLOAT]     `total_drug_cost`
  - Aggregate Cost Paid for All Claims
* [INTEGER]   `bene_count_ge65`
  - Number of Medicare Beneficiaries Age 65+
* [STRING]    `bene_count_ge65_suppress_flag`
  - Reason for Suppression of Bene_Count_ge65
* [INTEGER]   `total_claim_count_ge65`
  - Number of Claims, Including Refills, for Beneficiaries Age 65+
* [STRING]    `ge65_suppress_flag`
  - Reason for Suppression of Total_Claim_Count_Ge65, Total_Drug_Cost_Ge65, and Total_Day_Supply_Ge65
* [INTEGER]   `total_day_supply_ge65`
  - Number of Day's Supply for All Claims for Beneficiaries Age 65+
* [FLOAT]     `total_drug_cost_ge65`
  - Aggregate Cost Paid for All Claims for Beneficiaries Age 65+
* [FLOAT]     `total_30_day_fill_count`
  - The aggregate number of Medicare Part D standardized 30-day fills. The standardized 30-day fill is derived from the number of days supplied on each Part D claim divided by 30. Standardized 30-day fill values less than 1.0 were bottom-coded with a value of 1.0 and standardized 30- day fill values greater than 12.0 were top-coded with a value of 12.0.
* [FLOAT]     `total_30_day_fill_count_ge65`
  - The number of Medicare Part D standardized 30-day fills for beneficiaries age 65 and older. The standardized 30-day fill is derived from the number of days supplied on each Part D claim divided by 30. Standardized 30-day fill values less than 1.0 were bottom-coded with a value of 1.0 and standardized 30-day fill values greater than 12.0 were top-coded with a value of 12.0.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
