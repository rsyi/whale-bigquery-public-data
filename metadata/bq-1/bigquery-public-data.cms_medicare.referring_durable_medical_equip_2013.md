# `cms_medicare.referring_durable_medical_equip_2013`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `referring_npi`
  - NPI for the referring provider on the DMEPOS claim.
* [STRING]    `referring_provider_last_name_organization_name`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s last name. When the referring provider is registered as an organization (entity type code = ‘O’), this is the organization name.
* [STRING]    `referring_provider_first_name`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s first name. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `referring_provider_middle_initial`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s middle initial. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `referring_provider_credentials`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), these are the referring provider’s credentials. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `referring_provider_gender`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s gender. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `referring_provider_entity_code`
  - Type of entity reported in NPPES. An entity code of ‘I’ identifies referring providers registered as individuals and an entity type code of ‘O’ identifies referring providers registered as organizations.
* [STRING]    `referring_provider_street_1`
  - The first line of the referring provider’s street address, as reported in NPPES.
* [STRING]    `referring_provider_street_2`
  - The second line of the referring provider’s street address, as reported in NPPES.
* [STRING]    `referring_provider_city`
  - The city where the referring provider is located, as reported in NPPES.
* [STRING]    `referring_provider_state`
  - The state where the referring provider is located, as reported in NPPES. The fifty U.S. states and the District of Columbia are reported by the state postal abbreviation. The following values are used for other areas: 'XX' = 'Unknown' 'AA' = 'Armed Forces Central/South America' 'AE' = 'Armed Forces Europe' 'AP' = 'Armed Forces Pacific' 'AS' = 'American Samoa' 'GU' = 'Guam' 'MP' = 'North Mariana Islands' 'PR' = 'Puerto Rico' 'VI' = 'Virgin Islands' 'ZZ' = 'Foreign Country'
* [STRING]    `referring_provider_zip`
  - The referring provider’s zip code, as reported in NPPES.
* [STRING]    `referring_provider_country`
  - The country where the referring provider is located, as reported in NPPES. The country code will be ‘US’ for any state or U.S. possession. For foreign countries (i.e., state values of ‘ZZ’), the provider country values include the following: ‘AE’ = ‘United Arab Emirates’; ‘IL’= Israel’; ‘AR’= ‘Argentina’; ‘IN’= India’; ‘AU’= ‘Australia’; ‘IS’= Iceland; ‘BR’= ‘Brazil’; ‘IT’= Italy’; ‘CA’= ‘Canada’; ‘JP’= Japan’; ‘CH’= Switzerland’; ‘KR’= ‘Korea’; ‘CN’= China’; ‘NL’= ‘Netherlands’; ‘CO’= Colombia’; ‘PK’= ‘Pakistan’; ‘DE’= ‘Germany’; ‘SA’= ‘Saudi Arabia’; ‘ES’= ‘Spain’; ‘SY’= ‘Syria’; ‘FR’= France’; ‘TR’= ‘Turkey’; ‘GB’= Great Britain’; ‘VE’= ‘Venezuela’; ‘HU’= Hungary’
* [STRING]    `referring_provider_type`
  - Derived from the Medicare provider/supplier specialty code reported on all of the NPI's Part B non-institutional claims (DMEPOS & non-DMEPOS). For referring providers that have more than one Medicare specialty code reported on their claims, the Medicare specialty code associated with the largest number of services was used. Where a prescriber's NPI did not have associated Part B claims, the taxonomy code associated with the NPI in NPPES was mapped to a Medicare specialty code using an external crosswalk published here: http://www.cms.gov/Medicare/Provider-Enrollment-and-Certification/MedicareProviderSupEnroll/Taxonomy.html. For any taxonomy codes that could not be mapped to a Medicare specialty code, the taxonomy classification description was used.
* [STRING]    `referring_provider_type_flag`
  - A flag variable that indicates the source of the Referring Provider Type: "S" = Medicare Specialty Code description "T" = Taxonomy Code Classification description
* [INTEGER]   `number_of_suppliers`
  - Number of suppliers rendering products/services billed through DMEPOS MACs.
* [INTEGER]   `number_of_supplier_hcpcs`
  - Total number of unique DMEPOS product/service hcpcs codes billed by suppliers and ordered by the referring provider.
* [INTEGER]   `number_of_supplier_beneficiaries`
  - Total number of unique beneficiaries associated with DMEPOS claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries.
* [INTEGER]   `number_of_supplier_claims`
  - Total number of DMEPOS claims submitted by suppliers, reflecting products/services ordered by the referring provider.
* [INTEGER]   `number_of_supplier_services`
  - Total DMEPOS products/services rendered by suppliers and ordered by the referring provider.
* [FLOAT]     `supplier_submitted_charges`
  - The total charges that suppliers submitted for all DMEPOS products/services ordered by the referring provider.
* [FLOAT]     `supplier_medicare_allowed_amount`
  - The Medicare allowed amount for all DMEPOS products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [FLOAT]     `supplier_medicare_payment_amount`
  - Amount that Medicare paid after deductible and coinsurance amounts have been deducted for all supplier's DMEPOS line item products/services ordered by the referring provider.
* [STRING]    `durable_medical_equipment_suppression_indicator`
  - A 1-byte value which defines the suppression, if needed, of the utilization, charge and payment information associated with durable medical equipment HCPCS codes. A value of '*' means the suppressed information is based on a dme-specific claim count of 1 through 10. A value of '#' means the dme-specific information has been counter-suppressed. Counter-suppression is needed when the display of dme-specific data could be used to recalculate suppressed values in non-dme-specific columns.
