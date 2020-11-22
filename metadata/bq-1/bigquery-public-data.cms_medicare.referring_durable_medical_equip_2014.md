# `cms_medicare.referring_durable_medical_equip_2014`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `referring_npi`
  - NPI for the referring provider on the DMEPOS claim.
* [STRING]    `provider_last_name`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s last name. When the referring provider is registered as an organization (entity type code = ‘O’), this is the organization name.
* [STRING]    `provider_first_name`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s first name. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `provider_middle_initial`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s middle initial. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `provider_credentials`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), these are the referring provider’s credentials. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `provider_gender`
  - When the referring provider is registered in NPPES as an individual (entity type code=’I’), this is the referring provider’s gender. When the referring provider is registered as an organization (entity type code = ‘O’), this will be blank.
* [STRING]    `provider_entity_code`
  - Type of entity reported in NPPES. An entity code of ‘I’ identifies referring providers registered as individuals and an entity type code of ‘O’ identifies referring providers registered as organizations.
* [STRING]    `provider_street_1`
  - The first line of the referring provider’s street address, as reported in NPPES.
* [STRING]    `provider_street_2`
  - The second line of the referring provider’s street address, as reported in NPPES.
* [STRING]    `provider_city`
  - The city where the referring provider is located, as reported in NPPES
* [STRING]    `provider_state`
  - The state where the referring provider is located, as reported in NPPES. The fifty U.S. states and the District of Columbia are reported by the state postal abbreviation. The following values are used for other areas: 'XX' = 'Unknown' 'AA' = 'Armed Forces Central/South America' 'AE' = 'Armed Forces Europe' 'AP' = 'Armed Forces Pacific' 'AS' = 'American Samoa' 'GU' = 'Guam' 'MP' = 'North Mariana Islands' 'PR' = 'Puerto Rico' 'VI' = 'Virgin Islands' 'ZZ' = 'Foreign Country'
* [STRING]    `provider_zip`
  - The referring provider’s zip code, as reported in NPPES.
* [STRING]    `provider_country`
  - The country where the referring provider is located, as reported in NPPES. The country code will be ‘US’ for any state or U.S. possession. For foreign countries (i.e., state values of ‘ZZ’), the provider country values include the following: AE=United Arab Emirates IT=Italy AG=Antigua JP=Japan AR=Argentina KR=Korea AU=Australia KW=Kuwait BO=Bolivia KY=Cayman Islands BR=Brazil LB=Lebanon CA=Canada MX=Mexico CH=Switzerland NL=Netherlands CN=China NO=Norway CO=Colombia NZ=New Zealand DE= Germany PA=Panama ES= Spain PK=Pakistan FR=France RW=Rwanda GB=Great Britain SA=Saudi Arabia HU= Hungary SY=Syria IL= Israel TH=Thailand IN=India TR=Turkey IS= Iceland VE=Venezuela
* [STRING]    `provider_type`
  - Derived from the Medicare provider/supplier specialty code reported on all of the NPI's Part B non-institutional claims (DMEPOS and non-DMEPOS). For referring providers that have more than one Medicare specialty code reported on their claims, the Medicare specialty code associated with the largest number of services was used.
* [STRING]    `provider_type_flag`
  - A flag variable that indicates the source of the Referring Provider Type: "S" = Medicare Specialty Code description "T" = Taxonomy Code Classification description
* [INTEGER]   `number_of_suppliers`
  - Number of suppliers rendering DMEPOS products/services ordered by the referring provider.
* [INTEGER]   `number_of_supplier_hcpcs`
  - Total number of unique DMEPOS product/service HCPCS codes billed by suppliers and ordered by the referring provider.
* [INTEGER]   `number_of_supplier_beneficiaries`
  - Number of beneficiaries associated with the supplier DMEPOS products/services ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries.
* [INTEGER]   `number_of_supplier_claims`
  - Number of DMEPOS claims submitted by the supplier, reflecting products/services ordered by the referring provider. Aggregated records based on number_of_supplier_claims fewer than 11 are not included in the data file.
