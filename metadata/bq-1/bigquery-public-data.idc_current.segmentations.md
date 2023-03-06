# `idc_current.segmentations` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

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
