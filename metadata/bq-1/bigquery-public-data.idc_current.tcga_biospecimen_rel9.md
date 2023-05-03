# `idc_current.tcga_biospecimen_rel9` [view]
`bq-1` | `bigquery-public-data`
Views in this dataset reference the tables in the dataset corresponding to the current IDC version.

## Column details
* [STRING]    `sample_barcode`
  - TCGA sample_barcode; e.g. TCGA-AB-2809-03A.
* [STRING]    `sample_gdc_id`
  - Unique GDC identifier for this sample (corresponds to the sample_barcode), eg a1ec9279-c1a6-4e58-97ed-9ec1f36187c5  --  this can be used to access more information from the GDC data portal
* [STRING]    `case_barcode`
  - TCGA patient/case barcode, eg TCGA-AB-2809 (the first 12 characters of the 16-character sample barcode)
* [STRING]    `case_gdc_id`
  - GDC unique identifer for this case; e.g. 7b4ce492-ff40-4bf1-b3e8-75ff83e8746d. This identifier can be used to find more information at the GDC Data Portal ( https://portal.gdc.cancer.gov/cases/7b4ce492-ff40-4bf1-b3e8-75ff83e8746d )
* [STRING]    `sample_type`
  - Two-digit sample_type code which forms part of the sample barcode e.g. 01,11,06, etc.
* [STRING]    `sample_type_name`
  - The longer name of the sample type; e.g. Primary Tumor, Recurrent Tumor, etc.
* [STRING]    `program_name`
  - Program Name, always TCGA (The Cancer Genome Atlas) in this table.
* [STRING]    `project_short_name`
  - Project name abbreviation; the program name appended with a project name abbreviation; e.g. TCGA-OV, etc.
* [INTEGER]   `batch_number`
  - The BCR Batch Code; see https://gdc.cancer.gov/resources-TCGA-users/TCGA-code-tables/bcr-batch-codes for explanation of the codes
* [STRING]    `bcr`
  - Biospecimen Core Resource; e.g. Nationwide Children's Hospital, Washington University
* [FLOAT]     `days_to_collection`
  - Time interval from the date of biospecimen collection to the date of initial pathologic diagnosis, represented as a calculated number of days.
* [FLOAT]     `days_to_sample_procurement`
  - The number of days from the date the patient was diagnosed to the date of the procedure that produced the sample.
* [STRING]    `is_ffpe`
  - Indicator to signify whether or not the tissue sample was fixed in formalin and embedded in paraffin (FFPE); almost always NO -- only a few (99) FFPE samples were included in the TCGA project
* [INTEGER]   `num_portions`
  - In some cases, a sample was divided into multiple portions -- up to 6 portions, but for most samples the number is 1 (or even 0).
* [INTEGER]   `num_slides`
  - In some cases, portions of a sample were placed onto multiple slides -- generally not more than 2, but occasionally more.
* [FLOAT]     `avg_percent_lymphocyte_infiltration`
  - The average percentage of infiltration by lymphocytes in a sample or specimen
* [FLOAT]     `avg_percent_monocyte_infiltration`
  - The average percentage of infiltration by monocyte in a sample or specimen
* [FLOAT]     `avg_percent_necrosis`
  - The average percentage of necrosis in a sample or specimen
* [FLOAT]     `avg_percent_neutrophil_infiltration`
  - The average percentage of neutrophil infiltration in a sample or specimen
* [FLOAT]     `avg_percent_normal_cells`
  - The average percentage of normal cells in a sample or specimen
* [FLOAT]     `avg_percent_stromal_cells`
  - The average percentage of stromal cells in a sample or specimen
* [FLOAT]     `avg_percent_tumor_cells`
  - The average percentage of tumor cells in a sample or specimen
* [FLOAT]     `avg_percent_tumor_nuclei`
  - The average percentage of tumor nuclei in a sample or specimen
* [FLOAT]     `max_percent_lymphocyte_infiltration`
  - The maximum percentage of infiltration by lymphocytes in a sample or specimen
* [FLOAT]     `max_percent_monocyte_infiltration`
  - The maximum percentage of infiltration by monocytes in a sample or specimen
* [FLOAT]     `max_percent_necrosis`
  - The maximum percentage of necrosis in a sample or specimen
* [FLOAT]     `max_percent_neutrophil_infiltration`
  - The maximum percentage of neutrophil infiltration in a sample or specimen
* [FLOAT]     `max_percent_normal_cells`
  - The maximum percentage of normal cells in a sample or specimen
* [FLOAT]     `max_percent_stromal_cells`
  - The maximum percentage of stromal cells in a sample or specimen
* [FLOAT]     `max_percent_tumor_cells`
  - The maximum percentage of tumor cells in a sample or specimen
* [FLOAT]     `max_percent_tumor_nuclei`
  - The maximum percentage of tumor nuclei in a sample or specimen
* [FLOAT]     `min_percent_lymphocyte_infiltration`
  - The minimum percentage of infiltration by lymphocytes in a sample or specimen
* [FLOAT]     `min_percent_monocyte_infiltration`
  - The minimum percentage of infiltration by lymphocytes in a sample or specimen
* [FLOAT]     `min_percent_necrosis`
  - The minimum percentage of necrosis in a sample or specimen
* [FLOAT]     `min_percent_neutrophil_infiltration`
  - The minimum percentage of neutrophil infiltration in a sample or specimen
* [FLOAT]     `min_percent_normal_cells`
  - The minimum percentage of normal cells in a sample or specimen
* [FLOAT]     `min_percent_stromal_cells`
  - The minimum percentage of stromal cells in a sample or specimen
* [FLOAT]     `min_percent_tumor_cells`
  - The minimum percentage of tumor cells in a sample or specimen
* [FLOAT]     `min_percent_tumor_nuclei`
  - The minimum percentage of tumor nuclei in a sample or specimen

-------------------------------------------------------------------------------
*Do not make edits above this line.*
