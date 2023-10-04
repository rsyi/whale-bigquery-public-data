# `google_political_ads.creative_stats`
`bq-1` | `bigquery-public-data`
This table contains the information for election ads that have appeared on Google Ads Services. Ad-level targeting data was added to this file in April 2020. ad_id is referenced from: campaign_targeting.ads_list Data that was previously available in the `google_political_ads.campaign_targeting` table has been deprecated and removed in favor of this table.

## Column details
* [STRING]    `ad_id`
  - Unique id for a specific election ad.
* [STRING]    `ad_url`
  - URL to view the election ad in the election Advertising on Google report.
* [STRING]    `ad_type`
  - The type of the ad. Can be TEXT VIDEO or IMAGE.
* [STRING]    `regions`
  - The regions that this ad is verified for or were served in.
* [STRING]    `advertiser_id`
  - ID of the advertiser who purchased the ad.
* [STRING]    `advertiser_name`
  - Name of advertiser.
* [STRING]    `ad_campaigns_list`
  - IDs of all election ad campaigns that included the ad.
* [DATE]      `date_range_start`
  - First day a election ad ran and had an impression.
* [DATE]      `date_range_end`
  - Most recent day a election ad ran and had an impression.
* [INTEGER]   `num_of_days`
  - Total number of days a election ad ran and had an impression.
* [STRING]    `impressions`
  - Number of impressions for the election ad. Impressions are grouped into several buckets ≤ 10k 10k-100k 100k-1M 1M-10M > 10M.
* [STRING]    `spend_usd`
  - [DEPRECATED] This field is deprecated in favor of specifying the lower and higher spend bucket bounds in separate Spend_Range_Min and Spend_Range_Max columns.
* [TIMESTAMP] `first_served_timestamp`
  - The timestamp of the earliest impression for this ad.
* [TIMESTAMP] `last_served_timestamp`
  - The timestamp of the most recent impression for this ad.
* [STRING]    `age_targeting`
  - Age ranges included in the ad's targeting
* [STRING]    `gender_targeting`
  - Genders included in the ad's targeting.
* [STRING]    `geo_targeting_included`
  - Geographic locations included in the ad's targeting.
* [STRING]    `geo_targeting_excluded`
  - Geographic locations excluded in the ad's targeting.
* [INTEGER]   `spend_range_min_usd`
  - Lower bound of the amount in USD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_usd`
  - Upper bound of the amount in USD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_eur`
  - Lower bound of the amount in EUR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_eur`
  - Upper bound of the amount in EUR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_inr`
  - Lower bound of the amount in INR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_inr`
  - Upper bound of the amount in INR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_bgn`
  - Lower bound of the amount in BGN spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_bgn`
  - Upper bound of the amount in BGN spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_czk`
  - Lower bound of the amount in CZK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_czk`
  - Upper bound of the amount in CZK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_dkk`
  - Lower bound of the amount in DKK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_dkk`
  - Upper bound of the amount in DKK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_huf`
  - Lower bound of the amount in HUF spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_huf`
  - Upper bound of the amount in HUF spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_pln`
  - Lower bound of the amount in PLN spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_pln`
  - Upper bound of the amount in PLN spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_ron`
  - Lower bound of the amount in RON spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_ron`
  - Upper bound of the amount in RON spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_sek`
  - Lower bound of the amount in SEK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_sek`
  - Upper bound of the amount in SEK spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_gbp`
  - Lower bound of the amount in GBP spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_gbp`
  - Upper bound of the amount in GBP spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_nzd`
  - Lower bound of the amount in NZD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_nzd`
  - Upper bound of the amount in NZD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_ils`
  - Lower bound of the amount in ILS spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_ils`
  - Upper bound of the amount in ILS spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_aud`
  - Lower bound of the amount in AUD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_aud`
  - Upper bound of the amount in AUD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_twd`
  - Lower bound of the amount in TWD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_twd`
  - Upper bound of the amount in TWD spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_brl`
  - Lower bound of the amount in BRL spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_brl`
  - Upper bound of the amount in BRL spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_ars`
  - Lower bound of the amount in ARS spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_ars`
  - Upper bound of the amount in ARS spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_zar`
  - Lower bound of the amount in ZAR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_zar`
  - Upper bound of the amount in ZAR spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_min_clp`
  - Lower bound of the amount in CLP spent by the advertiser on the election ad.
* [INTEGER]   `spend_range_max_clp`
  - Upper bound of the amount in CLP spent by the advertiser on the election ad.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
