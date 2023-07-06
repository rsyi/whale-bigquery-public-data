# `idc_v15.segmentations_view` [view]
`bq-1` | `bigquery-public-data`
Attributes of the segments stored in DICOM Segmentation objects; see source code for the underlying query at https://github.com/ImagingDataCommons/etl_flow/blob/master/bq/derived_table_creation/BQ_Table_Building/derived_data_views/sql/segmentations.sql

## Column details
* [STRING]    `PatientID`
* [STRING]    `StudyInstanceUID`
* [STRING]    `SeriesInstanceUID`
* [STRING]    `SOPInstanceUID`
* [STRING]    `FrameOfReferenceUID`
* [RECORD]    `AnatomicRegion`
* [STRING]    `AnatomicRegion.CodeValue`
* [STRING]    `AnatomicRegion.CodingSchemeDesignator`
* [STRING]    `AnatomicRegion.CodeMeaning`
* [RECORD]    `AnatomicRegionModifier`
* [STRING]    `AnatomicRegionModifier.CodeValue`
* [STRING]    `AnatomicRegionModifier.CodingSchemeDesignator`
* [STRING]    `AnatomicRegionModifier.CodeMeaning`
* [RECORD]    `SegmentedPropertyCategory`
* [STRING]    `SegmentedPropertyCategory.CodeValue`
* [STRING]    `SegmentedPropertyCategory.CodingSchemeDesignator`
* [STRING]    `SegmentedPropertyCategory.CodeMeaning`
* [RECORD]    `SegmentedPropertyType`
* [STRING]    `SegmentedPropertyType.CodeValue`
* [STRING]    `SegmentedPropertyType.CodingSchemeDesignator`
* [STRING]    `SegmentedPropertyType.CodeMeaning`
* [RECORD]    `SegmentedPropertyType.AnatomicRegionModifierSequence`
* [STRING]    `SegmentedPropertyType.AnatomicRegionModifierSequence.CodeValue`
* [STRING]    `SegmentedPropertyType.AnatomicRegionModifierSequence.CodingSchemeDesignator`
* [STRING]    `SegmentedPropertyType.AnatomicRegionModifierSequence.CodeMeaning`
* [RECORD]    `SegmentedPropertyType.SegmentedPropertyTypeModifierCodeSequence`
* [STRING]    `SegmentedPropertyType.SegmentedPropertyTypeModifierCodeSequence.CodeValue`
* [STRING]    `SegmentedPropertyType.SegmentedPropertyTypeModifierCodeSequence.CodingSchemeDesignator`
* [STRING]    `SegmentedPropertyType.SegmentedPropertyTypeModifierCodeSequence.CodeMeaning`
* [STRING]    `SegmentAlgorithmType`
* [STRING]    `SegmentAlgorithmName`
* [INTEGER]   `SegmentNumber`
* [STRING]    `TrackingUID`
* [STRING]    `TrackingID`
* [STRING]    `segmented_SeriesInstanceUID`
* [STRING]    `viewer_url`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
