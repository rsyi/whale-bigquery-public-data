# `idc_current.dicom_metadata_curated_series_level_view` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

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
* [STRING]    `primaryAnatomicStructureModifier_code_designator_value_str`
  - Concatenated values of `CodingSchemeDesignator` and `CodeValue` separated by `:` from SpecimenDescriptionSequence[0] > PrimaryAnatomicStructureSequence[0] > PrimaryAnatomicStructureModifierSequence[0] (applicable in SM).
* [STRING]    `primaryAnatomicStructureModifier_CodeMeaning`
  - `CodeMeaning` from SpecimenDescriptionSequence[0] > PrimaryAnatomicStructureSequence[0] > PrimaryAnatomicStructureModifierSequence[0] (applicable in SM).
* [STRING]    `illuminationType_code_designator_value_str`
  - Concatenated values of `CodingSchemeDesignator` and `CodeValue` separated by `:` from OpticalPathSequence[0].IlluminationTypeCodeSequence[0] (applicable in SM).
* [STRING]    `illuminationType_CodeMeaning`
  - `CodeMeaning` from OpticalPathSequence[0].IlluminationTypeCodeSequence[0] (applicable in SM).
* [STRING]    `Modality`
  - DICOM Modality

-------------------------------------------------------------------------------
*Do not make edits above this line.*
