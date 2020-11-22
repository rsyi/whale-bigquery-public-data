# `sdoh_hud_housing.2017_lihtc_database_hud`
`bq-1` | `bigquery-public-data`
This is a list of all of the housing units that are covered by HUDs LITC program from the mid-1980s through 2017.

## Column details
* [STRING]    `hud_id`
  - Unique Project Identifier for the Database — characters 1-3: Allocating agency code (see table below) digits 4-7: Year placed in service (0000 or 0001 if unknown or missing) digit 8: Number of years property was added to database after initial request, e.g. 1= 2015 property reported to HUD with 2016 update (0 if property added to DB prior to 2015 update) digits 9-11: Record number within allocating agency and year placed in service;* Note: Beginning with the 2015 database update, digit 8 (see variable definition) was added to HUD_ID.
* [STRING]    `project`
  - Project name
* [STRING]    `proj_add`
  - Project street address
* [STRING]    `proj_cty`
  - Project city
* [STRING]    `proj_st`
  - Project state
* [STRING]    `proj_zip`
  - Project zip
* [STRING]    `state_id`
  - State-defined Project ID
* [STRING]    `contact`
  - Owner or owner's contact
* [STRING]    `company`
  - Name of contact company
* [STRING]    `co_add`
  - Contact's business address
* [STRING]    `co_cty`
  - Contact's city
* [STRING]    `co_st`
  - Contact's state
* [STRING]    `co_zip`
  - Contact's zip
* [STRING]    `co_tel`
  - Contact's telephone
* [FLOAT]     `latitude`
  - Latitude: Degrees Decimal
* [FLOAT]     `longitude`
  - Longitude: Negative Degrees Decimal -- GIS Mapping Convention
* [INTEGER]   `reg`
  - Census Region; 1=Northeast 2=Midwest 3=South 4=West
* [STRING]    `msa`
  - MSA/PMSA Number (1999)
* [STRING]    `cbsa`
  - Core Based Statistical Area (CBSA) Lowest Level Code
* [STRING]    `placece`
  - Census Place Code (1990)
* [STRING]    `placefp`
  - FIPS Place Code (2000)
* [STRING]    `place2010`
  - FIPS Place Code (2010)
* [STRING]    `cosubcur`
  - County Subdivision Code (Minor Civil Division/ Census Civil Division)
* [STRING]    `fips1990`
  - Unique 1990 Census Tract ID -- digits 1-2: State FIPS Code digits 3-5: County FIPS Code digits 6-11: Census Tract Number (no decimal point included)
* [STRING]    `st1990`
  - 1990 State FIPS Code
* [STRING]    `cnty1990`
  - 1990 County FIPS Code
* [STRING]    `trct1990`
  - 1990 Census Tract Number
* [STRING]    `fips2000`
  - Unique 2000 Census Tract ID -- digits 1-2: State FIPS Code digits 3-5: County FIPS Code digits 6-11: Census Tract Number (no decimal point included)
* [STRING]    `st2000`
  - 2000 State FIPS Code
* [STRING]    `cnty2000`
  - 2000 County FIPS Code
* [STRING]    `trct2000`
  - 2000 Census Tract Number
* [STRING]    `fips2010`
  - Unique 2010 Census Tract: Digits 1-2: State FIPS Code Digits 3-5: County FIPS Code Digits 6-11: Census Tract Number (decimal point excluded)
* [STRING]    `st2010`
  - 2010 State FIPS Code
* [STRING]    `cnty2010`
  - 2010 County FIPS Code
* [STRING]    `trct2010`
  - 2010 Census Tract Number
* [INTEGER]   `scattered_site_cd`
  - Scattered Site Property; 1=Yes 2=No
* [INTEGER]   `resyndication_cd`
  - Resyndicated Property; 1=Yes 2=No
* [FLOAT]     `allocamt`
  - Annual dollar amount of tax credits allocated
* [INTEGER]   `n_units`
  - Total number of units
* [INTEGER]   `li_units`
  - Total number of low income units
* [INTEGER]   `n_0br`
  - Number of efficiencies
* [INTEGER]   `n_1br`
  - Number of 1-bedroom units
* [INTEGER]   `n_2br`
  - Number of 2-bedroom units
* [INTEGER]   `n_3br`
  - Number of 3-bedroom units
* [INTEGER]   `n_4br`
  - Number of 4-bedroom units
* [INTEGER]   `inc_ceil`
  - Elected rent/income ceiling for low income units;1=50% AMGI 2=60% AMGI 3=Not Reported
* [INTEGER]   `low_ceil`
  - Units set aside with rents lower than elected rent/income ceiling;1=Yes 2=No
* [INTEGER]   `ceilunit`
  - Number of units set aside with rents lower than elected rent/income ceiling
* [STRING]    `yr_pis`
  - Year placed in service; 1987-2016=year placed in service 8888=placed in service status not confirmed 9999=placed in service status confirmed, but placed in service year missing
