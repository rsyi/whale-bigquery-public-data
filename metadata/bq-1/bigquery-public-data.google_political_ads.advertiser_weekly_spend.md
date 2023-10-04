# `google_political_ads.advertiser_weekly_spend`
`bq-1` | `bigquery-public-data`
This table contains the information for how much an advertiser spent on political ads during a given week. The table's primary key is advertiser_id, election_cycle, week_start_date

## Column details
* [STRING]    `advertiser_id`
  - Unique ID for an advertiser verified to run election ads on Google Ads Services.
* [STRING]    `advertiser_name`
  - Name of advertiser.
* [STRING]    `election_cycle`
  - [DEPRECATED] This field is deprecated in favor of the Elections column in advertiser_stats table. It will be deleted some time after July 2019.
* [DATE]      `week_start_date`
  - The start date for the week where spending occurred.
* [INTEGER]   `spend_usd`
  - The amount in USD spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_eur`
  - The amount in EUR spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_inr`
  - The amount in INR spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_bgn`
  - The amount in BGN spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_hrk`
  - The amount in HRK spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_czk`
  - The amount in CZK spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_dkk`
  - The amount in DKK spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_huf`
  - The amount in HUF spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_pln`
  - The amount in PLN spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_ron`
  - The amount in RON spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_sek`
  - The amount in SEK spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_gbp`
  - The amount in GBP spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_nzd`
  - The amount in NZD spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_ils`
  - The amount in ILS spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_aud`
  - The amount in AUD spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_twd`
  - The amount in TWD spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_brl`
  - The amount in BRL spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_ars`
  - The amount in ARS spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_zar`
  - The amount in ZAR spent on election ads during the given week by the advertiser.
* [INTEGER]   `spend_clp`
  - The amount in CLP spent on election ads during the given week by the advertiser.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
