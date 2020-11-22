# `san_francisco.street_trees`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `tree_id`
  - Unique ID for Tree
* [STRING]    `legal_status`
  - Legal staus: Permitted or DPW maintained
* [STRING]    `species`
  - Species of tree
* [STRING]    `address`
  - Address of Tree
* [INTEGER]   `site_order`
  - Order of tree at address where multiple trees are at same address. Trees are ordered in ascending address order
* [STRING]    `site_info`
  - Description of location of tree
* [STRING]    `plant_type`
  - Landscaping or Tree
* [STRING]    `care_taker`
  - Agency or person that is primary caregiver to tree. Owner of Tree
* [STRING]    `care_assistant`
  - Agency or person that is secondary caregiver to tree
* [TIMESTAMP] `plant_date`
  - Date tree was planted
* [STRING]    `dbh`
  - depth, height
* [STRING]    `plot_size`
  - dimension of tree plot
* [STRING]    `permit_notes`
  - Tree permit number reference
* [FLOAT]     `x_coordinate`
  - CA State Plane III
* [FLOAT]     `y_coordinate`
  - CA State Plane III
* [FLOAT]     `latitude`
  - WGS84
* [FLOAT]     `longitude`
  - WGS84
* [STRING]    `location`
  - Location formatted for mapping

-------------------------------------------------------------------------------
*Do not make edits above this line.*
