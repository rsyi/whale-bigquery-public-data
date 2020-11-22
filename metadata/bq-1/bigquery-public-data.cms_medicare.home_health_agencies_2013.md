# `cms_medicare.home_health_agencies_2013`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `provider_id`
  - The 6-digit identification number for the home health agency on the claim.
* [STRING]    `agency_name`
  - The home health agency name, as reported in the POS file.
* [STRING]    `street_address`
  - The home health agency address, as reported in the POS file.
* [STRING]    `city`
  - The city where the home health agency is located, as reported in the POS file.
* [STRING]    `state`
  - The state where the home health agency is located, as reported in POS file. The fifty U.S. states and the District of Columbia are reported by the state postal abbreviation.
* [INTEGER]   `zip_code`
  - The home health agency’s zip code, as reported in the POS file.
* [INTEGER]   `total_episodes_non_lupa`
  - Total count of non-LUPA episodes provided by a specific home health agency or in a unique HHRG category in the calendar year.
* [INTEGER]   `distinct_users_non_lupa`
  - Number of distinct Medicare beneficiaries receiving at least one non-LUPA home health episode in the calendar year. Beneficiaries may receive multiple home health episodes per year but are only counted once in this field.
* [INTEGER]   `total_hha_charge_amount_non_lupa`
  - Total charges that the home health agency submitted for non-LUPA episodes.
* [INTEGER]   `total_hha_medicare_payment_amount_non_lupa`
  - Total amount that Medicare paid for non-LUPA episodes. Home health services do not have any cost-sharing requirements and the Medicare payment amount will equal the allowed amount.
* [INTEGER]   `total_hha_medicare_standard_payment_amount_non_lupa`
  - Total amount that Medicare paid for non-LUPA episodes adjusted for geographic differences in payment rates.
* [INTEGER]   `outlier_payments_as_a_percent_of_medicare_payment_amount_non_lupa`
  - The percent of total Medicare payments for non-LUPA episodes paid to an HHA for outlier episodes.
* [INTEGER]   `total_lupa_episodes`
  - Total count of low utilization payment amount episodes provided by a specific HHA in the calendar year.
* [INTEGER]   `total_hha_medicare_payment_amount_for_lupas`
  - Total amount that Medicare paid for LUPA episodes provided by a specific HHA in the calendar year.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
