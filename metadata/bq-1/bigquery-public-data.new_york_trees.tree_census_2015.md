# `new_york_trees.tree_census_2015`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `tree_id`
  - Unique identification number for each tree point
* [INTEGER]   `block_id`
  - Identifier linking each tree to the block in the blockface table/shapefile that it is mapped on.
* [DATE]      `created_at`
  - The date tree points were collected in the census software
* [INTEGER]   `tree_dbh`
  - Diameter of the tree, measured at approximately 54" / 137cm above the ground.
* [INTEGER]   `stump_diam`
  - Diameter of stump measured through the center, rounded to the nearest inch.
* [STRING]    `curb_loc`
  - Location of tree bed in relationship to the curb; trees are either along the curb (OnCurb) or offset from the curb (OffsetFromCurb)
* [STRING]    `status`
  - Indicates whether the tree is alive, standing dead, or a stump.
* [STRING]    `health`
  - Indicates the user's perception of tree health.
* [STRING]    `spc_latin`
  - Scientific name for species, e.g. "Acer rubrum"
* [STRING]    `spc_common`
  - Common name for species, e.g. "red maple"
* [STRING]    `steward`
  - Indicates the number of unique signs of stewardship observed for this tree. Not recorded for stumps or dead trees.
* [STRING]    `guards`
  - Indicates whether a guard is present, and if the user felt it was a helpful or harmful guard. Not recorded for dead trees and stumps
* [STRING]    `sidewalk`
  - Indicates whether one of the sidewalk flags immediately adjacent to the tree was damaged, cracked, or lifted. Not recorded for dead trees and stumps.
* [STRING]    `user_type`
  - This field describes the category of user who collected this tree point's data.
* [STRING]    `problems`
* [STRING]    `root_stone`
  - Indicates the presence of a root problem caused by paving stones in tree bed
* [STRING]    `root_grate`
  - Indicates the presence of a root problem caused by metal grates in tree bed
* [STRING]    `root_other`
  - Indicates the presence of other root problems
* [STRING]    `trunk_wire`
  - Indicates the presence of a trunk problem caused by wires or rope wrapped around the trunk
* [STRING]    `trnk_light`
  - Indicates the presence of a trunk problem caused by lighting installed on the tree
* [STRING]    `trnk_other`
  - Indicates the presence of other trunk problems
* [STRING]    `brch_light`
  - Indicates the presence of a branch problem caused by lights (usually string lights) or wires in the branches
* [STRING]    `brch_shoe`
  - Indicates the presence of a branch problem caused by sneakers in the branches
* [STRING]    `brch_other`
  - Indicates the presence of other branch problems
* [STRING]    `address`
  - Nearest estimated address to tree
* [INTEGER]   `zipcode`
  - Five-digit zipcode in which tree is located
* [STRING]    `zip_city`
  - City as derived from zipcode. This is often (but not always) the same as borough.
* [INTEGER]   `cb_num`
  - Community board in which tree point is located
* [INTEGER]   `borocode`
  - Code for borough in which tree point is located
* [STRING]    `boroname`
  - Name of borough in which tree point is located
* [INTEGER]   `cncldist`
  - Council district in which tree point is located
* [INTEGER]   `st_assem`
  - State Assembly District in which tree point is located
* [INTEGER]   `st_senate`
  - State Senate District in which tree point is located
* [STRING]    `nta`
  - This is the NTA Code corresponding to the neighborhood tabulation area from the 2010 US Census that the tree point falls into.
* [STRING]    `nta_name`
  - This is the NTA name corresponding to the neighborhood tabulation area from the 2010 US Census that the tree point falls into.
* [INTEGER]   `boro_ct`
  - This is the boro_ct identifyer for the census tract that the tree point falls into.
* [STRING]    `state`
  - All features given value 'New York'
* [FLOAT]     `latitude`
  - Latitude of point, in decimal degrees
* [FLOAT]     `longitude`
  - Longitude of point, in decimal degrees
* [FLOAT]     `x_sp`
  - X coordinate, in state plane. Units are feet.
* [FLOAT]     `y_sp`
  - Y coordinate, in state plane. Units are feet

-------------------------------------------------------------------------------
*Do not make edits above this line.*
