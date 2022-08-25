# `cms_medicare.inpatient_charges_2013`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `provider_id`
  - The CMS Certification Number (CCN) of the provider billing for outpatient hospital services
* [STRING]    `provider_name`
  - The name of the provider
* [STRING]    `provider_street_address`
  - The street address in which the provider is physically located
* [STRING]    `provider_city`
  - The city in which the provider is physically located
* [STRING]    `provider_state`
  - The state in which the provider is physically located
* [STRING]    `provider_zipcode`
  - The zip code in which the provider is physically located
* [STRING]    `drg_definition`
  - The code and description identifying the MS-DRG. MS-DRGs are a classification system that groups similar clinical conditions (diagnoses) and the procedures furnished by the hospital during the stay
* [STRING]    `hospital_referral_region_description`
  - The Hospital Referral Region (HRR) in which the provider is physically located
* [INTEGER]   `total_discharges`
  - The number of discharges billed by the provider for inpatient hospital services
* [FLOAT]     `average_covered_charges`
  - The provider's average charge for services covered by Medicare for all discharges in the MS-DRG. These will vary from hospital to hospital because of differences in hospital charge structures
* [FLOAT]     `average_total_payments`
  - The average total payments to all providers for the MS-DRG including the MSDRG amount, teaching, disproportionate share, capital, and outlier payments for all cases. Also included 5 in average total payments are co-payment and deductible amounts that the patient is responsible for and any additional payments by third parties for coordination of benefits
* [FLOAT]     `average_medicare_payments`
  - The average amount that Medicare pays to the provider for Medicare's share of the MS-DRG. Average Medicare payment amounts include the MS-DRG amount, teaching, disproportionate share, capital, and outlier payments for all cases. Medicare payments DO NOT include beneficiary co-payments and deductible amounts nor any additional payments from third parties for coordination of benefits

-------------------------------------------------------------------------------
*Do not make edits above this line.*