* [INTEGER]   `number_of_supplier_services`
  - Number of DMEPOS products/services rendered by the supplier; note that the metrics used to count the number provided can vary from service to service.
* [FLOAT]     `supplier_submitted_charges`
  - Average of the charges that suppliers submit for DMEPOS products/services. Total submitted charges can be calculated by multiplying the avg_supplier_submitted_charge by the number_of_supplier_services.
* [FLOAT]     `supplier_medicare_allowed_amount`
  - Average Medicare allowed amounts for the DMEPOS product/service rendered by suppliers. Medicare allowed amounts includes the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying. Total Medicare allowed amounts can be calculated by multiplying the avg_supplier_medicare_allow_amt by the number_of_supplier_services.
* [FLOAT]     `supplier_medicare_payment_amount`
  - Average amount that Medicare paid suppliers after deductible and coinsurance amounts have been deducted for the line item DMEPOS product/service. Total Medicare payment amounts can be calculated by multiplying the avg_supplier_medicare_pmt_amt by the number_of_supplier_services.
* [FLOAT]     `supplier_medicare_standard_payment_amount`
  - Average amount that Medicare paid after beneficiary deductible and coinsurance amounts have been deducted for the line item DMEPOS product/service and after standardization of the Medicare payment has been applied. Standardization removes geographic differences in payment rates for individual product/services and makes Medicare payments across geographic areas comparable.
* [STRING]    `durable_medical_equipment_suppression_indicator`
  - A flag indicating the reason the utilization, charge and payment subtotal information for Durable Medical Equipment is suppressed. “*” = Primary suppressed due to Number of Durable Medical Equipment Claims between 1 and 10. “#” = Counter suppressed because the claim count from at least one of the corresponding claim count categories (Number of Prosthetic and Orthotic Claims or Number of Drug and Nutritional Products Claims) is between 1 and 10. Counter suppression prevents the disclosure of a primary suppressed value when all categories sum to the total value.
* [INTEGER]   `dme_suppliers`
  - Number of suppliers rendering durable medical equipment products/services. A blank indicates the value is suppressed.
* [INTEGER]   `dme_hcpcs`
  - Total number of unique durable medical equipment HCPCS codes billed by suppliers and ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `dme_beneficiaries`
  - Total number of unique beneficiaries associated with durable medical equipment claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries. A blank indicates the value is suppressed.
* [INTEGER]   `dme_claims`
  - Total number of durable medical equipment claims submitted by suppliers, reflecting services ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `dme_services`
  - Total durable medical equipment products/services rendered by suppliers and ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `dme_submitted_charges`
  - The total charges that suppliers submitted for all durable medical equipment products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `dme_medicare_allowed_amount`
  - The Medicare allowed amount for all durable medical equipment products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying. A blank indicates the value is suppressed.
* [FLOAT]     `dme_medicare_payment_amount`
  - Amount that Medicare paid after deductible and coinsurance amounts have been deducted for all supplier's durable medical equipment line item products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `dme_medicare_standard_payment_amount`
  - Amount that Medicare paid after beneficiary deductible and coinsurance amounts have been deducted for all supplier’s durable medical equipment line item products/services and after standardization of the Medicare payment has been applied. Standardization removes geographic differences in payment rates for individual product/services and makes Medicare payments across geographic areas comparable. A blank indicates the value is suppressed.
* [STRING]    `prosthetic_and_orthotic_suppression_indicator`
  - A flag indicating the reason the utilization, charge and payment subtotal information for Prosthetics and Orthotics is suppressed.  “*” = Primary suppressed due to Number of Prosthetic and Orthotic Claims between 1 and 10. “#” = Counter suppressed because the claim count from at least one of the corresponding claim count categories (Number of Durable Medical Equipment Claims or Number of Drug and Nutritional Products Claims) is between 1 and 10. Counter suppression prevents the disclosure of a primary suppressed value when all categories sum to the total value.
