# `google_ads_transparency_center.sqlp-temp-donotremove-1710740762064375826-z0oxvM4b`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `advertiser_id`
  - A unique identifier for a specific advertiser
* [STRING]    `creative_id`
  - A unique identifier for a specific ad
* [STRING]    `creative_page_url`
  - A link to the relevant Ads Transparency Center page for this ad
* [STRING]    `ad_format_type`
  - A description of the ad type
* [STRING]    `advertiser_disclosed_name`
  - The advertiser's name for transparency reporting and disclosures
* [STRING]    `advertiser_legal_name`
  - The legal name of the advertiser
* [STRING]    `advertiser_location`
  - ISO 3166-2 region code (for example "FR" for France)
* [STRING]    `advertiser_verification_status`
  - Whether or not the advertiser has verified their identity with Google yet
* [RECORD]    `region_stats`
  - Collection of regions in which the ad served (in the European Economic Area and Turkey) and their relevant stats
* [STRING]    `region_stats.region_code`
  - ISO 3166-2 region code (for example "FR" for France) of the region where the ad was shown, or a text representation of an aggregate region (for example "EEA" for the European Economic Area)
* [STRING]    `region_stats.first_shown`
  - YYYY-MM-DD representation of the first date the ad was shown. If the ad was first shown before March 1st, 2023, March 1st, 2023 will be reported as the first_shown date.
* [STRING]    `region_stats.last_shown`
  - YYYY-MM-DD representation of the last date the ad was shown
* [STRING]    `region_stats.times_shown_end_date`
  - YYYY-MM-DD representation of the date up to which times_shown (both upper and lower bounds) has been updated. This field is NULL if no impressions occurred within the reporting period.
* [INTEGER]   `region_stats.times_shown_lower_bound`
  - The lower bound of the number of times the ad was shown in the associated region. This field is NULL if no impressions occurred within the reporting period.
* [INTEGER]   `region_stats.times_shown_upper_bound`
  - The upper bound of the number of times the ad was shown in the associated region. This field is NULL if no impressions occurred within the valid reporting period.
* [STRING]    `region_stats.times_shown_start_date`
  - YYYY-MM-DD representation of the earliest date for which times_shown is considered (both upper and lower bounds). Impressions are reported for activity since March 1st, 2023. This field is NULL if no impressions occurred with the reporting period.
* [STRING]    `region_stats.times_shown_availability_date`
  - YYYY-MM-DD representation of the date on which impressions will become available if no impressions occurred within the reporting period. This field is NULL if impressions did occur within the reporting period.
* [RECORD]    `region_stats.surface_serving_stats`
  - Collection of platforms where the ad served and their relevant serving times lower/upper bound. This field is NULL if no platform serving stats data is populated.
* [RECORD]    `region_stats.surface_serving_stats.surface_serving_stats`
  - Collection of platforms where the ad served and their relevant serving times lower/upper bound. The field is empty if no platform serving stats data is available within the valid reporting period.
* [STRING]    `region_stats.surface_serving_stats.surface_serving_stats.surface`
  - The platform where the ad served. Possible values are: SEARCH, MAPS, PLAY, SHOPPING, YOUTUBE.
* [INTEGER]   `region_stats.surface_serving_stats.surface_serving_stats.times_shown_upper_bound`
  - The upper bound of the number of times the ad was shown in the associated region and platform.
* [INTEGER]   `region_stats.surface_serving_stats.surface_serving_stats.times_shown_lower_bound`
  - The lower bound of the number of times the ad was shown in the associated region and platform.
* [STRING]    `region_stats.surface_serving_stats.surface_serving_stats.times_shown_availability_date`
* [RECORD]    `audience_selection_approach_info`
  - Information on audience selection, broken out by approach type. The available values are: "CRITERIA_INCLUDED" (Criteria from this category were included in the ad's audience), "CRITERIA_EXCLUDED" (Criteria from this category were excluded from the ad's audience), "CRITERIA_INCLUDED_AND_EXCLUDED" (Some criteria from this category were included and others were excluded from the ad's audience), and "CRITERIA_UNUSED" (Criteria from these categories were not used for audience selection).
* [STRING]    `audience_selection_approach_info.demographic_info`
  - Describes if and how demographic info was used to select the ad audience (see audience_selection_approach_info above for more details)
* [STRING]    `audience_selection_approach_info.geo_location`
  - Describes if and how geo location info was used to select the ad audience (see audience_selection_approach_info above for more details)
* [STRING]    `audience_selection_approach_info.contextual_signals`
  - Describes if and how contextual signals were used to select the ad audience (see audience_selection_approach_info above for more details)
* [STRING]    `audience_selection_approach_info.customer_lists`
  - Describes if and how customer lists were used to select the ad audience (see audience_selection_approach_info above for more details)
* [STRING]    `audience_selection_approach_info.topics_of_interest`
  - Describes if and how topics of interest were used to select the ad audience (see audience_selection_approach_info above for more details)
* [STRING]    `topic`
  - The topic of the ad

-------------------------------------------------------------------------------
*Do not make edits above this line.*
