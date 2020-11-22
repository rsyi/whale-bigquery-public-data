# `sec_quarterly_financials.submission`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [INTEGER]   `central_index_key`
  - Central Index Key (CIK). Ten digit number assigned by the Commission to each registrant that submits filings. central_index_key: [cik]
* [STRING]    `company_name`
  - Name of registrant. This corresponds to the name of the legal entity as recorded in EDGAR as of the filing date. company_name: [name]
* [STRING]    `sic`
  - Standard Industrial Classification (SIC). Four digit code assigned by the Commission as of the filing date, indicating the registrant's type of business.
* [STRING]    `countryba`
  - The ISO 3166-1 country of the registrant's business address.
* [STRING]    `stprba`
  - The state or province of the registrant's business address, if field countryba is US or CA.
* [STRING]    `cityba`
  - The city of the registrant's business address.
* [STRING]    `zipba`
  - The zip code of the registrant's business address.
* [STRING]    `ba_street1`
  - The first line of the street of the registrant's business address. ba_street1: [bas1]
* [STRING]    `ba_street2`
  - The second line of the street of the registrant's business address. ba_street2: [bas2]
* [STRING]    `ba_phone`
  - The phone number of the registrant's business address. ba_phone: [baph]
* [STRING]    `countryma`
  - The ISO 3166-1 country of the registrant's mailing address.
* [STRING]    `stprma`
  - The state or province of the registrant's mailing address, if field countryma is US or CA.
* [STRING]    `cityma`
  - The city of the registrant's mailing address.
* [STRING]    `zipma`
  - The zip code of the registrant's mailing address.
* [STRING]    `ma_street1`
  - The first line of the street of the registrant's mailing address. ma_street1: [mas1]
* [STRING]    `ma_street2`
  - The second line of the street of the registrant's mailing address. ma_street2: [mas2]
* [STRING]    `country_inc`
  - The country of incorporation for the registrant. country_inc: [countryinc]
* [STRING]    `state_province_inc`
  - The state or province of incorporation for the registrant, if countryinc is US or CA, otherwise NULL. state_province_inc: [stprinc]
* [STRING]    `ein`
  - Employee Identification Number, 9 digit identification number assigned by the Internal Revenue Service to business entities operating in the United States.
* [STRING]    `former_name`
  - Most recent former name of the registrant, if any. former_name: [former]
* [INTEGER]   `date_changed`
  - Date of change from the former name, if any. date_changed: [changed]
* [STRING]    `filer_status`
  - Filer status with the Commission at the time of submission: 1-LAF=Large Accelerated, 2-ACC=Accelerated, 3-SRA=Smaller Reporting Accelerated, 4-NON=Non-Accelerated, 5-SML=Smaller Reporting Filer, NULL=not assigned. filer_status: [afs]
* [BOOLEAN]   `well_known_seasoned_issuer`
  - Well Known Seasoned Issuer (WKSI). An issuer that meets specific Commission requirements at some point during a 60-day period preceding the date the issuer satisfies its obligation to update its shelf registration statement. well_known_seasoned_issuer: [wksi]
* [STRING]    `fiscal_year_end`
  - Fiscal Year End Date. fiscal_year_end: [fye]
* [STRING]    `form`
  - The submission type of the registrant's filing.
* [INTEGER]   `period`
  - Balance Sheet Date.
* [INTEGER]   `fiscal_year`
  - Fiscal Year Focus (as defined in EFM Ch. 6). fiscal_year: [fy]
* [STRING]    `fiscal_period_focus`
  - Fiscal Period Focus (as defined in EFM Ch. 6) within Fiscal Year. The 10-Q for the 1st, 2nd and 3rd quarters would have a fiscal period focus of Q1, Q2 (or H1), and Q3 (or M9) respectively, and a 10-K would have a fiscal period focus of FY. fiscal_period_focus: [fp]
* [INTEGER]   `date_filed`
  - The date of the registrant's filing with the Commission. date_filed: [filed]
* [TIMESTAMP] `date_accepted`
  - The acceptance date and time of the registrant's filing with the Commission. Filings accepted after 5:30pm EST are considered filed on the following business day. date_accepted: [accepted]
* [BOOLEAN]   `has_previous_report`
  - Previous Report.  TRUE indicates that the submission information was subsequently amended prior to the end cutoff date of the data set. "has_previous_report: [prevrpt]
* [BOOLEAN]   `has_required_detail`
  - TRUE indicates that the XBRL submission contains quantitative disclosures within the footnotes and schedules at the required detail level (e.g., each amount). has_required_detail: [detail]
* [STRING]    `instance`
  - The name of the submitted XBRL Instance Document (EX-101.INS) type data file. The name often begins with the company ticker symbol.
* [INTEGER]   `num_ciks`
  - Number of Central Index Keys (CIK) of registrants (i.e., business units) included in the consolidating entity's submitted filing. num_ciks: [nciks]
* [STRING]    `additional_ciks`
  - Additional CIKs of co-registrants included in a consolidating entity's EDGAR submission, separated by spaces. If there are no other co-registrants (i.e., nciks = 1), the value of aciks is NULL. For a very small number of filers, the list of co-registrants is too long to fit in the field. Where this is the case, PARTIAL will appear at the end of the list indicating that not all co-registrants' CIKs are included in the field; users should refer to the complete submission file for all CIK information. additional_ciks: [aciks]
* [FLOAT]     `public_float_usd`
  - Public float, in USD, if provided in this submission. public_float_usd: [pubfloatusd]
* [INTEGER]   `float_date`
  - Date on which the public float was measured by the filer. float_date: [floatdate]
* [STRING]    `float_axis`
  - If the public float value was computed by summing across several tagged values, this indicates the nature of the summation. float_axis: [floataxis]
* [INTEGER]   `float_terms`
  - If the public float was computed, the number of terms in the summation. float_terms: [floatmems]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
