# `idc_v18.analysis_results_metadata`
`bq-1` | `bigquery-public-data`
Metadata of Analysis Results. These are the results of analysis performed against Original Collections hosted by IDC.

## Column details
* [STRING]    `ID`
  - Results ID
* [STRING]    `Title`
  - Descriptive title
* [STRING]    `Access`
  - Limited or Public
* [STRING]    `source_doi`
  - DOI that can be resolved at doi.org to a wiki page
* [STRING]    `source_url`
  - URL of a wiki page
* [STRING]    `CancerTypes`
  - Type(s) of cancer analyzed
* [STRING]    `TumorLocations`
  - Body location that was analyzed
* [INTEGER]   `Subjects`
  - Number of subjects whose data was analyzed
* [STRING]    `Collections`
  - collection_names of original data collections analyzed
* [STRING]    `AnalysisArtifacts`
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
* [STRING]    `AnalysisArtifactsonTCIA`
  - DEPRECATED: Duplicate of AnalysisArtifacts
* [STRING]    `DOI`
  - DEPRECATED: Duplicate of source_doi
* [STRING]    `CancerType`
  - DEPRECATED: Duplicate of CancerTypes
* [STRING]    `Location`
  - DEPRECATED: Duplicate of PrimarySiteLocations

-------------------------------------------------------------------------------
*Do not make edits above this line.*
