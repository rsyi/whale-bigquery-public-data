# `google_political_ads.advertiser_stats`
`bq-1` | `bigquery-public-data`
This table contains the information about advertisers who have run an election ad on Google Ads Services with at least one impression. The table's primary key is advertiser_id. This table relates to the others in this dataset, with the following connections between columns: advertiser_id is referenced from: advertiser_weekly_spend.advertiser_id campaign_targeting.advertiser_id creative_stats.advertiser_id advertiser_name is referenced from: advertiser_weekly_spend.advertiser_name campaign_targeting.advertiser_name advertiser_id.advertiser_name

## Column details
* [STRING]    `advertiser_id`
  - Unique ID for an advertiser verified to run election ads on Google Ads Services.
* [STRING]    `advertiser_name`
  - Name of advertiser.
* [STRING]    `public_ids_list`
  - List of public IDs used to identify the advertiser if available.
* [STRING]    `regions`
  - The list of regions where the ads of this advertiser were served
* [STRING]    `elections`
  - The list of elections that this advertiser participated in based on the regions.
* [INTEGER]   `total_creatives`
  - Total number of election ads the advertiser ran with at least one impression.
* [INTEGER]   `spend_usd`
  - Total amount in USD spent on election ads by the advertiser.
* [INTEGER]   `spend_eur`
  - Total amount in EUR spent on election ads by the advertiser.
* [INTEGER]   `spend_inr`
  - Total amount in INR spent on election ads by the advertiser.
* [INTEGER]   `spend_bgn`
  - Total amount in BGN spent on election ads by the advertiser.
* [INTEGER]   `spend_hrk`
  - Total amount in HRK spent on election ads by the advertiser.
* [INTEGER]   `spend_czk`
  - Total amount in CZK spent on election ads by the advertiser.
* [INTEGER]   `spend_dkk`
  - Total amount in DKK spent on election ads by the advertiser.
* [INTEGER]   `spend_huf`
  - Total amount in HUF spent on election ads by the advertiser.
* [INTEGER]   `spend_pln`
  - Total amount in PLN spent on election ads by the advertiser.
* [INTEGER]   `spend_ron`
  - Total amount in RON spent on election ads by the advertiser.
* [INTEGER]   `spend_sek`
  - Total amount in SEK spent on election ads by the advertiser.
* [INTEGER]   `spend_gbp`
  - Total amount in GBP spent on election ads by the advertiser.
* [INTEGER]   `spend_nzd`
  - Total amount in NZD spent on election ads by the advertiser.
* [INTEGER]   `spend_ils`
  - Total amount in ILS spent on election ads by the advertiser.
* [INTEGER]   `spend_aud`
  - Total amount in AUD spent on election ads by the advertiser.
* [INTEGER]   `spend_twd`
  - Total amount in TWD spent on election ads by the advertiser.
* [INTEGER]   `spend_brl`
  - Total amount in BRL spent on election ads by the advertiser.
* [INTEGER]   `spend_ars`
  - Total amount in ARS spent on election ads by the advertiser.
* [INTEGER]   `spend_zar`
  - Total amount in ZAR spent on election ads by the advertiser.
* [INTEGER]   `spend_clp`
  - Total amount in CLP spent on election ads by the advertiser.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
