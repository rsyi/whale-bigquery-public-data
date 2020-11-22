# `cms_medicare.hospice_providers_2014`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `provider_id`
  - The 6-digit identification number for the hospice provider on the claim.
* [STRING]    `name`
  - The hospice provider name, as reported in the POS file.
* [STRING]    `street_address`
  - The hospice provider address, as reported in the POS file.
* [STRING]    `city`
  - The city where the hospice provider is located, as reported in the POS file.
* [STRING]    `state`
  - The state where the hospice is located, as reported in the POS file. The fifty U.S. states, the District of Columbia and Puerto Rico are reported by the state postal abbreviation.
* [INTEGER]   `zip_code`
  - The hospice provider zip code, as reported in the POS file.
* [STRING]    `hrr`
  - The Hospital Referral Region the hospice provider is located, based on provider ZIP code.
* [INTEGER]   `hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `total_days`
  - Total count of hospice care days provided in the calendar year. Includes first and last day of care.
* [INTEGER]   `total_medicare_payment_amount`
  - Total amount that Medicare paid for hospice care. Hospice services do not have any cost-sharing requirements and the Medicare payment amount will equal the allowed amount.
* [INTEGER]   `total_medicare_standard_payment_amount`
  - Total amount that Medicare paid for hospice care adjusted for geographic differences in payment rates.
* [INTEGER]   `total_charge_amount`
  - Total charges that hospice providers submitted for hospice care.
* [INTEGER]   `percent_routine_home_care_days`
  - Percent of total number of hospice days that were routine home care (RHC) days. RHC days identified using Revenue Code 0651.
* [INTEGER]   `physician_services`
  - Total number of hospice care physician services provided. Physician services identified using Revenue Code 0657.
* [FLOAT]     `home_health_visit_hours_per_day`
  - Average number of hours per day of home health hospice care provided. Home health visits identified using Revenue Codes 0570, 0571, 0572 and 0579.
* [FLOAT]     `skilled_nursing_visit_hours_per_day`
  - Average number of hours per day of skilled nursing hospice care provided. Skilled nursing visits identified using Revenue Codes 0550, 0551, 0552 and 0559.
* [FLOAT]     `social_service_visit_hours_per_day`
  - Average number of hours per day of social services hospice care provided. Social service visits identified using Revenue Codes 0560, 0561, 0562 and 0569.
* [INTEGER]   `total_live_discharges`
  - Number of distinct Medicare beneficiaries with live discharges from hospice care. A hospice beneficiary was considered to have a live discharge if hospice beneficary did not die in hospice care and was not receiving hospice care in CY2015. Includes live discharges for any reason including revocation.
* [INTEGER]   `hospice_beneficiaries_with_seven_or_fewer_hospice_care_days`
  - Number of distinct Medicare beneficiaries with 7 or fewer hospice care days in CY2014. Excludes hospice beneficaries whose hospice care continued from a previous calendar year or into the next calendar year.
* [INTEGER]   `hospice_beneficiaries_with_more_than_sixty_hospice_care_days`
  - Number of distinct Medicare beneficiaries with more than 60 hospice care days in CY2014.
* [INTEGER]   `hospice_beneficiaries_with_more_than_one_hundred_eighty_hospice_care_days`
  - Number of distinct Medicare beneficiaries with more than 180 hospice care days in CY2014.
* [FLOAT]     `home_health_visit_hours_per_day_during_week_prior_to_death`
  - Average number of hours per day of home health hospice care provided during the seven days prior to death. Home health visits identified using Revenue Codes 0570, 0571, 0572 and 0579.
* [FLOAT]     `skilled_nursing_visit_hours_per_day_during_week_prior_to_death`
  - Average number of hours per day of skilled nursing hospice care provided during the seven days prior to death. Skilled nursing visits identified using Revenue Codes 0550, 0551, 0552 and 0559.
* [FLOAT]     `social_service_visit_hours_per_day_during_week_prior_to_death`
  - Average number of hours per day of social services hospice care provided during the seven days prior to death. Social service visits identified using Revenue Codes 0560, 0561, 0562 and 0569.
* [FLOAT]     `average_age`
  - Average age of Medicare beneficiaries using hospice care in CY2014.
* [INTEGER]   `male_hospice_beneficiaries`
  - Number of distinct male Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `female_hospice_beneficiaries`
  - Number of distinct female Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `white_hospice_beneficiaries`
  - Number of distinct white Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `black_hospice_beneficiaries`
  - Number of distinct black Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `asian_hospice_beneficiaries`
  - Number of distinct Asian Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `hispanic_hospice_beneficiaries`
  - Number of distinct Hispanic Medicare beneficiaries receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `other_unknown_race_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries of other/unknown race receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `medicare_advantage_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries enrolled in Medicare Advantage for at least one month and receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `medicaid_eligible_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries eligible for Medicaid for at least one month and receiving at least one day of hospice care in the calendar year.
