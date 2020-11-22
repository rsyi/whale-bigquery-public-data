# `cms_medicare.nursing_facilities_2014`
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
* [FLOAT]     `average_length_of_stays_days`
  - Average lenth of stay, in days, for all Medicare beneficiaries with at least one stay in the skilled nursing facility in the year.
* [INTEGER]   `total_snf_charge_amount`
  - Total of the charges that the skilled nursing facility submitted for all Medicare stays in the year.
* [INTEGER]   `total_snf_medicare_allowed_amount`
  - Total Medicare allowed amount for all Medicare stays in the year. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [INTEGER]   `total_snf_medicare_payment_amount`
  - Total amount that Medicare paid for all Medicare stays in the year after deductible and coinsurance amounts have been deducted.
* [INTEGER]   `total_snf_medicare_standard_payment_amount`
  - Total amount that Medicare paid for all Medicare stays in the year after deductible and coinsurance amounts have been deducted, adjusted for geographic differences in payment rates.
* [INTEGER]   `average_age`
  - Average age of beneficiaries. Beneficiary age is calculated at the end of the calendar year or at the time of death.
* [INTEGER]   `male_beneficiaries`
  - Number of male beneficiaries.
* [INTEGER]   `female_beneficiaries`
  - Number of female beneficiaries.
* [INTEGER]   `nondual_beneficiaries`
  - Number of Medicare beneficiaries qualified to receive Medicare only benefits. Beneficiaries are classified as Medicare only entitlement if they received zero months of any Medicaid benefits (full or partial) in the given calendar year.
* [INTEGER]   `dual_beneficiaries`
  - Number of Medicare beneficiaries qualified to receive Medicare and Medicaid benefits. Beneficiaries are classified as Medicare and Medicaid entitlement if in any month in the given calendar year they were receiving full or partial Medicaid benefits.
* [INTEGER]   `white_beneficiaries`
  - Number of non-Hispanic white beneficiaries.
* [INTEGER]   `black_beneficiaries`
  - Number of non-Hispanic black or African American beneficiaries.
* [INTEGER]   `asian_pacific_islander_beneficiaries`
  - Number of Asian Pacific Islander beneficiaries.
* [INTEGER]   `hispanic_beneficiaries`
  - Number of Hispanic beneficiaries.
* [INTEGER]   `american_indian_or_alaska_native_beneficiaries`
  - Number of American Indian or Alaska Native beneficiaries.
* [INTEGER]   `other_unknown_beneficiaries`
  - Number of beneficiaries with race not elsewhere classified.
* [FLOAT]     `average_hcc_score`
  - Average Hierarchical Condition Category (HCC) risk score of beneficiaries. Please refer to the “Additional Information” section of the Methodology document for more details on HCC risk scores.
* [INTEGER]   `percent_of_beneficiaries_with_atrial_fibrillation`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for atrial fibrillation.
* [INTEGER]   `percent_of_beneficiaries_with_alzheimers`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for Alzheimer’s, related disorders, or dementia.
* [INTEGER]   `percent_of_beneficiaries_with_asthma`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for Asthma.
* [INTEGER]   `percent_of_beneficiaries_with_cancer`
  - Percent of beneficiaries meeting the CCW chronic condition algorithms for cancer. Includes breast cancer, colorectal cancer, lung cancer and prostate cancer.
* [INTEGER]   `percent_of_beneficiaries_with_chf`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for heart failure.
* [INTEGER]   `percent_of_beneficiaries_with_chronic_kidney_disease`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for chronic kidney disease.
* [INTEGER]   `percent_of_beneficiaries_with_copd`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for chronic obstructive pulmonary disease.
* [INTEGER]   `percent_of_beneficiaries_with_depression`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for depression.
* [INTEGER]   `percent_of_beneficiaries_with_diabetes`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for diabetes.
* [INTEGER]   `percent_of_beneficiaries_with_hyperlipidemia`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for hyperlipidemia.
* [INTEGER]   `percent_of_beneficiaries_with_hypertension`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for hypertension.
* [INTEGER]   `percent_of_beneficiaries_with_ihd`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for ischemic heart disease.
* [INTEGER]   `percent_of_beneficiaries_with_osteoporosis`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for osteoporosis.
* [INTEGER]   `percent_of_beneficiaries_with_ra_oa`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for rheumatoid arthritis/osteoarthritis.
* [INTEGER]   `percent_of_beneficiaries_with_schizophrenia`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for schizophrenia and other psychotic disorders.
* [INTEGER]   `percent_of_beneficiaries_with_stroke`
  - Percent of beneficiaries meeting the CCW chronic condition algorithm for stroke.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
