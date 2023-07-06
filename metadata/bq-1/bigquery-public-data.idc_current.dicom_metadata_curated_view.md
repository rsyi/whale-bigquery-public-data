# `idc_current.dicom_metadata_curated_view` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

## Column details
* [STRING]    `SOPInstanceUID`
  - DICOM SOPInstanceUID
* [FLOAT]     `SliceThickness`
  - Cast of Slice_Thickness to FLOAT64
* [STRING]    `BodyPartExamined`
  - Curated value of BodyPartExamined following the manually created mapping. For the mapping details, please refer to the query referenced in the series description.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
