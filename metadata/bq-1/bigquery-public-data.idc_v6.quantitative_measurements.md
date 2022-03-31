# `idc_v6.quantitative_measurements` [view]
`bq-1` | `bigquery-public-data`
A convenience view providing simplified access to the items within the DICOM SR TID 1500 documents that contain quantitative measurements. All attributes named following the CamelCase notation (except Quantity and Value) correspond to standard DICOM attributes and are documented in the DICOM standard.

## Column details
* [STRING]    `PatientID`
* [STRING]    `SOPInstanceUID`
* [INTEGER]   `measurementGroup_number`
* [STRING]    `segmentationInstanceUID`
* [INTEGER]   `segmentationSegmentNumber`
* [STRING]    `sourceSegmentedSeriesUID`
* [STRING]    `trackingIdentifier`
* [STRING]    `trackingUniqueIdentifier`
* [RECORD]    `Quantity`
* [STRING]    `Quantity.CodeValue`
* [STRING]    `Quantity.CodingSchemeDesignator`
* [STRING]    `Quantity.CodeMeaning`
* [RECORD]    `derivationModifier`
* [STRING]    `derivationModifier.CodeValue`
* [STRING]    `derivationModifier.CodingSchemeDesignator`
* [STRING]    `derivationModifier.CodeMeaning`
* [NUMERIC]   `Value`
* [RECORD]    `Units`
* [STRING]    `Units.CodeValue`
* [STRING]    `Units.CodingSchemeDesignator`
* [STRING]    `Units.CodingSchemeVersion`
* [STRING]    `Units.CodeMeaning`
* [RECORD]    `finding`
* [STRING]    `finding.CodeValue`
* [STRING]    `finding.CodingSchemeDesignator`
* [STRING]    `finding.CodingSchemeVersion`
* [STRING]    `finding.CodeMeaning`
* [RECORD]    `findingSite`
* [STRING]    `findingSite.CodeValue`
* [STRING]    `findingSite.CodingSchemeDesignator`
* [STRING]    `findingSite.CodingSchemeVersion`
* [STRING]    `findingSite.CodeMeaning`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
