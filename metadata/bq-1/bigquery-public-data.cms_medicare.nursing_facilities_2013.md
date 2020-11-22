# `cms_medicare.nursing_facilities_2013`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `provider_id`
  - The 6-digit identification number for the skilled nursing facility on the claim.
* [STRING]    `facility_name`
  - The skilled nursing facility name, as reported in the POS file.
* [STRING]    `street_address`
  - The skilled nursing facility address, as reported in the POS file.
* [STRING]    `city`
  - The city where the skilled nursing facility is located, as reported in the POS file.
* [STRING]    `state`
  - The state where the skilled nursing facility is located, as reported in POS file. The fifty U.S. states and the District of Columbia are reported by the state postal abbreviation.
* [INTEGER]   `zip_code`
  - The skilled nursing facility’s zip code, as reported in the POS file.
* [INTEGER]   `total_stays`
  - Total number of skilled nursing facility stays.
* [INTEGER]   `distinct_beneficiaries_per_provider`
  - Number of distinct Medicare beneficiaries with at least one skilled nursing facility day per provider. A beneficiary will only be counted once per provider, but may be double-counted across providers.
* [INTEGER]   `average_length_of_stay_days`
  - Average lenth of stay, in days, for all Medicare beneficiaries with at least one stay in the skilled nursing facility in the year.
* [INTEGER]   `total_snf_charge_amount`
  - Total of the charges that the skilled nursing facility submitted for all Medicare stays in the year.
* [INTEGER]   `total_snf_medicare_allowed_amount`
  - Total Medicare allowed amount for all Medicare stays in the year. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [INTEGER]   `total_snf_medicare_payment_amount`
  - Total amount that Medicare paid for all Medicare stays in the year after deductible and coinsurance amounts have been deducted.
* [INTEGER]   `total_snf_medicare_standard_payment_amount`
  - Total amount that Medicare paid for all Medicare stays in the year after deductible and coinsurance amounts have been deducted, adjusted for geographic differences in payment rates.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
