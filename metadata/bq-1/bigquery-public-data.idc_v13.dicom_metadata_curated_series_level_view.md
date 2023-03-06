# `idc_v13.dicom_metadata_curated_series_level_view` [view]
`bq-1` | `bigquery-public-data`
dicom_metadata_curated_series_level contains metadata that has been aggregated/cleaned up to describe content at series level; see source code for the underlying query at https://github.com/ImagingDataCommons/etl_flow/blob/master/bq/derived_table_creation/BQ_Table_Building/derived_data_views/sql/dicom_metadata_curated_series_level.sql

## Column details
* [STRING]    `SeriesInstanceUID`
* [FLOAT]     `min_PixelSpacing_2sf`
* [INTEGER]   `max_TotalPixelMatrixColumns`
* [INTEGER]   `max_TotalPixelMatrixRows`
* [INTEGER]   `ObjectiveLensPower`
* [STRING]    `primaryAnatomicStructure_code_designator_value_str`
* [STRING]    `primaryAnatomicStructure_CodeMeaning`
* [STRING]    `illuminationType_code_designator_value_str`
* [STRING]    `illuminationType_CodeMeaning`
* [STRING]    `Modality`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
