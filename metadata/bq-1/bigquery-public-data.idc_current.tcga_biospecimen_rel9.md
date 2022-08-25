# `idc_current.tcga_biospecimen_rel9` [view]
`bq-1` | `bigquery-public-data`
Data was extracted from the TCGA program in April 2017. It contains sample data for TCGA patient cases, originally based on the information provided by the TCGA biospecimen core resource (BCR) to the TCGA DCC in the form of xml files. Most patients (cases) provided two samples: one primary tumor sample and one blood normal sample, although other sample types exist, such as metastatic tumor samples, adjacent ""normal"" tissue samples, etc. There are, in a few cases, as many as 8 samples from a single case, although these may represent multiple "vials" from a smaller number of biospecimens. Also, some samples were obtained from cases for which no clinical information existed and which are therefore not represented in the Clinical table (which contains close to 200 fewer cases than this table does). More details: information about “clinical data elements” can be found at the NCI CDE (clinical data element) browser at https://cdebrowser.nci.nih.gov. This table has been deprecated. It has been copied to isb-cgc-bq.TCGA_versioned.biospecimen_gdc_2017_02. Please see isb-cgc-bq.TCGA.biospecimen_gdc_current for the most current table.

## Column details
* [STRING]    `sample_barcode`
* [STRING]    `sample_gdc_id`
* [STRING]    `case_barcode`
* [STRING]    `case_gdc_id`
* [STRING]    `sample_type`
* [STRING]    `sample_type_name`
* [STRING]    `program_name`
* [STRING]    `project_short_name`
* [INTEGER]   `batch_number`
* [STRING]    `bcr`
* [FLOAT]     `days_to_collection`
* [FLOAT]     `days_to_sample_procurement`
* [STRING]    `is_ffpe`
* [INTEGER]   `num_portions`
* [INTEGER]   `num_slides`
* [FLOAT]     `avg_percent_lymphocyte_infiltration`
* [FLOAT]     `avg_percent_monocyte_infiltration`
* [FLOAT]     `avg_percent_necrosis`
* [FLOAT]     `avg_percent_neutrophil_infiltration`
* [FLOAT]     `avg_percent_normal_cells`
* [FLOAT]     `avg_percent_stromal_cells`
* [FLOAT]     `avg_percent_tumor_cells`
* [FLOAT]     `avg_percent_tumor_nuclei`
* [FLOAT]     `max_percent_lymphocyte_infiltration`
* [FLOAT]     `max_percent_monocyte_infiltration`
* [FLOAT]     `max_percent_necrosis`
* [FLOAT]     `max_percent_neutrophil_infiltration`
* [FLOAT]     `max_percent_normal_cells`
* [FLOAT]     `max_percent_stromal_cells`
* [FLOAT]     `max_percent_tumor_cells`
* [FLOAT]     `max_percent_tumor_nuclei`
* [FLOAT]     `min_percent_lymphocyte_infiltration`
* [FLOAT]     `min_percent_monocyte_infiltration`
* [FLOAT]     `min_percent_necrosis`
* [FLOAT]     `min_percent_neutrophil_infiltration`
* [FLOAT]     `min_percent_normal_cells`
* [FLOAT]     `min_percent_stromal_cells`
* [FLOAT]     `min_percent_tumor_cells`
* [FLOAT]     `min_percent_tumor_nuclei`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