* [INTEGER]   `number_of_durable_medical_equipment_suppliers`
  - Number of suppliers rendering durable medical equipment products/services.
* [INTEGER]   `number_of_durable_medical_equipment_hcpcs`
  - Total number of unique beneficiaries associated with durable medical equipment claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries.
* [INTEGER]   `number_of_durable_medical_equipment_beneficiaries`
  - Total number of unique durable medical equipment hcpcs codes billed by suppliers and ordered by the referring provider.
* [INTEGER]   `number_of_durable_medical_equipment_claims`
  - Total number of durable medical equipment claims submitted by suppliers, reflecting services ordered by the referring provider.
* [INTEGER]   `number_of_durable_medical_equipment_services`
  - Total durable medical equipment products/services rendered by suppliers and ordered by the referring provider.
* [FLOAT]     `durable_medical_equipment_submitted_charges`
  - The total charges that suppliers submitted for all durable medical equipment products/services ordered by the referring provider.
* [FLOAT]     `durable_medical_equipment_medicare_allowed_amount`
  - The Medicare allowed amount for all durable medical equipment products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [FLOAT]     `durable_medical_equipment_medicare_payment_amount`
  - Amount that Medicare paid after deductible and coinsurance amounts have been deducted for all supplier's durable medical equipment line item products/services ordered by the referring provider.
* [STRING]    `prosthetic_and_orthotic_suppression_indicator`
  - A 1-byte value which defines the suppression, if needed, of the utilization, charge and payment information associated with prosthetic and orthotic HCPCS codes. A value of '*' means the suppressed information is based on a prosthetic and orthotic-specific claim count of 1 through 10. A value of '#' means the prosthetic and orthotic-specific information has been counter-suppressed. Counter-suppression is needed when the display of prosthetic and orthotic-specific data could be used to recalculate suppressed values in non-prosthetic and orthotic-specific columns.
* [INTEGER]   `number_of_prosthetic_and_orthotic_suppliers`
  - Number of suppliers rendering prosthetic and orthotic products/services.
* [INTEGER]   `number_of_prosthetic_and_orthotic_hcpcs`
  - Total number of unique prosthetic and orthotic hcpcs codes billed by suppliers and ordered by the referring provider.
* [INTEGER]   `number_of_prosthetic_and_orthotic_beneficiaries`
  - Total number of unique beneficiaries associated with prosthetic and orthotic claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries.
* [INTEGER]   `number_of_prosthetic_and_orthotic_claims`
  - Total number of prosthetic and orthotic claims submitted by suppliers, reflecting products/services ordered by the referring provider.
* [INTEGER]   `number_of_prosthetic_and_orthotic_services`
  - Total prosthetic and orthotic products/services rendered by suppliers and ordered by the referring provider.
* [FLOAT]     `prosthetic_and_orthotic_submitted_charges`
  - The total charges that suppliers submitted for all prosthetic and orthotic products/services ordered by the referring provider.
* [FLOAT]     `prosthetic_and_orthotic_medicare_allowed_amount`
  - The Medicare allowed amount for all prosthetic and orthotic products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [FLOAT]     `prosthetic_and_orthotic_medicare_payment_amount`
  - Amount that Medicare paid after deductible and coinsurance amounts have been deducted for all supplier's prosthetic and orthotic line item products/services ordered by the referring provider.
* [STRING]    `drug_and_nutritional_suppression_indicator`
  - A 1-byte value which defines the suppression, if needed, of the utilization, charge and payment information associated with drug and nutritional HCPCS codes. A value of '*' means the suppressed information is based on a drug and nutritional-specific claim count of 1 through 10. A value of '#' means the drug and nutritional-specific information has been counter-suppressed. Counter-suppression is needed when the display of drug and nutritional-specific data could be used to recalculate suppressed values in non-drug and nutritional-specific columns.
* [INTEGER]   `number_of_drug_and_nutritional_products_suppliers`
  - Number of suppliers rendering drug and nutritional products/services.
* [INTEGER]   `number_of_drug_and_nutritional_products_hcpcs`
  - Total number of unique drug and nutritional product hcpcs codes billed by suppliers and ordered by the referring provider.
* [INTEGER]   `number_of_drug_and_nutritional_products_beneficiaries`
  - Total number of unique beneficiaries associated with drug and nutritional product claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries.
* [INTEGER]   `number_of_drug_and_nutritional_products_claims`
  - Total number of drug and nutritional product claims submitted by suppliers, reflecting services ordered by the referring provider.
* [INTEGER]   `number_of_drug_and_nutritional_products_services`
  - Total drug and nutritional products/services rendered by suppliers and ordered by the referring provider.
* [FLOAT]     `drug_and_nutritional_products_submitted_charges`
  - The total charges that suppliers submitted for drug and nutritional products/services ordered by the referring provider.
* [FLOAT]     `drug_and_nutritional_products_medicare_allowed_amount`
  - The Medicare allowed amount for drug and nutritional products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying.
* [FLOAT]     `drug_and_nutritional_products_medicare_payment_amount`
  - Amount that Medicare paid suppliers after deductible and coinsurance amounts have been deducted for drug and nutritional line item products/services ordered by the referring provider.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
