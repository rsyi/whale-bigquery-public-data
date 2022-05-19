# `covid19_govt_response.oxford_policy_tracker`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `country_name`
  - Name of the country
* [STRING]    `alpha_3_code`
  - 3-letter alpha code abbreviation of the country/region. See `bigquery-public-data.utility_us.country_code_iso` for more details
* [STRING]    `region_name`
  - Name of the region within the country
* [STRING]    `region_code`
  - Code of the region within the country
* [DATE]      `date`
  - Date of the measured policy action status
* [STRING]    `school_closing`
  - C1 - Ordinal scale record closings of schools and universities; 0 - No measures 1 - recommend closing 2 - Require closing (only some levels or categories eg just high school or just public schools) 3 - Require closing all levels No data - blank
* [STRING]    `school_closing_flag`
  - Are C1 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `school_closing_notes`
  - Additional details about C1 policy actions
* [STRING]    `workplace_closing`
  - C2 - Ordinal scale record closings of workplace; 0 - No measures 1 - recommend closing (or work from home) 2 - require closing (or work from home) for some sectors or categories of workers 3 - require closing (or work from home) all-but-essential workplaces (eg grocery stores doctors) No data - blank
* [STRING]    `workplace_closing_flag`
  - Are C2 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `workplace_closing_notes`
  - Additional details about C2 policy actions
* [STRING]    `cancel_public_events`
  - C3 - Ordinal scale record cancellations of public events;0- No measures 1 - Recommend cancelling 2 - Require cancelling No data - blank
* [STRING]    `cancel_public_events_flag`
  - Are C3 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `cancel_public_events_notes`
  - Additional details about C3 policy actions
* [STRING]    `restrictions_on_gatherings`
  - C4 - Ordinal scale to record the cut-off size for bans on private gatherings;  0 - No restrictions 1 - Restrictions on very large gatherings (the limit is above 1000 people) 2 - Restrictions on gatherings between 100-1000 people 3 - Restrictions on gatherings between 10-100 people 4 - Restrictions on gatherings of less than 10 people No data - blank
* [STRING]    `restrictions_on_gatherings_flag`
  - Are C4 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `restrictions_on_gatherings_notes`
  - Additional details about C4 policy actions
* [STRING]    `close_public_transit`
  - C5 - Ordinal scale to record closing of public transportation; 0 - No measures 1 - Recommend closing (or significantly reduce volume/route/means of transport available) 2 - Require closing (or prohibit most citizens from using it)
* [STRING]    `close_public_transit_flag`
  - Are C5 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `close_public_transit_notes`
  - Additional details about C5 policy actions
* [STRING]    `stay_at_home_requirements`
  - C6 - Ordinal scale record of orders to “shelter-in- place” and otherwise confine to home.
* [STRING]    `stay_at_home_requirements_flag`
  - Are C6 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank"\
* [STRING]    `stay_at_home_requirements_notes`
  - Additional details about C6 policy actions
* [STRING]    `restrictions_on_internal_movement`
  - C7 - Ordinal scale of restrictions on internal movement;  0 - No measures 1 - Recommend closing (or significantly reduce volume/route/means of transport) 2 - Require closing (or prohibit most people from using it)
* [STRING]    `restrictions_on_internal_movement_flag`
  - Are C7 actions targeted at specific areas or general:0 - Targeted 1- General No data - blank
* [STRING]    `restrictions_on_internal_movement_notes`
  - Additional details about C7 policy actions
* [STRING]    `international_travel_controls`
  - C8 - Ordinal scale record of restrictions on international travel; 0 - No measures 1 - Screening 2 - Quarantine arrivals from high-risk regions 3 - Ban on high-risk regions 4 - Total border closure No data - blank
* [STRING]    `international_travel_controls_notes`
  - Additional details about C8 policy actions
* [STRING]    `income_support`
  - E1 - Ordinal scale record if the government is covering the salaries or providing direct cash payments universal basic income or similar of people who lose their jobs or cannot work. (Includes payments to firms if explicitly linked to payroll/ salaries)
