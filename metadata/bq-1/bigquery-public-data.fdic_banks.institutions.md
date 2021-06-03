# `fdic_banks.institutions`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `fdic_certificate_number`
  - A unique number assigned by the FDIC used to identify institutions and for the issuance of insurance certificates.
* [STRING]    `institution_name`
  - The legal name of the institution.
* [STRING]    `state_name`
  - State in which the the institution is physically located. The FDIC Act defines state as any State of the United States, the District of Columbia, and any territory of the United States, Puerto Rico, Guam, American Samoa, the Trust Territory of the Pacific Islands, the Virgin Island, and the Northern Mariana Islands.
* [STRING]    `fdic_id`
  - FDIC's unique identifier number for holding companies, banks, branches and nondeposit subsidiaries.
* [STRING]    `docket`
  - An identification number assigned to institutions chartered by the office of thrift supervision or members of the federal housing finance board (FHFB) and formerly by the federal home loan bank board.  The value is "00000" for institutions not members of the FHFB.
* [BOOLEAN]   `active`
  - Institutions that are currently open and insured by the FDIC
* [STRING]    `address`
  - Street address at which the institution or one of its branches is physically located.
* [INTEGER]   `total_assets`
  - The sum of all assets owned by the institution including cash, loans, securities, bank premises and other assets. This total does not include off-balance-sheet accounts.
* [STRING]    `bank_charter_class`
  - A classification code assigned by the FDIC based on the institution's charter type (commercial bank or savings institution), charter agent (state or federal), Federal Reserve membership status (Fed member, Fed nonmember)and its primary federal regulator (state chartered institutions are subject to both federal and state supervision).   N = commercial bank, national (federal) charter and Fed member, supervised by the Office of the Comptroller of the Currency (OCC)  SM = commercial bank, state charter and Fed member, supervised by the Federal Reserve (FRB)  NM = commercial bank, state charter and Fed nonmember, supervised by the FDIC  SB = savings banks, state charter, supervised by the FDIC  SA = savings associations, state or federal charter, supervised by the Office of Thrift Supervision (OTS)  OI = insured U.S. branch of a foreign chartered institution (IBA)
