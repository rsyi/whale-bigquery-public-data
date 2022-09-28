# `world_bank_wdi.country_summary`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `country_code`
  - A short alphabetic or numeric geographical code representing a specific country or area. In April 2016 WDI has adopted the three digit ISO code to identify countries in its databases.
* [STRING]    `short_name`
  - Country name the country's official name as approved by the relevant body (Italy is used as an example): conventional short form (Italy).
* [STRING]    `table_name`
  - Country name the country's name as approved by the relevant body (Italy is used as an example): conventional short form (Republic of Italy).
* [STRING]    `long_name`
  - Country name the country's name as approved by the relevant body (Italy is used as an example): conventional long form (Republic of Italy).
* [STRING]    `two_alpha_code`
  - ISO-2 digit alpha code value of the country. Re: www.iso.org
* [STRING]    `currency_unit`
  - Currency unit (such as the dollar euro peso rupee) issued as a coin or banknote a standard unit of value and a unit of account.
* [STRING]    `special_notes`
  - Country special notes for data and metadata users.
* [STRING]    `region`
  - World Bank region to which a country belongs.
* [STRING]    `income_group`
  - World Bank income group to which a country belongs after the country classification is completed every year.
* [STRING]    `wb_2_code`
  - World Bank 2 digit code value of the country.
* [STRING]    `national_accounts_base_year`
  - Base year is the base or pricing period used for constant price calculations in the country’s national accounts. Price indexes derived from national accounts aggregates such as the implicit deflator for gross domestic product (GDP) express the price level relative to base year prices.
* [STRING]    `national_accounts_reference_year`
  - Reference year is the year in which the local currency constant price series of a country is valued. The reference year is usually the same as the base year used to report the constant price series. However when the constant price data are chain linked the base year is changed annually so the data are rescaled to a specific reference year to provide a consistent time series. When the country has not rescaled following a change in base year World Bank staff rescale the data to maintain a longer historical series. To allow for cross-country comparison and data aggregation constant price data reported in World Development Indicators are rescaled to a common reference year (2010) and currency (U.S. dollars).
* [STRING]    `sna_price_valuation`
  - SNA price valuation shows whether value added in the national accounts is reported at basic prices (B) or producer prices (P). Producer prices include taxes paid by producers and thus tend to overstate the actual value added in production. However value added can be higher at basic prices than at producer prices in countries with high agricultural subsidies.
* [STRING]    `lending_category`
  - World Bank lending category to which a country belongs after the operational guidelines are completed every year.
* [STRING]    `other_groups`
  - Other types of grouping approved by the WDI team.
* [STRING]    `system_of_national_accounts`
  - System of National Accounts identifies whether a country uses the 1968 1993 or 2008 System of National Accounts (SNA). The 2008 SNA is an update of the 1993 SNA and retains its basic theoretical framework.
* [STRING]    `alternative_conversion_factor`
  - Alternative conversion factor identifies the countries and years for which a World Bank–estimated conversion factor has been used in place of the official exchange rate (line rf in the International Monetary Fund’s [IMF] International Financial Statistics). See later in Sources and methods for further discussion of alternative conversion factors.
* [STRING]    `ppp_survey_year`
  - Purchasing power parity (PPP) survey year is the latest available survey year for the International Comparison Program’s estimates of PPPs.
* [STRING]    `balance_of_payments_manual_in_use`
  - Balance of Payments Manual in use refers to the classification system used to compile and report data on balance of payments. 6 refers to the 6th edition of the IMF’s Balance of Payments Manual (2009).
* [STRING]    `external_debt_reporting_status`
  - External debt shows debt reporting status for 2016 data. A indicates that data are as reported P that data are based on reported or collected information but include an element of staff estimation and E that data are World Bank staff estimates.
* [STRING]    `system_of_trade`
  - System of trade refers to the United Nations general trade system (G) or special trade system (S). Under the general trade system goods entering directly for domestic consumption and goods entered into customs storage are recorded as imports at arrival. Under the special trade system goods are recorded as imports when declared for domestic consumption whether at time of entry or on withdrawal from customs storage.
* [STRING]    `government_accounting_concept`
  - Government finance accounting concept is the accounting basis for reporting central government financial data. For most countries government finance data have been consolidated (C) into one set of accounts capturing all central government fiscal activities. Budgetary central government accounts (B) exclude some central government units.
* [STRING]    `imf_data_dissemination_standard`
  - IMF data dissemination standard shows the countries that subscribe to the IMF’s Special Data Dissemination Standard (S) or Enhanced General Data Dissemination System (e-GDDS). S refers to countries that subscribe to the SDDS and have posted data on the Dissemination Standards Bulletin Board at http://dsbb.imf.org. S+ countries must observe additional coverage periodicity and timeliness requirements. e-G refers to countries that subscribe to the e-GDDS.
* [STRING]    `latest_population_census`
  - Latest population census shows the most recent year in which a census was conducted and in which at least preliminary results have been released. The preliminary results from the very recent censuses could be reflected in timely revisions if basic data are available such as population by age and sex as well as the detailed definition of counting coverage and completeness.
* [STRING]    `latest_household_survey`
  - Latest demographic education or health household survey indicates the household surveys used to compile the demographic education and health data. Detailed information on each survey is provided through the following links:  AIDS Indicator Survey Demographic and Health Survey Health Issues Survey and Malaria Indicator Survey - www.dhsprogram.com; Living Standards Measurement Study -  www.worldbank.org/lsms; Multiple Indicator Cluster Survey - http://mics.unicef.org; Reproductive Health Survey -  www.cdc.gov/reproductivehealth; World Health Survey is available at - www.who.int/healthinfo/survey/en.
* [STRING]    `source_of_most_recent_income_and_expenditure_data`
  - Source of most recent income and expenditure data shows household surveys that collect income and expenditure data. Names and detailed information on household surveys can be found on the website of the International Household Survey Network (www.surveynetwork.org). Core Welfare Indicator Questionnaire Surveys (CWIQ) developed by the World Bank measure changes in key social indicators for different population groups—specifically indicators of access utilization and satisfaction with core social and economic services. Expenditure survey/budget surveys (ES/BS) collect detailed information on household consumption as well as on general demographic social and economic characteristics. Integrated household surveys (IHS) collect detailed information on a wide variety of topics including health education economic activities housing and utilities.
* [STRING]    `vital_registration_complete`
  - Vital registration complete identifies countries that report at least 90 percent complete registries of vital (birth and death) statistics to the United Nations Statistics Division and are reported in its Population and Vital Statistics Reports. Countries with complete vital statistics registries may have more accurate and more timely demographic indicators than other countries.
* [STRING]    `latest_agricultural_census`
  - Latest agricultural census shows the most recent year in which an agricultural census was conducted or planned to be conducted as reported to the Food and Agriculture Organization.
* [STRING]    `latest_industrial_data`
  - Latest industrial data show the most recent year for which manufacturing value added data at the three-digit level of the International Standard Industrial Classification (revision 2 or 3) are available in the United Nations Industrial Development Organization database.
* [STRING]    `latest_trade_data`
  - Latest trade data show the most recent year for which structure of merchandise trade data from the United Nations Statistics Division’s Commodity Trade (Comtrade) database are available.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