* [INTEGER]   `hospice_beneficiaries_with_a_primary_diagnosis_of_cancer`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis of cancer. Clinical Classifications Software single level diagnosis categories 11-17 were used to define cancer diagnoses. If a hospice beneficiary had more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `hospice_beneficiaries_with_a_primary_diagnosis_of_dementia`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis of dementia. Clinical Classifications Software single level diagnosis category 653 were used to define dementia diagnoses. If a hospice beneficiary had more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `hospice_beneficiaries_with_a_primary_diagnosis_of_stroke`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis of circulatory/heart disease. Clinical Classifications Software single level diagnosis categories 96-108 and 114-121 were used to define circulatory/heart diagnoses. If a hospice beneficiary had more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `hospice_beneficiaries_with_a_primary_diagnosis_of_circulatory_heart_disease`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis of stroke. Clinical Classifications Software single level diagnosis categories 109-113 were used to define stroke diagnoses. If a hospice beneficiaryhad more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `hospice_beneficiaries_with_a_primary_diagnosis_of_respiratory_disease`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis of respiratory disease. Clinical Classifications Software single level diagnosis categories 127-134 were used to define respiratory diagnoses. If a hospice beneficiary had more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `hospice_beneficiaries_with_other_primary_diagnoses`
  - Number of distinct Medicare beneficiaries receiving hospice care for a primary diagnosis other than cancer, dementia, circulatory/heart, stroke, or respiratory. If a hospice beneficiary had more than one primary diagnosis the most frequent diagnosis in terms of hospice care days was used.
* [INTEGER]   `site_of_service_home_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days at home. Site of service was determined using HCPCS codes Q5001-Q5010, Q5001 indicates care provided in hospice beneficiary's private residence (home).
* [INTEGER]   `site_of_service_assisted_living_facility_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in an assisted living facility. Site of service was determined using HCPCS codes Q5001-Q5010, Q5002 indicates care provided in an assisted living facility.
* [INTEGER]   `site_of_service_long_term_care_or_non_skilled_nursing_facility_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in a long term care or non-skilled nursing facility. Site of service was determined using HCPCS codes Q5001-Q5010, Q5003 indicates care provided in a long term care or non-skilled nursing facility.
* [INTEGER]   `site_of_service_skilled_nursing_facility_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in a skilled nursing facility. Site of service was determined using HCPCS codes Q5001-Q5010, Q5004 indicates care provided in a skilled nursing facility.
* [INTEGER]   `site_of_service_inpatient_hospital_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in an inpatient hospital. Site of service was determined using HCPCS codes Q5001-Q5010, Q5005 indicates care provided in an inpatient hospital.
* [INTEGER]   `site_of_service_inpatient_hospice_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in an inpatient hospice facility. Site of service was determined using HCPCS codes Q5001-Q5010, Q5006 indicates care provided in an inpatient hospice facility.
* [INTEGER]   `site_of_service_other_facility_hospice_beneficiaries`
  - Number of distinct Medicare beneficiaries receiving the majority of their hospice care days in a long term care hospital, psychiatric facility, home care in a hospice facility or unknown facility. Site of service was determined using HCPCS codes Q5001-Q5010, Q5007-Q5010 indicate care provided in other facilities.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
