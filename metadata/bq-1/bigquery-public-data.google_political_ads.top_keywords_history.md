# `google_political_ads.top_keywords_history`
`bq-1` | `bigquery-public-data`
The "Top Keywords" section of the US report was removed and updates to this table were terminated in December 2019. The table reflects historical data. This table contains the information for the top six keywords on which political advertisers have spent money during an election cycle. This data is only provided for US elections. The primary key is election_cycle, report_date.

## Column details
* [STRING]    `election_cycle`
  - [DEPRECATED] This field is deprecated in favor of the Region and Elections field. It will be deleted some time after July 2019.
* [DATE]      `report_date`
  - [DEPRECATED] The start date for the week where the spending was reported.
* [STRING]    `keyword_1`
  -  [DEPRECATED] Keyword with the most spend by advertisers for political ads
* [INTEGER]   `spend_usd_1`
  - [DEPRECATED] Total spend in USD for Keyword_1.
* [STRING]    `keyword_2`
  - [DEPRECATED] Keyword with the next most spend by advertisers for political ads
* [INTEGER]   `spend_usd_2`
  - [DEPRECATED] Total spend in USD for Keyword_2.
* [STRING]    `keyword_3`
  - [DEPRECATED] Keyword with the next most spend by advertisers for political ads
* [INTEGER]   `spend_usd_3`
  - [DEPRECATED] Total spend in USD for Keyword_3.
* [STRING]    `keyword_4`
  - [DEPRECATED] Keyword with the next most spend by advertisers for political ads
* [INTEGER]   `spend_usd_4`
  - [DEPRECATED] Total spend in USD for Keyword_4.
* [STRING]    `keyword_5`
  - [DEPRECATED] Keyword with the next most spend by advertisers for political ads
* [INTEGER]   `spend_usd_5`
  - [DEPRECATED] Total spend in USD for Keyword_5.
* [STRING]    `keyword_6`
  - [DEPRECATED] Keyword with the next most spend by advertisers for political ads
* [INTEGER]   `spend_usd_6`
  - [DEPRECATED] Total spend in USD for Keyword_6.
* [STRING]    `region`
  - [DEPRECATED] The region where advertisers used these keywords.
* [STRING]    `elections`
  - [DEPRECATED] The elections during which these keywords were used.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