* [STRING]    `change_code_1`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_2`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_3`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_4`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_5`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_6`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_7`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_8`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_9`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_10`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_11`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_12`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_13`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_14`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `change_code_15`
  - FDIC code used to signify a structural event relating to an institution.  The definitions of the codes are available in the `bigquery-public-data.fdic_banks.change_codes`
* [STRING]    `occ_charter`
  - A unique number assigned by the Office of the Comptroller of the Currency (OCC) used to identify institutions that it has chartered and regulates (i.e. national  banks).
* [STRING]    `chartering_agency`
  - All Chartering Agencies - State and Federal  Comptroller of the Currency - Chartering authority for nationally chartered commercial banks and for federally chartered savings associations (The Office of Thrift Supervision (OTS) before 7/21/11)  State (includes U.S. Territories) - Chartering authority for institutions that are not chartered by the OCC or OTS
* [BOOLEAN]   `conservatorship`
  - A flag that indicates if an institution is being operated in government conservatorship.
* [STRING]    `city`
  - City in which an institution's headquarters or one of its branches is physically located.
* [STRING]    `category_code`
  - Numeric code which identifies the major and minor categories of an institution.  Definitions of these are available in`bigquery-public-data.fdic_banks.category_code`
* [STRING]    `county_fips_code`
  - A five digit number representing the state and county in which the institution is physically located.  The first two digits represent the FIPS state numeric code and the last three digits represent the FIPS county numeric code.
* [STRING]    `county_name`
  - County where the institution is physically located (abbreviated if the county name exceeds 16 characters).
* [DATE]      `established_date`
  - The date on which the institution began operations.
* [DATE]      `last_updated`
  - Date the data was last updated
* [DATE]      `effective_date`
  - Effective Start Date of the data contained in this row.
* [DATE]      `end_effective_date`
  - The date that ends or closes out the last structural event relating to an institution. For closed institutions, this date represents the day that the institution became inactive.
* [BOOLEAN]   `denovo_institute`
  - A flag used to indicate whether an institution is a new institution (not a recharter). This flag is set quarterly. For instance, if REPDTE is 3/31/98 and DENOVO equals 1, the institution was a denovo during the first quarter of 1998.
* [INTEGER]   `total_deposits`
  - The sum of all deposits including demand deposits, money market deposits, other savings deposits, time deposits and deposits in foreign offices.
* [INTEGER]   `equity_capital`
  - Total equity capital (includes preferred and common stock, surplus and undivided profits).
* [STRING]    `fdic_geo_region`
  - The FDIC Office assigned to the geographic area.  The eight FDIC Regions and their respective states are:    Boston - Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, Vermont  New York - Delaware, District of Columbia, Maryland, New Jersey, New York, Pennsylvania, Puerto Rico, U.S. Virgin Islands  Atlanta - Alabama, Florida, Georgia, North Carolina, South Carolina, Virginia, West Virginia  Memphis - Arkansas, Kentucky, Louisiana, Mississippi, Tennessee  Chicago - Illinois, Indiana, Michigan, Ohio, Wisconsin   Kansas City - Iowa, Kansas, Minnesota, Missouri, Nebraska, North Dakota, South Dakota  Dallas - Colorado, New Mexico, Oklahoma, Texas  San Francisco - Alaska, American Samoa, Arizona, California, Guam, Hawaii, Idaho, Montana, Nevada, Oregon, States of Micronesia, Utah, Washington, Wyoming
* [STRING]    `fdic_supervisory_region`
  - The supervisory FDIC office assigned to the institution.  The eight FDIC Supervisory Regions and their respective states are:    Boston - Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, Vermont  New York - Delaware, District of Columbia, Maryland, New Jersey, New York, Pennsylvania, Puerto Rico, U.S. Virgin Islands  Atlanta - Alabama, Florida, Georgia, North Carolina, South Carolina, Virginia, West Virginia  Memphis - Arkansas, Kentucky, Louisiana, Mississippi, Tennessee  Chicago - Illinois, Indiana, Michigan, Ohio, Wisconsin   Kansas City - Iowa, Kansas, Minnesota, Missouri, Nebraska, North Dakota, South Dakota  Dallas - Colorado, New Mexico, Oklahoma, Texas  San Francisco - Alaska, American Samoa, Arizona, California, Guam, Hawaii, Idaho, Montana, Nevada, Oregon, States of Micronesia, Utah, Washington, Wyoming
* [STRING]    `fdic_supervisory_region_code`
  - "A numeric value associated with the name of an FDIC supervisory region  2 - New York - states: Connecticut, Delaware, Maine, Maryland, Massachusetts, New Hampshire, New Jersey, New York, Pennsylvania, Puerto Rico, Rhode Island, Vermont, Virgin Islands  5 - Atlanta - states: Alabama, Florida, Georgia, North Carolina, South Carolina, Virginia  9 - Chicago - states: Illinois, Indiana, Kentucky, Michigan, Ohio  11 - Kansas City - states: Iowa, Kansas, Minnesota, Missouri, Nebraska, North Dakota, South Dakota  13 - Dallas - states: Arkansas, Colorado, Louisiana, Mississippi, New Mexico, Oklahoma, Tennessee, Texas  14 - San Francisco - states: Alaska, American Samoa, Arizona, California, Federated States of Micronesia, Guam, Hawaii, Idaho, Montana, Nevada, Oregon, Utah, Washington, Wyoming  15 - Washington Office - Division of Risk Management Supervision (RMS)  16 - Washington Office - The Office of Complex Financial Institutions (CFI) "
* [STRING]    `fed_reserve_district`
* [STRING]    `fed_reserve_district_id`
  - A number used to identify the Federal Reserve district in which the institution is located. 01 = Boston,  02 - New York, 03 = Philadelphia,  04 = Cleveland, 05 = Richmond, 06 = Atlanta, 07 = Chicago, 08 - St. Louis, 09 = Minneapolis, 10 - Kansas city, 11 = Dallas, 12 - San Francisco
* [STRING]    `fed_reserve_unique_id`
  - A unique number assigned by the Federal Reserve board as the entity's unique identifier
* [BOOLEAN]   `federal_charter`
  - A flag used to indicate whether the institution is chartered by an agent of the federal government.
* [STRING]    `fdic_field_office`
  - The FDIC Field Office where an institution is physically located.
* [BOOLEAN]   `iba`
  - Includes Bank Insurance Fund insured branches in the U.S. established by banks chartered and headquartered in foreign countries.  These institutions are regulated by one of the three Federal commercial bank regulators and submit financial data to the Federal Reserve.
* [BOOLEAN]   `inactive_flag`
  - Institutions that are currently closed but were once insured by the FDIC.
* [STRING]    `insurance_fund_membership`
  - Deposit Insurance Fund (DIF), Bank Insurance Fund (BIF), Savings Association Insurance Fund (SAIF)
* [STRING]    `secondary_insurance_fund`
  - As a result of the establishment of a single Deposit Insurance Fund (DIF) effective April 1, 2006, the Secondary Insurance fund is no longer applicable. previously both bif and saif bank insurance fund - institutions that are members of the bank insurance fund savings association insurance fund - Institutions that are members of the Savings Association Insurance Fund
* [DATE]      `deposit_insurance_date`
  - The date that an institution obtained federal deposit insurance.
* [BOOLEAN]   `credit_card_institution`
  - Institutions with total loans greater than 50% of total assets and credit card loans greater than 50% of total loans, including loans that have been securitized and sold.
* [BOOLEAN]   `bank_insurance_fund_member`
  - Institutions who are members of the Bank Insurance Fund. As of April 1, 2006 BIF was merged together with the Savings Institution Insurance Fund (SAIF) to create a single Deposit Insurance Fund (DIF).  All FDIC insured BIF member institutions, that are still active or open, are now insured members of DIF.
* [BOOLEAN]   `insured_commercial_bank`
  - Includes commercial banks insured by the FDIC.  These institutions are regulated by one of the three Federal commercial bank regulators (FDIC, Federal Reserve Board, or Office of the Comptroller of the Currency).  They submit financial reports to the Federal Reserve (state member banks) or the FDIC (state non-member banks and national banks).
* [BOOLEAN]   `deposit_insurance_fund_member`
  - "A flag used to indicate whether an institution is insured under the Deposit Insurance Fund (DIF).  As of April 1, 2006 the Bank Insurance Fund (BIF) was merged together with the Savings Institution Insurance Fund (SAIF) to create a single Deposit Insurance Fund (DIF).  All FDIC insured BIF and SAIF member institutions that are still active or open are now insured members of DIF.    False = No, not DIF insured and True = Yes, DIF insured.  Note that institutions that became inactive prior to April 2006 will also have false value.   "
* [BOOLEAN]   `fdic_insured`
  - Includes institutions insured by the FDIC.
* [BOOLEAN]   `saif_insured`
  - Institutions who are members of the Savings Association Insurance Fund. As of April 1, 2006 SAIF was merged together with the Bank Insurance Fund (BIF) to create a single Deposit Insurance Fund (DIF).  All FDIC insured SAIF member institutions, that are still active or open, are now insured members of DIF.
* [BOOLEAN]   `insured_savings_institute`
  - Includes savings institutions insured by the FDIC that operate under state or federal banking codes applicable to thrift institutions.  These institutions are regulated by and submit financial reports to one of two Federal regulators (FDIC or Office of Thrift Supervision).
* [STRING]    `new_cert_number`
  - A new certificate number of an already existing FDIC-insured institution resulting from either a merger or an acquisition.
* [BOOLEAN]   `oakar_institute`
  - A member of one insurance fund that acquired deposits insured by the other fund, where that portion of the buyer's deposits remained insured by, and assessable by, the other fund.
* [STRING]    `ots_region`
  - Prior to 7/21/11, the Office of Thrift Supervision (OTS) Region in which the institution is physically located. The five OTS Regions and their respective states are: Northeast - Connecticut, Delaware, Maine, Massachusetts, New Hampshire, New Jersey, New York, Pennsylvania, Rhode Island, Vermont, West Virginia Southeast - Alabama, District of Columbia, Florida, Georgia, Maryland, North Carolina, Puerto Rico, South Carolina, U.S. Virgin Islands, Virginia Central - Illinois, Indiana, Kentucky, Michigan, Ohio, Tennessee, Wisconsin Midwest - Arkansas, Colorado, Iowa, Kansas, Louisiana, Minnesota, Mississippi, Missouri, Nebraska, New Mexico, North Dakota, Oklahoma, South Dakota, Texas West - Alaska, American Samoa, Arizona, California, Guam, Hawaii, Idaho, Montana, Nevada, States of Micronesia, Oregon, Utah, Washington, Wyoming "
* [DATE]      `last_structural_change`
  - A date field indicating the date that a change to this record was processed. Standard format = "CCYYMMDD" (Length = 8) which has been converted to Month, Day, Year format for display purposes.
* [STRING]    `qbp_region`
  - The Quarterly Banking Profile (QBP) Commercial Bank Region in which the institution is physically located.
* [STRING]    `regulator`
* [DATE]      `report_date`
  - The last day of the financial reporting period selected.
* [DATE]      `reporting_period_end_date`
  - The financial reporting period selected in CCYYMM format.
* [BOOLEAN]   `state_chartered`
  - A flag that indicates if an institution is state chartered.
* [FLOAT]     `return_on_assets`
  - Net income after taxes and extraordinary items (annualized) as a percent of average total assets.
* [FLOAT]     `roa_quarterly`
  - Quarterly net income after taxes and extraordinary items as a percent of average total assets.
* [FLOAT]     `roa_pretax`
  - Annualized pre-tax net income as a percent of average assets. Note: Includes extraordinary items and other adjustments, net of taxes.
* [FLOAT]     `row_pretax_quarterly`
  - Quarterly pre-tax net income as a percent of average assets. Note: Includes extraordinary items and other adjustments, net of taxes.
* [FLOAT]     `return_on_equity`
  - Annualized net income as a percent of average equity on a consolidated basis.     Note: If retained earnings are  negative, the ratio is shown as NA.
* [FLOAT]     `roe_quarterly`
  - Quarterly net income (including gains or losses on securities and extraordinary items) as a percentage of average total equity capital.
* [DATE]      `run_date`
  - The day the institution information was updated.
* [BOOLEAN]   `sasser_institute`
  - OTS supervised savings associations that converted their charter to that of a commercial or savings bank.  Converted associations remain members of the SAIF, but they become subject to supervision by one of the three federal banking agencies. Not Applicable as of March 31, 2006.
* [BOOLEAN]   `law_sasser`
  - A flag associated with OTS supervised savings associations that converted their charter to that of a commercial or savings bank.  Converted associations remain members of the SAIF, but they become subject to supervision by one of the three federal banking agencies. Not Applicable as of March 31, 2006.
* [STRING]    `state`
  - 2 letter postal abbreviation for the state in which the the headquarters are physically located. The FDIC Act defines state as any State of the United States, the District of Columbia, and any territory of the United States, Puerto Rico, Guam, American Samoa, the Trust Territory of the Pacific Islands, the Virgin Island, and the Northern Mariana Islands.
* [STRING]    `state_fips_code`
  - 2 digit FIPS code to uniquely identify the state
* [STRING]    `trade_name_1`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `trade_name_2`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `trade_name_3`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `trade_name_4`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `trade_name_5`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `trade_name_6`
  - Trade name other than the institution's legal name used to identify one of the institution's physical offices at which deposits are accepted or solicited from the public
* [STRING]    `zip_code`
  - The first three, four, or five digits of the full postal zip code representing physical location of the institution or its branch office.
* [STRING]    `occ_district`
  - The Office of the Comptroller of the Currency (OCC) District in which the institution is physically located. The six OCC Districts and their respective states are: Northeast - Connecticut, Delaware, District of Columbia, Maine, Maryland, Massachusetts, New Hampshire, New Jersey, New York, Pennsylvania, Puerto Rico, Rhode Island, Vermont, U.S. Virgin Islands  Southeast - Alabama, Florida, Georgia, Mississippi, North Carolina, South Carolina, Tennessee, Virginia, West Virginia  Central - Illinois, Indiana, Kentucky, Michigan, Ohio, Wisconsin  Midwest - Iowa, Kansas, Minnesota, Missouri, Nebraska, North Dakota, South Dakota  Southwest - Arkansas, Louisiana, New Mexico, Oklahoma, Texas  West - Alaska, American Samoa, Arizona, California, Colorado, Guam, Hawaii, Idaho, Montana, Nevada, Oregon, States of Micronesia, Utah, Washington, Wyoming
* [STRING]    `ultimate_cert_number`
  - The cert number of the last successor or acquirer of the institution
* [BOOLEAN]   `cfpb_supervisory_flag`
  - Indicates secondary supervision by CFPB
* [DATE]      `cfpb_supervisory_start_date`
  - Date the institution began secondary supervision by CFPB
* [DATE]      `cfpb_supervisory_end_date`
  - Date the institution ended supervision by CFPB
* [INTEGER]   `offices_count`
* [STRING]    `parent_fdic_cert`
  - FDIC certificate number of the parent bank or savings institution with which the reported institution;s financial data has been consolidated. Beginning in March 1997, both the Thrift Financial Reports and Call Reports are completed on a fully consolidated basis. Previously, the consolidation of subsidiary depository institutions was prohibited. Now, parent institutions are required to file consolidated reports, while their subsidiary financial institutions are still required to file separate reports. Click on the certificate number to identify the parent bank or thrift.
* [STRING]    `parent_parcert`
  - The PARCERT number identifies the subsidiary institutions parent certificate number. Beginning in March 1997, both the Thrift Financial Reports and Call Reports are completed on a fully consolidated basis. Previously, the consolidation of subsidiary depository institutions was prohibited. Now, parent institutions are required to file consolidated reports, while their subsidiary financial institutions are still required to file separate reports.
* [STRING]    `high_holder_city`
  - City in which the headquarters of the institution's regulatory high holder are physically located.
* [INTEGER]   `total_domestic_deposits`
  - The sum of all domestic office deposits, including demand deposits, money market deposits, other savings deposits and time deposits.
* [BOOLEAN]   `ffiec_call_report_filer`
  - A flag that indicates whether and institution filed an FFIEC 031 Call Report. Commercial banks with domestic and foreign offices are required to file such a report.
* [BOOLEAN]   `holding_company_flag`
  - A flag used to indicate whether an institution is a member of a multibank holding company
* [BOOLEAN]   `ag_lending_flag`
  - A flag used to indicate whether an institution is an agricultural lending institution
* [STRING]    `ownership_type`
  - Banking institutions fall into one of two ownership types, stock or non-stock. An institution which sells stock to raise capital is called a stock institution. It is owned by the shareholders who benefit from profits earned by the institution. A non-stock institution, or mutual institution, is owned and controlled solely by its depositors. A mutual does not issue capital stock.
* [STRING]    `top_holder`
  - Regulatory top holder is assigned by the Federal Reserve Board based on ownership and control percentages. "Note: Information on bank holding companies is only as of quarter-end. Regulatory top holder is any company that directly or indirectly owns, controls or has power to vote 25 percent or more of a bank's or direct holding company's shares or controls in any manner the election of a majority of the directors or trustees of a bank or direct holding company or exercises a controlling influence over the management or policies of a bank or direct holding company. Information on Thrift Holding Companies that own Savings Associations but do not own banks is not currently available in the ID System. Source: Federal Reserve Board National Information Center data base."
* [INTEGER]   `net_income`
  - Net interest income plus total noninterest income plus realized gains (losses) on securities and extraordinary items, less total noninterest expense, loan loss provisions and income taxes.
* [INTEGER]   `quarterly_net_income`
  - Quarterly net interest income plus total noninterest income plus realized gains (losses) on securities and extraordinary items, less total noninterest expense, loan loss provisions and income taxes.
* [INTEGER]   `office_count_domestic`
  - The number of domestic offices (including headquarters) operated by active institutions in the 50 states of the U.S.A.
* [INTEGER]   `office_count_foreign`
  - The number of foreign offices (outside the U.S.) operated by the institution.
* [INTEGER]   `office_count_us_territories`
  - The number of offices operated by an FDIC-insured institution in all commonwealths and terrirtories of the US, along with those in freely associated states under the Compact of Free Association
* [STRING]    `rssd_id`
  - The unique number assigned by the Federal Reserve Board to the regulatory high holding company of the institution.
* [STRING]    `holding_company_state`
  - State location of the regulatory high holding company (either direct or indirect owner).
* [BOOLEAN]   `subchap_s_indicator`
* [STRING]    `trust_powers_status`
  - "A flag used to indicate an institution's Trust Powers Granted status. 0 = No Trust Power Granted 1 = Trust Power Granted Where Trust Power has been granted specific codes are: 00 - Trust powers not know 10 - Full trust powers granted 11 - Full trust powers granted, exercised 12 - Full trust powers granted, not exercised 20 - Limited trust powers granted 21 - Limited trust powers granted, exercised 22 - Limited trust powers granted, not exercised 30 - Trust powers not granted 31 - Trust powers not granted, but exercised "
* [STRING]    `asset_concentration_hierarchy`
  - "Asset Concentration Hierarchy - An indicator of an institution's primary specialization in terms of asset concentration 1 - International Specialization 2 - Agricultural Specialization 3 - Credit-card Specialization  4 - Commercial Lending Specialization  5 - Mortgage Lending Specialization 6 - Consumer Lending SpecializationI 7 - Other Specialized < $1 Billion  8 - All Other < $1 Billion  9 - All Other > $1 Billion"
* [STRING]    `primary_specialization`
  - " Name associated with the numeric indicator (SPECGRP) of an institution's primary specialization in terms of asset concentration: 1 - International Specialization 2 - Agricultural Specialization 3 - Credit-card Specialization  4 - Commercial Lending Specialization  5 - Mortgage Lending Specialization 6 - Consumer Lending SpecializationI 7 - Other Specialized < $1 Billion  8 - All Other < $1 Billion  9 - All Other > $1 Billion"
* [STRING]    `csa_name`
  - "The name associated with the numeric code that the U.S. Census Bureau Office of Management and Budget assigns for the combined statistical area (CSA) per the 2000 standards. If an institution is not defined as a CSA, the value of the field will be blank. For more information see: http://www.census.gov/population/www/estimates/metroarea.html . "
* [STRING]    `csa_fips_code`
  - The numeric code that the U.S. Census Bureau Office of Management and Budget assigns for the combined statistical area (CSA) per the 2000 standards. If an institution is not defined as a CSA, the value of the field will be zero. For more information see: http://www.census.gov/population/www/estimates/metroarea.html .
* [BOOLEAN]   `csa_indicator`
  - A flag used to indicate whether an institution is in a Combined Statistical Area.
* [STRING]    `cbsa_name`
  - The name associated with the numeric code that the U.S. Census Bureau Office of Management and Budget assigns for the CBSA. The 2000 standards provide that each CBSA must contain at least one urban area of 10,000 or more population. Metropolitan and micropolitan statistical areas are two categories of core based statistical areas. If an institution is not defined as a CBSA, the value of the field will be zero. For more information see: http://www.census.gov/population/www/estimates/metroarea.html .
* [STRING]    `cbsa_fips_code`
  - The numeric code that the U.S. Census Bureaus Office of Management and Budget assigns for the CBSA. The 2000 standards provide that each CBSA must contain at least one urban area of 10,000 or more population. Metropolitan and micropolitan statistical areas are two categories of core based statistical areas. If an institution is not defined as a CBSA, the value of the field will be zero. For more information see: http://www.census.gov/population/www/estimates/metroarea.html .
* [BOOLEAN]   `cbsa_metro_flag`
  - A flag used to indicate whether an institution is in a metropolitan statistical area. The US Census bureau office of Management and Budget defines the metropolitan statistical area. A core based statistical area associated with at least one urbanized area that has a population of at least 50,000. The metropolitan statistical area comprises the central county or counties containing the core, plus adjacent outlying counties having a high degree of social and economic integration with the central county as measured through commuting.
* [BOOLEAN]   `cbsa_micro_flag`
  - A flag used to indicate whether an institution is in a micropolitan statistical area. The US Census bureau office of Management and Budget defines the micropolitan statistical area. A core based statistical area associated with at least one urbanized area that has a population of at least 50,000. The micropolitan statistical area comprises the central county or counties containing the core, plus adjacent outlying counties having a high degree of social and economic integration with the central county as measured through commuting.
* [STRING]    `cbsa_division_name`
  - "The name associated with the numeric code given by the US Census Bureau office of Management and Budget (2000 standards) that represents the core based statistical division (CBSADIV). A    metropolitan division is a county or group of counties    within a core based statistical area that contains a core    with a population of at least 2.5 million. A CBSA metropolitan    division consists of one or more main/secondary counties    that represent an employment center or centers, plus    adjacent counties associated with the main county or    counties through commuting ties. If an institution is not defined as a CBSA division the value of the field will be zero."
* [STRING]    `cbsa_division_fips_code`
  - The numeric code given by the US Census Bureau office of Management and Budget that represents the core based statistical division (CBSADIV) under the year 2000 standards. A metropolitan division is a county or group of counties within a core based statistical area that contains a core with a population of at least 2.5 million. A CBSA metropolitan division consists of one or more main/secondary counties that represent an employment center or centers, plus adjacent counties associated with the main county or counties through commuting ties. If an institution is not defined as a CBSA division the value of the field will be zero.
* [BOOLEAN]   `cbsa_division_flag`
  - A flag used to indicate whether an institution is in a CBSA division

-------------------------------------------------------------------------------
*Do not make edits above this line.*
