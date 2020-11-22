# `fcc_political_ads.content_info`
`bq-1` | `bigquery-public-data`
This data table aims to extract useful information from the raw receipt PDF files available from the FCC. Data in this table has been manually extracted and annotated by ProPublica’s Free the Files Effort or Google. This is an experimental dataset based on humans reading PDFs and extracting data, and there may be errors- please do not use as a complete or comprehensive dataset. Current annotation efforts will omit files that lack gross spend, advertiser or ad air date information.This table will be continually expanded with additional annotated files.

## Column details
* [STRING]    `contentInfoId`
  - Primary key for content_info table
* [STRING]    `advertiser`
  - 
      Text listed in the file as the advertiser
* [STRING]    `candidate`
  - 
      Candidate name from FEC record
* [INTEGER]   `grossSpend`
  - 
      Gross amount paid for the ad in lower monetary value i.e., cents not
      dollars
* [STRING]    `infoSource`
  - 
      Where the annotation came from. Currently, the only value is 'MANUAL', for
      annotations a person manually transcribed from the file. We intend to
      eventually add annotations written automatically by algorithms.
* [BOOLEAN]   `invalidOcr`
  - 
      Indicates if the ocr does not match the raw file text. In this case, the
      OCR process needs more work and the file is not ready to be
      transcribed.
* [STRING]    `ocrFileDirectory`
  - 
      If available, path in GCS Storage to the machine-readable plain text
      content of the original file. To retrieve the files, use the gsutil
      command from the Cloud SDK, like 'gsutil cp
      gs://fcc-files-ocr/125/akRGEs7DFUpkNYSZvZsHkg==/* ~/files'
* [STRING]    `organization`
  - 
      Political campaign organization from FEC that paid for the ad
* [STRING]    `periodEnd`
  - 
      Last day the ad aired in the broadcaster's local timezone as
      YYYY-MM-DD
* [STRING]    `periodStart`
  - 
      First day the ad aired in the broadcaster's local timezone as
      YYYY-MM-DD
* [STRING]    `product`
  - 
      Text listed in the file as the product
* [STRING]    `rawFileLink`
  - 
      HTTP URL to view the original file in your Web browser.
* [STRING]    `rawFilePath`
  - 
      Cloud Storage URI to original file uploaded to the broadcaster
* [STRING]    `sourceId`
  - 
      For annotations that came from an external dataset (like ProPublica), the
      unique identifier for the annotation in the source dataset.
* [STRING]    `agency`
  - 
      Text listed in the file as the agency that facilitated the ad purchase

-------------------------------------------------------------------------------
*Do not make edits above this line.*
