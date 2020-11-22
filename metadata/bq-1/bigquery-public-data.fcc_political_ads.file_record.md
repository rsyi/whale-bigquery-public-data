# `fcc_political_ads.file_record`
`bq-1` | `bigquery-public-data`
The  file_record table represents original files retrieved from the FCC, with extra
fields added such as a path to a plain text version of the file.  Each file is a receipt showing how much someone spent to run a political ad.

Retrieved from: https://publicfiles.fcc.gov/developer/!/file/get_file_id_fileId_format

## Column details
* [STRING]    `fileRecordId`
  - 
      Primary key for file_record table
* [BOOLEAN]   `duplicateContent`
  - 
      The original FCC file records have duplicates, that is, multiple
      file_record rows may point the same rawFilePath. Each duplicate
      file_record row has duplicateContent=true. Even though they collectively
      point to the same rawFilePath, each duplicate file_record row still has
      its own unique fileId.
* [STRING]    `fileExtension`
  - 
      File extension of the original file the broadcaster sent the FCC, like
      'pdf', 'docx' or 'rtf'. Even though these might not have been PDFs
      originally, the FCC converts them to PDFs after upload, so all the files
      available via the FCC are PDFs.
* [STRING]    `fileId`
  - 
      Unique id for a file
* [STRING]    `fileManagerId`
  - 
      Unique ID for a file manager
* [STRING]    `fileName`
  - 
      Name of the original file the broadcaster sent to the FCC, without
      the file extension, e.g., 'Jane Smith for California Governor
      Invoice'.
* [INTEGER]   `fileSize`
  - 
      Size in bytes of the original file the broadcaster sent the FCC, like '100000'.
* [STRING]    `fileStatus`
  - 
      Status of the file. Format is {uploadStatus}_{convertStatus}, where
      {uploadStatus} may be: PEN - Pending - upload processing has started, ERR
      - Error - there was an error converting the file to PDF, COM - Completed -
      upload and conversion is complete. {convertStatus} may be: UPL - Upload -
      file is being uploaded, CVT - file is being converted to PDF, COM_CVT -
      completed conversion, ERR_CVT - error in conversion, CPY - upload was
      already PDF with no need to convert, DLQ - error in internal processing.
      ETL - nightly data copy from a different database source (if preceded by
      err, error during ETL), INS - insertion, a very temporary status while the
      record is being inserted. PRC - processing (if preceded by err, means
      error in processing). An example value for fileStatus could be COM_CPY.

* [STRING]    `folderId`
  - 
      Unique ID for a folder
* [STRING]    `folderPath`
  - 
      Path to the folder in the FCC's API containing the original file, like 'Political
      Files/2016/Federal/US Senate/Jane Smith'
* [TIMESTAMP] `lastUpdateTs`
  - 
      Most recent time in UTC that a broadcaster sent the FCC an update to the previously submitted
      file, like '2019-01-01T00:00:00Z'. Uses ISO 8601 format.
* [STRING]    `md5`
  - 
      MD5 hash of the original file, encoded in base64. Uniquely identifies each original file.
* [BOOLEAN]   `ocrFile`
  - 
      Whether the raw file has been converted into machine-readable text.
* [STRING]    `ocrFileDirectory`
  - 
      If available, path in Google Cloud Storage to the machine-readable
      plain text content of the original file. To retrieve the files, use the
      gsutil command from the Cloud SDK, like 'gsutil cp
      gs://fcc-files-ocr/125/akRGEs7DFUpkNYSZvZsHkg==/* ~/files'
* [STRING]    `rawFilePath`
  - 
      Path in Google Cloud Storage to the original file.
* [STRING]    `stationId`
  - 
      Unique identifier specifying the TV or radio broadcasting station
      who ran the ads described in this receipt.
* [INTEGER]   `year`
  - 
      Calendar year during which the ads described in the receipt were shown.
* [STRING]    `rawFileLink`
  - 
      HTTP URL to view the original file in your Web browser.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
