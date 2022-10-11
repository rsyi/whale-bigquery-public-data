# `ebi_chembl.products_30`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `dosage_form`
  -  The dosage form of the product (e.g., tablet, capsule etc)
* [STRING]    `route`
  -  The administration route of the product (e.g., oral, injection etc)
* [STRING]    `trade_name`
  -  The trade name for the product
* [DATETIME]  `approval_date`
  - The FDA approval date for the product (not necessarily first approval of the active ingredient)
* [STRING]    `ad_type`
  -  RX = prescription, OTC = over the counter, DISCN = discontinued
* [INTEGER]   `oral`
  - Flag to show whether product is orally delivered
* [INTEGER]   `topical`
  - Flag to show whether product is topically delivered
* [INTEGER]   `parenteral`
  - Flag to show whether product is parenterally delivered
* [INTEGER]   `black_box_warning`
  - Flag to show whether the product label has a black box warning
* [STRING]    `applicant_full_name`
  -  Name of the company applying for FDA approval
* [INTEGER]   `innovator_company`
  - Flag to show whether the applicant is the innovator of the product
* [STRING]    `product_id`
  - FDA application number for the product
* [STRING]    `nda_type`
  -  Abbreviated New Drug Applications (ANDA or generic) are “A”.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
