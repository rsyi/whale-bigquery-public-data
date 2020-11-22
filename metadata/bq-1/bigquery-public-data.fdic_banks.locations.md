# `fdic_banks.locations`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `fdic_certificate_number`
  - A unique number assigned by the FDIC used to identify institutions and for the issuance of insurance certificates.
* [STRING]    `institution_name`
  - The legal name of the institution.
* [STRING]    `branch_name`
  - Name of the branch.
* [STRING]    `branch_number`
  - The branch's corresponding office number.
* [BOOLEAN]   `main_office`
  - The main office for the institution.
* [STRING]    `branch_address`
  - Street address at which the branch is physically located.
* [STRING]    `branch_city`
  - City in which branch is physically located.
* [STRING]    `zip_code`
  - The first five digits of the full postal zip code representing physical location of the branch.
* [STRING]    `branch_county`
  - County where the branch is physically located.
* [STRING]    `county_fips_code`
  - A five digit number representing the state and county in which the institution is physically located.  The first two digits represent the FIPS state numeric code and the last three digits represent the FIPS county numeric code.
* [STRING]    `state`
  - State abbreviation in which the branch is physically located. The FDIC Act defines state as any State of the United States, the District of Columbia, and any territory of the United States, Puerto Rico, Guam, American Samoa, the Trust Territory of the Pacific Islands, the Virgin Island, and the Northern Mariana Islands.
* [STRING]    `state_name`
  - State in which the  branch is physically located. The FDIC Act defines state as any State of the United States, the District of Columbia, and any territory of the United States, Puerto Rico, Guam, American Samoa, the Trust Territory of the Pacific Islands, the Virgin Island, and the Northern Mariana Islands.
* [STRING]    `institution_class`
  - "A classification code assigned by the FDIC based on the institution's charter type (commercial bank or savings institution), charter agent (state or federal), Federal Reserve membership status (Fed member, Fed nonmember) and its primary federal regulator (state chartered institutions are subject to both federal and state supervision). N -Commercial bank, national (federal) charter and Fed member, supervised by the Office of the Comptroller of the Currency (OCC) NM -Commercial bank, state charter and Fed nonmember, supervised by the FDIC OI - Insured U.S. branch of a foreign chartered institution (IBA) SA - Savings associations, state or federal charter, supervised by the Office of Thrift Supervision (OTS) SB - Savings banks, state charter, supervised by the FDIC SM - Commercial bank, state charter and Fed member, supervised by the Federal Reserve (FRB)"
* [STRING]    `cbsa_fips_code`
  - Numeric code of the Core Based Statistical Area (CBSA) as defined by the US Census Bureau Office of Management and Budget.
* [STRING]    `cbsa_name`
  - Name of the Core Based Statistical Area (CBSA) as defined by the US Census Bureau Office of Management and Budget.
* [BOOLEAN]   `cbsa_division_flag`
  - A flag indicating member of a Core Based Statistical Division as defined by the US Census Bureau Office of Management and Budget.
* [INTEGER]   `cbsa_division_fips_code`
  - Numeric code of the Core Based Statistical Division as defined by the US Census Bureau Office of Management and Budget.
* [STRING]    `cbsa_division_name`
  - Name of the Core Based Statistical Division as defined by the US Census Bureau Office of Management and Budget.
* [BOOLEAN]   `cbsa_metro_flag`
  - A flag used to indicate whether an branch is in a Metropolitan Statistical Area as defined by the US Census Bureau Office of Management and Budget
* [STRING]    `cbsa_metro_fips_code`
  - Numeric code of the Metropolitan Statistical Area as defined by the US Census Bureau Office of Management and Budget
* [STRING]    `cbsa_metro_name`
  - Name of the Metropolitan Statistical Area as defined by the US Census Bureau Office of Management and Budget
* [BOOLEAN]   `cbsa_micro_flag`
  - A flag (1=Yes) used to indicate whether an branch is in a Micropolitan Statistical Area as defined by the US Census Bureau Office of Management and Budget
* [BOOLEAN]   `csa_flag`
  - Flag (1=Yes) indicating member of a Combined Statistical Area (CSA) as defined by the US Census Bureau Office of Management and Budget
* [STRING]    `csa_fips_code`
  - Numeric code of the Combined Statistical Area (CSA) as defined by the US Census Bureau Office of Management and Budget
* [STRING]    `csa_name`
  - Name of the Combined Statistical Area (CSA) as defined by the US Census Bureau Office of Management and Budget
* [DATE]      `date_established`
  - The date on which the branch began operations.
* [STRING]    `fdic_uninum`
  - This is the FDIC UNINUM of the institution that owns the branch. A UNINUM is a unique sequentially number added to the FDIC database for both banks and branches. There is no pattern imbedded within the number. The FI_UNINUM is updated with every merger or purchase of branches to reflect the most current owner.
* [DATE]      `last_updated`
  - The day the institution information was updated.
* [STRING]    `service_type`
  - "Define the various types of offices of FDIC-insured institutions. 11 -  Full Service Brick and Mortar Office 12 -  Full Service Retail Office 13 -  Full Service Cyber Office 14 -  Full Service Mobile Office 15 -  Full Service Home/Phone Banking 16 -  Full Service Seasonal Office 21 -  Limited Service Administrative Office 22 -  Limited Service Military Facility 23 -  Limited Service Facility Office 24 -  Limited Service Loan Production Office 25 -  Limited Service Consumer Credit Office 26 -  Limited Service Contractual Office 27 -  Limited Service Messenger Office 28 -  Limited Service Retail Office 29 -  Limited Service Mobile Office 30 -  Limited Service Trust Office"
* [STRING]    `branch_fdic_uninum`
  - Unique Identification Number for a Branch Office as assigned by the FDIC

-------------------------------------------------------------------------------
*Do not make edits above this line.*
