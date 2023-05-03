# `idc_current.analysis_results_metadata` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

## Column details
* [STRING]    `ID`
  - Results ID
* [STRING]    `Title`
  - Descriptive title
* [STRING]    `Access`
  - Limited or Public
* [STRING]    `DOI`
  - DOI that can be resolved at doi.org to a wiki page
* [STRING]    `CancerType`
  - Type(s) of cancer analyzed
* [STRING]    `Location`
  - Body location that was analyzed
* [INTEGER]   `Subjects`
  - Number of subjects whose data was analyzed
* [STRING]    `Collections`
  - idc_webapp_collection_ids of original data collections analyzed
* [STRING]    `AnalysisArtifactsonTCIA`
  - Types of analysis artifacts produced
* [DATE]      `Updated`
  - Most recent update reported by TCIA
* [STRING]    `license_url`
  - URL of license of this analysis result
* [STRING]    `license_long_name`
  - Long name of license of this analysis result
* [STRING]    `license_short_name`
  - Short name of license of this analysis result
* [STRING]    `Description`
  - Analysis result description

-------------------------------------------------------------------------------
*Do not make edits above this line.*
