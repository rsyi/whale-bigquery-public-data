# `medicare.outpatient_charges_2013`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `apc`
  - Code and description identifying the APC. APCs are a classification system where individual services (Healthcare Common Procedure Coding System [HCPCS] codes) are assigned based on similar clinical characteristics and similar costs
* [INTEGER]   `provider_id`
  - The CMS Certification Number (CCN) of the provider billing for outpatient hospital services
* [STRING]    `provider_name`
  - The name of the provider
* [STRING]    `provider_street_address`
  - The street address in which the provider is physically located
* [STRING]    `provider_city`
  - The city in which the provider is physically located
* [STRING]    `provider_state`
  - The state in which the provider is physically located
* [INTEGER]   `provider_zipcode`
  - The zip code in which the provider is physically located
* [STRING]    `hospital_referral_region`
  - The Hospital Referral Region (HRR) in which the provider is physically located
* [INTEGER]   `outpatient_services`
  - The number of services billed by the provider for outpatient hospital services
* [FLOAT]     `average_estimated_submitted_charges`
  - The provider's average estimated submitted charge for services covered by Medicare for the APC. These will vary from hospital to hospital because of differences in hospital charge structures
* [FLOAT]     `average_total_payments`
  - The average of total payments to the provider for the APC including the Medicare APC amount. Also included in Total Payments are co-payment and deductible amounts that the patient is responsible for

-------------------------------------------------------------------------------
*Do not make edits above this line.*
