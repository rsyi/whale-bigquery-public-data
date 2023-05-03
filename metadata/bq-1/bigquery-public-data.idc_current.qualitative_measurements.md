# `idc_current.qualitative_measurements` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

## Column details
* [STRING]    `PatientID`
* [STRING]    `SOPInstanceUID`
* [INTEGER]   `measurementGroup_number`
  - Measurement group number corresponding to the measurement groups within the TID 1500 report, starting from 0.
* [STRING]    `segmentationInstanceUID`
  - SOPInstanceUID of the segmentation object defining the region of interest corresponding to the measurement.
* [INTEGER]   `segmentationSegmentNumber`
  - SegmentNumber of the segment within the segmentation object referenced by segmentationInstanceUID defining the region of interest corresponding to the measurement.
* [STRING]    `sourceSegmentedSeriesUID`
  - SeriesInstanceUID corresponding to the image series over which the measurement was done.
* [STRING]    `trackingIdentifier`
  - Value of the TID 1500 Measurement group row corresponding to the concept "Tracking Identifier" (e.g., row 2 in TID 1411)
* [STRING]    `trackingUniqueIdentifier`
  - Value of the TID 1500 Measurement group row corresponding to the concept "Tracking Unique Identifier" (e.g., row 3 in TID 1411)
* [RECORD]    `Quantity`
  - Value of the concept code corresponding to TID 1500 Measurement group row where VT is CODE.
* [STRING]    `Quantity.CodeValue`
* [STRING]    `Quantity.CodingSchemeDesignator`
* [STRING]    `Quantity.CodeMeaning`
* [RECORD]    `Value`
  - Value corresponding to the concept listed in the Quantity field.
* [STRING]    `Value.CodeValue`
* [STRING]    `Value.CodingSchemeDesignator`
* [STRING]    `Value.CodingSchemeVersion`
* [STRING]    `Value.CodeMeaning`
* [RECORD]    `finding`
  - Value of the TID 1500 Measurement group row corresponding to the concept "Finding" (e.g., row 3b in TID 1411)
* [STRING]    `finding.CodeValue`
* [STRING]    `finding.CodingSchemeDesignator`
* [STRING]    `finding.CodingSchemeVersion`
* [STRING]    `finding.CodeMeaning`
* [RECORD]    `findingSite`
  - Value of the TID 1500 Measurement group row corresponding to the concept "Finding Site" (e.g., row 2 in TID 1419)
* [STRING]    `findingSite.CodeValue`
* [STRING]    `findingSite.CodingSchemeDesignator`
* [STRING]    `findingSite.CodingSchemeVersion`
* [STRING]    `findingSite.CodeMeaning`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
