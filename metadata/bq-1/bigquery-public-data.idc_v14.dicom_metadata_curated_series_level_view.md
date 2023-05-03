# `idc_v14.dicom_metadata_curated_series_level_view` [view]
`bq-1` | `bigquery-public-data`
dicom_metadata_curated_series_level contains metadata that has been aggregated/cleaned up to describe content at series level; see source code for the underlying query at https://github.com/ImagingDataCommons/etl_flow/blob/master/bq/derived_table_creation/BQ_Table_Building/derived_data_views/sql/dicom_metadata_curated_series_level.sql

## Column details
* [STRING]    `SeriesInstanceUID`
  - DICOM SeriesInstanceUID
* [FLOAT]     `min_PixelSpacing_2sf`
  - Minimum value of the first component of pixel spacing across all instances in the series. Contains first non-null value between first component of the top-level PixelSpacing attribute and the one in SharedFunctionalGroupSequence[0] > PixelMeasuresSequence[0]. Rounded to two significant figures.
* [INTEGER]   `max_TotalPixelMatrixColumns`
  - Minimum value of the Columns attribute across instances within the series. Contains first non-null value between the top-level Columns attribute and the one in TotalPixelMatrixColumns (encountered in SM modality).
* [INTEGER]   `max_TotalPixelMatrixRows`
  - Minimum value of the Rows attribute across instances within the series. Contains first non-null value between the top-level Rows attribute and the one in TotalPixelMatrixRows (encountered in SM modality).
* [INTEGER]   `ObjectiveLensPower`
  - Value of OpticalPathSequence[0] > ObjectiveLensPower (applicable in SM).
* [STRING]    `primaryAnatomicStructure_code_designator_value_str`
  - Concatenated values of `CodingSchemeDesignator` and `CodeValue` separated by `:` from SpecimenDescriptionSequence[0] > PrimaryAnatomicStructureSequence[0] (applicable in SM).
* [STRING]    `primaryAnatomicStructure_CodeMeaning`
  - `CodeMeaning` from SpecimenDescriptionSequence[0] > PrimaryAnatomicStructureSequence[0] (applicable in SM).
* [STRING]    `illuminationType_code_designator_value_str`
  - Concatenated values of `CodingSchemeDesignator` and `CodeValue` separated by `:` from OpticalPathSequence[0].IlluminationTypeCodeSequence[0] (applicable in SM).
* [STRING]    `illuminationType_CodeMeaning`
  - `CodeMeaning` from OpticalPathSequence[0].IlluminationTypeCodeSequence[0] (applicable in SM).
* [STRING]    `Modality`
  - DICOM Modality

-------------------------------------------------------------------------------
*Do not make edits above this line.*