* [STRING]    `income_support_flag`
  - Sector scope of E1 actions;  0 - formal sector workers only 1 - transfers to informal sector workers too No data - blank
* [STRING]    `income_support_notes`
  - Additional details about E1 policy actions
* [STRING]    `debt_contract_relief`
  - E2 - Record if govt. is freezing financial obligations (eg stopping loan repayments preventing services like water from stopping or banning evictions)
* [STRING]    `debt_contract_relief_notes`
  - Additional details about E2 policy actions
* [FLOAT]     `fiscal_measures`
  - E3 - What economic stimulus policies are adopted (in USD); Record monetary value USD of fiscal stimuli including spending or tax cuts NOT included in S10 (see below) -If none enter 0 No data - blank Please use the exchange rate of the date you are coding not the current date.
* [STRING]    `fiscal_measures_notes`
  - Additional details about E3 policy actions
* [FLOAT]     `international_support`
  - E4 - Announced offers of COVID-19 related aid spending to other countries (in USD);  Record monetary value announced if additional to previously announced spending -if none enter 0 No data - blank Please use the exchange rate of the date you are coding not the current date.
* [STRING]    `international_support_notes`
  - Additional details about E4 policy actions
* [STRING]    `public_information_campaigns`
  - H1 - Ordinal scale record presence of public info campaigns;  0 -No COVID-19 public information campaign 1 - public officials urging caution about COVID-19 2 - coordinated public information campaign (e.g. across traditional and social media) No data - blank
* [STRING]    `public_information_campaigns_flag`
  - Sector scope of H1 actions;  0 - formal sector workers only 1 - transfers to informal sector workers too No data - blank
* [STRING]    `public_information_campaigns_notes`
  - Additional details about H1 policy actions
* [STRING]    `testing_policy`
  - H2 - Ordinal scale record of who can get tested;  0 – No testing policy 1 – Only those who both (a) have symptoms AND (b) meet specific criteria (eg key workers admitted to hospital came into contact with a known case returned from overseas) 2 – testing of anyone showing COVID-19 symptoms 3 – open public testing (eg “drive through” testing available to asymptomatic people) No data Nb we are looking for policies about testing for having an infection (PCR tests) - not for policies about testing for immunity (antibody tests).
* [STRING]    `testing_policy_notes`
  - Additional details about H2 policy actions
* [STRING]    `contact_tracing`
  - H3 - Ordinal scale record if governments doing contact tracing; 0 - No contact tracing 1 - Limited contact tracing - not done for all cases 2 - Comprehensive contact tracing - done for all cases No data
* [STRING]    `contact_tracing_notes`
  - Additional details about H3 policy actions
* [FLOAT]     `emergency_healthcare_investment`
  - H4 - Short-term spending on e.g hospitals masks etc in USD; Record monetary value in USD of new short-term spending on health. If none enter 0. No data - blank Please use the exchange rate of the date you are coding not the current date.
* [STRING]    `emergency_healthcare_investment_notes`
  - Additional details about H4 policy actions
* [FLOAT]     `vaccine_investment`
  - H5 - Announced public spending on vaccine development in USD; Record monetary value in USD of new short-term spending on health. If none enter 0. No data - blank Please use the exchange rate of the date you are coding not the current date.
* [STRING]    `vaccine_investment_notes`
  - Additional details about H5 policy actions
* [STRING]    `misc_wildcard`
  - M1 - Record policy announcements that do not fit anywhere else
* [STRING]    `misc_wildcard_notes`
  - Additional details about M1 policy actions
* [INTEGER]   `confirmed_cases`
  - Number of confirmed COVID-19 cases
* [INTEGER]   `deaths`
  - Number of confirmed COVID-19 deaths
* [FLOAT]     `stringency_index`
  - Used after April 28 2020. Nine-point aggregation of the eight containment and closure indicators as well as H1 (public information campaigns). It reports a number between 0 to 100 that reflects the overall stringency of the governments response. This is a measure of how many of the these nine indicators (mostly around social isolation) a government has acted upon and to what degree.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