* [INTEGER]   `po_suppliers`
  - Number of suppliers rendering prosthetic and orthotic products/services. A blank indicates the value is suppressed.
* [INTEGER]   `po_hcpcs`
  - Total number of unique prosthetic and orthotic HCPCS codes billed by suppliers and ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `po_beneficiaries`
  - Total number of unique beneficiaries associated with prosthetic and orthotic claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries. A blank indicates the value is suppressed.
* [INTEGER]   `po_claims`
  - Total number of prosthetic and orthotic claims submitted by suppliers, reflecting products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `po_services`
  - Total prosthetic and orthotic products/services rendered by suppliers and ordered by the referring provider. A blank indicates the value is suppressed..
* [FLOAT]     `po_submitted_charges`
  - The total charges that suppliers submitted for all prosthetic and orthotic products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `po_medicare_allowed_amount`
  - The Medicare allowed amount for all prosthetic and orthotic products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying. A blank indicates the value is suppressed.
* [FLOAT]     `po_medicare_payment_amount`
  - Amount that Medicare paid after deductible and coinsurance amounts have been deducted for all supplier prosthetic and orthotic line item products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `po_medicare_standard_payment_amount`
  - Amount that Medicare paid after beneficiary deductible and coinsurance amounts have been deducted for all supplier’s prosthetic and orthotic line item products/services and after standardization of the Medicare payment has been applied. Standardization removes geographic differences in payment rates for individual product/services and makes Medicare payments across geographic areas comparable. A blank indicates the value is suppressed.
* [STRING]    `drug_and_nutritional_suppression_indicator`
  - A flag indicating the reason the utilization, charge and payment subtotal information for Drug and Nutritional products is suppressed. “*” = Primary suppressed due to Number of Drug and Nutritional Products Claims between 1 and 10. “#” = Counter suppressed because the claim count from at least one of the corresponding claim count categories (Number of Durable Medical Equipment Claims or Number of Orthotic and Prosthetic Claims) is between 1 and 10. Counter suppression prevents the disclosure of a primary suppressed value when all categories sum to the total value.
* [INTEGER]   `number_of_drug_and_nutritional_products_suppliers`
  - Number of suppliers rendering drug and nutritional products/services. A blank indicates the value is suppressed.
* [INTEGER]   `number_of_drug_and_nutritional_products_hcpcs`
  - Total number of unique drug and nutritional product HCPCS codes billed by suppliers and ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `number_of_drug_and_nutritional_products_beneficiaries`
  - Total number of unique beneficiaries associated with drug and nutritional product claims submitted by suppliers and ordered by the referring provider. Beneficiary counts fewer than 11 have been suppressed to protect the privacy of Medicare beneficiaries. A blank indicates the value is suppressed.
* [INTEGER]   `number_of_drug_and_nutritional_products_claims`
  - Total number of drug and nutritional product claims submitted by suppliers, reflecting services ordered by the referring provider. A blank indicates the value is suppressed.
* [INTEGER]   `number_of_drug_and_nutritional_products_services`
  - Total drug and nutritional products/services rendered by suppliers and ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `drug_and_nutritional_products_submitted_charges`
  - The total charges that suppliers submitted for drug and nutritional products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `drug_and_nutritional_products_medicare_allowed_amount`
  - The Medicare allowed amount for drug and nutritional products/services ordered by the referring provider. This figure is the sum of the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying. A blank indicates the value is suppressed.
* [FLOAT]     `drug_and_nutritional_products_medicare_payment_amount`
  - Amount that Medicare paid suppliers after deductible and coinsurance amounts have been deducted for drug and nutritional line item products/services ordered by the referring provider. A blank indicates the value is suppressed.
* [FLOAT]     `drug_and_nutritional_products_medicare_standard_payment_amount`
  - Amount that Medicare paid after beneficiary deductible and coinsurance amounts have been deducted for all supplier’s drug and nutritional line item products/services and after standardization of the Medicare payment has been applied.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
