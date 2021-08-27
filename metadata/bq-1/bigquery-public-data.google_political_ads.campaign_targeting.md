# `google_political_ads.campaign_targeting`
`bq-1` | `bigquery-public-data`
This table was deprecated and ad-level targeting information was made available in the `google_political_ads.creative_stats` BigQuery table, effective April 2020. This table contains the information related to ad campaigns run by advertisers.

## Column details
* [STRING]    `campaign_id`
  - [DEPRECATED] Unique ID for a political ad campaign.
* [STRING]    `age_targeting`
  - [DEPRECATED] Age ranges included in the campaign's targeting.
* [STRING]    `gender_targeting`
  - [DEPRECATED] Genders included in the campaign's targeting
* [STRING]    `geo_targeting_included`
  - [DEPRECATED] Geographic locations included in the campaign's targeting.
* [STRING]    `geo_targeting_excluded`
  - [DEPRECATED] Geographic locations excluded from the campaign's targeting.
* [DATE]      `start_date`
  - [DEPRECATED] Start date for the campaign.
* [DATE]      `end_date`
  - [DEPRECATED] End date for the campaign.
* [STRING]    `ads_list`
  - [DEPRECATED] List of Ad_IDs for the campaign.
* [STRING]    `advertiser_id`
  - [DEPRECATED] ID of the advertiser who purchased the ad.
* [STRING]    `advertiser_name`
  - [DEPRECATED] Name of advertiser.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
