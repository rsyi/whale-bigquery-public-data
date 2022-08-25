# `cms_medicare.outpatient_charges_2014`
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
* [STRING]    `apc`
  - The code and description identifying the MS-DRG. MS-DRGs are a classification system that groups similar clinical conditions (diagnoses) and the procedures furnished by the hospital during the stay
* [STRING]    `hospital_referral_region`
  - Code and description identifying the APC. APCs are a classification system where individual services (Healthcare Common Procedure Coding System [HCPCS] codes) are assigned based on similar clinical characteristics and similar costs
* [INTEGER]   `outpatient_services`
  - The number of discharges billed by the provider for inpatient hospital services
* [FLOAT]     `average_estimated_submitted_charges`
  - The number of services billed by the provider for outpatient hospital services
* [FLOAT]     `average_total_payments`
  - The provider's average estimated submitted charge for services covered by Medicare for the APC. These will vary from hospital to hospital because of differences in hospital charge structures

-------------------------------------------------------------------------------
*Do not make edits above this line.*
