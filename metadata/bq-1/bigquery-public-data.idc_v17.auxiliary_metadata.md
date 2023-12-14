# `idc_v17.auxiliary_metadata`
`bq-1` | `bigquery-public-data`
IDC version-related metadata

## Column details
* [STRING]    `collection_name`
  - Collection name as used externally by IDC webapp
* [STRING]    `collection_id`
  - Collection ID as used internally by IDC webapp and accepted by the IDC API
* [DATETIME]  `collection_timestamp`
  - Revision timestamp
* [STRING]    `collection_hash`
  - md5 hash of the of this version of the collection containing this instance
* [INTEGER]   `collection_init_idc_version`
  - The IDC version in which the collection containing this instance first appeared
* [INTEGER]   `collection_revised_idc_version`
  - The IDC version in which this version of the collection containing this instance first appeared
* [STRING]    `submitter_case_id`
  - Patient ID assigned by submitter of this data
* [STRING]    `idc_case_id`
  - IDC assigned UUID4 id of this version of the case/patient containing this instance
* [STRING]    `patient_hash`
  - md5 hash of this version of the patient/case containing this instance
* [INTEGER]   `patient_init_idc_version`
  - The IDC version in which the patient/case containing this instance first appeared
* [INTEGER]   `patient_revised_idc_version`
  - The IDC version in which this version of the patient/case containing this instance first appeared
* [STRING]    `StudyInstanceUID`
  - DICOM study containing this instance
* [STRING]    `study_uuid`
  - UUID of this version of the study containing this instance
* [INTEGER]   `study_instances`
  - Number of instances in the version of the study containing this instance
* [STRING]    `study_hash`
  - md5 hash of the data in the this version of the study containing this instance
* [INTEGER]   `study_init_idc_version`
  - The IDC version in which the study containing this instance first appeared
* [INTEGER]   `study_revised_idc_version`
  - The IDC version in which this version of the study containing this instance first appeared
* [INTEGER]   `study_final_idc_version`
  - The IDC version in which this version of the study containing this instance last appeared. If 0, thise is the current version.
* [STRING]    `SeriesInstanceUID`
  - DICOM series containing this instance
* [STRING]    `series_uuid`
  - UUID of this version of the series containing this instance
* [STRING]    `series_gcs_url`
  - URL of the Google Cloud Storage (GCS) folder of the series containing this instance
* [STRING]    `series_aws_url`
  - URL of the Amazon Web Services (AWS) folder of the series containing this instance
* [STRING]    `source_doi`
  - The DOI of a wiki page that describes the original collection or analysis result that includes this instance
* [STRING]    `source_url`
  - The URL of a wiki page that describes the original collection or analysis result that includes this instance
* [INTEGER]   `series_instances`
  - Number of instances in the version of the study containing this instance
* [STRING]    `series_hash`
  - md5 hash of the data in the this version of the series containing this instance
* [STRING]    `access`
  - Collection access status: Public or Limited
* [INTEGER]   `series_init_idc_version`
  - The IDC version in which the series containing this instance first appeared
* [INTEGER]   `series_revised_idc_version`
  - The IDC version in which this version of the series containing this instance first appeared
* [INTEGER]   `series_final_idc_version`
  - The IDC version in which this version of the series containing this instance last appeared. If 0, thise is the current version.
* [STRING]    `SOPInstanceUID`
  - DICOM instance containing this instance version
* [STRING]    `instance_uuid`
  - UUID of this version of this instance
* [STRING]    `gcs_url`
  - URL of the Google Cloud Storage (GCS) object containing the current version of this instance
* [STRING]    `gcs_bucket`
  - Name of the Google Cloud Storage (GCS) bucket containing the current version of this instance
* [STRING]    `aws_url`
  - URL to the Amazon Web Services (AWS) object containing the current version of this instance
* [STRING]    `aws_bucket`
  - Name to the Amazon Web Services (AWS) bucket containing the current version of this instance
* [INTEGER]   `instance_size`
  - Size in bytes of this version of this instance
* [STRING]    `instance_hash`
  - md5 hash of the data in the this version of this instance
* [INTEGER]   `instance_init_idc_version`
  - The IDC version in which this instance first appeared
* [INTEGER]   `instance_revised_idc_version`
  - The IDC version in which this instance first appeared
* [INTEGER]   `instance_final_idc_version`
  - The IDC version in which this instance last appeared. If 0, thise is the current version.
* [STRING]    `license_url`
  - URL of license of this analysis result
* [STRING]    `license_long_name`
  - Long name of license of this analysis result
* [STRING]    `license_short_name`
  - Short name of license of this analysis result
* [STRING]    `tcia_api_collection_id`
  - DEPRECATED: Collection name as used externally by IDC webapp
* [STRING]    `idc_webapp_collection_id`
  - DEPRECATED: Collection ID as used internally by IDC webapp and accepted by the IDC API

-------------------------------------------------------------------------------
*Do not make edits above this line.*
