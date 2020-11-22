# `cms_medicare.home_health_agencies_2014`
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
* [INTEGER]   `distinct_beneficiaries_non_lupa`
  - Number of distinct Medicare beneficiaries receiving at least one non-LUPA home health episode in the calendar year. Beneficiaries may receive multiple home health episodes per year but are only counted once in this field.
* [FLOAT]     `average_number_of_total_visits_per_episode_non_lupa`
  - Average number of total visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_skilled_nursing_visits_per_episode_non_lupa`
  - Average number of skilled nursing visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_pt_visits_per_episode_non_lupa`
  - Average number of physical therapy visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_ot_visits_per_episode_non_lupa`
  - Average number of occupational therapy visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_st_visits_per_episode_non_lupa`
  - Average number of speech therapy visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_home_health_aide_visits_per_episode_non_lupa`
  - Average number of home health aide visits provided by the HHA during a non-LUPA episode.
* [FLOAT]     `average_number_of_medical_social_visits_per_episode_non_lupa`
  - Average number of medical-social visits provided by the HHA during a non-LUPA episode.
* [INTEGER]   `total_hha_charge_amount_non_lupa`
  - Total charges that the home health agency submitted for non-LUPA episodes.
* [INTEGER]   `total_hha_medicare_payment_amount_non_lupa`
  - Total amount that Medicare paid for non-LUPA episodes. Home health services do not have any cost-sharing requirements and the Medicare payment amount will equal the allowed amount.
* [INTEGER]   `total_hha_medicare_standard_payment_amount_non_lupa`
  - Total amount that Medicare paid for non-LUPA episodes adjusted for geographic differences in payment rates.
* [FLOAT]     `outlier_payments_as_a_percent_of_medicare_payment_amount_non_lupa`
  - The percent of total Medicare payments for non-LUPA episodes paid to an HHA for outlier episodes.
* [INTEGER]   `total_lupa_episodes`
  - Total count of low utilization payment amount episodes provided by a specific HHA in the calendar year.
* [INTEGER]   `total_hha_medicare_payment_amount_for_lupas`
  - Total amount that Medicare paid for LUPA episodes provided by a specific HHA in the calendar year.
* [INTEGER]   `average_age`
  - Average age of beneficiaries. Beneficiary age is calculated at the end of the calendar year or at the time of death.
* [INTEGER]   `male_beneficiaries`
  - Number of male beneficiaries.
* [INTEGER]   `female_beneficiaries`
  - Number of female beneficiaries.
* [INTEGER]   `nondual_beneficiaries`
  - Number of Medicare beneficiaries qualified to receive Medicare only benefits. Beneficiaries are classified as Medicare only entitlement if they received zero months of any Medicaid benefits (full or partial) in the given calendar year.
* [INTEGER]   `dua_beneficiaries`
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
