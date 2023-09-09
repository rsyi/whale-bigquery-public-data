# `idc_v16.dicom_metadata_curated_view` [view]
`bq-1` | `bigquery-public-data`
dicom_all_curated consists of curated columns from dicom_metadata; see source code for the underlying query at https://github.com/ImagingDataCommons/etl_flow/blob/master/bq/derived_table_creation/BQ_Table_Building/derived_data_views/sql/dicom_metadata_curated.sql

## Column details
* [STRING]    `SOPInstanceUID`
  - DICOM SOPInstanceUID
* [FLOAT]     `SliceThickness`
  - Cast of Slice_Thickness to FLOAT64
* [STRING]    `BodyPartExamined`
  - Curated value of BodyPartExamined following the manually created mapping. For the mapping details, please refer to the query referenced in the series description.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