* [STRING]    `yr_alloc`
  - Allocation year
* [INTEGER]   `non_prof`
  - Non-profit sponsor;1=Yes 2=No
* [INTEGER]   `basis`
  - Increase in eligible basis; 1=Yes 2=No
* [INTEGER]   `bond`
  - Tax-exempt bond received; 1=Yes 2=No
* [INTEGER]   `mff_ra`
  - HUD Multi-Family financing/rental assistance; 1=Yes 2=No
* [INTEGER]   `fmha_514`
  - FmHA (RHS) Section 514 loan; 1=Yes 2=No
* [INTEGER]   `fmha_515`
  - FmHA (RHS) Section 515 loan; 1=Yes 2=No
* [INTEGER]   `fmha_538`
  - FmHA (RHS) Section 538 loan; 1=Yes 2=No
* [INTEGER]   `home`
  - HOME Investment Partnership Program funds; 1=Yes 2=No
* [INTEGER]   `home_amt`
  - Dollar amount of HOME funds
* [INTEGER]   `tcap`
  - Tax Credit Assistance Program (TCAP) funds;1=Yes 2=No
* [FLOAT]     `tcap_amt`
  - TCAP Amount
* [INTEGER]   `cdbg`
  - Community Development Block Grant (CDBG) funds;1=Yes 2=No
* [INTEGER]   `cdbg_amt`
  - Dollar amount of CDBG funds
* [INTEGER]   `fha`
  - FHA-insured loan;1=Yes 2=No
* [INTEGER]   `hopevi`
  - Forms part of a HOPEVI development;1=Yes 2=No
* [INTEGER]   `hpvi_amt`
  - Dollar amount of HOPEVI funds for development or building costs
* [INTEGER]   `tcep`
  - Tax Credit Exchange Program (TCEP) Funds;1=Yes 2=No
* [FLOAT]     `tcep_amt`
  - Dollar amount of TCEP funds
* [INTEGER]   `rentassist`
  - Federal or state project-based rental assistance contract;1=Federal 2=State 3=Both Federal and State 4=Neither 5=Unknown whether Federal or State
* [INTEGER]   `trgt_pop`
  - Targets a specific population with specialized services or facilities;1=Yes 2=No
* [STRING]    `trgt_fam`
  - Targets a specific population – families;1=Yes 2=No 0 or blank = Not indicated
* [STRING]    `trgt_eld`
  - Targets a specific population – elderly;1=Yes 2=No 0 or blank = Not indicated
* [STRING]    `trgt_dis`
  - Targets a specific population – disabled;1=Yes 2=No 0 or blank = Not indicated
* [STRING]    `trgt_hml`
  - Targets a specific population – homeless;1=Yes 2=No 0 or blank = Not indicated
* [STRING]    `trgt_other`
  - Targets a specific population – other;1=Yes 2=No 0 or blank = Not indicated
* [STRING]    `trgt_spc`
  - Targets a specific population – other as specified
* [INTEGER]   `type`
  - Type of construction;1=New construction 2=Acquisition and Rehab 3=Both new construction and A/R 4=Existing
* [INTEGER]   `credit`
  - Type of credit percentage;1=30 percent present value 2=70 percent present value 3=Both 4=TCEP only
* [INTEGER]   `n_unitsr`
  - Total number of units or if total units missing or inconsistent, total low-income units
* [INTEGER]   `li_unitr`
  - Total number of low income units or if total low-income units missing, total units
* [INTEGER]   `metro`
  - Is the census tract metro or non-metro?;1=Metro/Non-Central City 2=Metro/Central City 3=Non-Metro
* [INTEGER]   `dda`
  - Is the census tract in a difficult development area? (DDA status is based on placed in service year.);0=Not in DDA 1=In Metro DDA 2=In Non-Metro DDA 3=In Metro GO Zone DDA 4=In Non-Metro GO Zone DDA
* [INTEGER]   `qct`
  - Is the census tract a qualified census tract? (For projects placed in service prior to 2003, QCT is based on 1990 Census tract. For projects placed in service since 2003, QCT is based on 2000 Census tract.);1=In a qualified tract 2=Not in a qualified tract
* [STRING]    `nonprog`
  - No longer monitored for LIHTC program due to expired use or other reason (Status of no longer being monitored for the LIHTC Program is indicated for projects as specified by the allocating agency. This does not indicate whether or not a project remains affordable to low income populations.); 1=Yes
* [STRING]    `datanote`
  - Notes about data record changes processed for database update.
* [STRING]    `record_status`
  - Record Status compared to previous version of LIHTC database;N=New U=Updated X=Existing (Unchanged from previous DB version)
* [FLOAT]     `x`
* [FLOAT]     `y`
* [FLOAT]     `z`
* [INTEGER]   `yrmisflg`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
