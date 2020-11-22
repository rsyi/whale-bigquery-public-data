# `sdoh_cms_dual_eligible_enrollment.dual_eligible_enrollment_by_county_and_program`
`bq-1` | `bigquery-public-data`
This document presents counts of Medicare-Medicaid dual enrollees (including those in Medicare Savings Programs), by eligibility type, who were enrolled in a given month (to be continuously updated on a quarterly basis).  They include numbers of individuals at both the state and county level.   Note that these are monthly snapshots and are inherently lower than ever-enrolled counts which include persons enrolled at any time during a calendar year.  The underlying source data are the Medicare Modernization Act (MMA) data that states submit to CMS on an at-least monthly basis. These data are subject to retroactive adjustment.  Analyses were conducted within the Chronic Condition Data Warehouse (CCW) environment.   For more information on identifying dually eligible beneficiaries within CMS data, please refer to the following website: https://www.cms.gov/Medicare-Medicaid-Coordination/Medicare-and-Medicaid-Coordination/Medicare-Medicaid-Coordination-Office/Downloads/MMCO_Definition_of_Dual_Eligible.pdf.

## Column details
* [STRING]    `State_Abbr`
  - State of Beneficiary
* [STRING]    `County_Name`
  - County of Beneficiary
* [INTEGER]   `QMB_Only`
  - Number of Qualified Medicare Beneficiary Program (QMB) Only Enrollees
* [INTEGER]   `QMB_plus_Full`
  - Number of Qualified Medicare Beneficiary Program (QMB) plus Full Medicaid Enrollees
* [INTEGER]   `SLMB_only`
  - Number of Specified Low-Income Medicare Beneficiary (SLMB) Program Only Enrollees
* [INTEGER]   `SLMB_plus_Full`
  - Number of Specified Low-Income Medicare Beneficiary (SMLB) plus Full Medicaid Enrollees
* [INTEGER]   `QDWI`
  - Number of Qualifying Disabled Working Individual (QDWI) Enrollees
* [INTEGER]   `QI`
  - Number of Qualifying Individual (QI) Enrollees
* [INTEGER]   `Other_full`
  - Number of Other Dual Full Medicaid Enrollees
* [INTEGER]   `Public_Total`
  - Total Enrollees Across All Dual Eligible Programs
* [DATE]      `Date`
  - Date of Enrollment Snapshot
* [STRING]    `FIPS`
  - Geo FIPS Code

-------------------------------------------------------------------------------
*Do not make edits above this line.*
