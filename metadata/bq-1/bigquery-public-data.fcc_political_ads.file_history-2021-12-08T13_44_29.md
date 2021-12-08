# `fcc_political_ads.file_history-2021-12-08T13_44_29`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `fileHistoryId`
  - Primary key for file_history table
* [TIMESTAMP] `createdTimestamp`
  - 
      When this file_history entry was created, i.e. the last time the
      broadcaster uploaded an updated file to the FCC. createdTimestap is
      overwhelmingly identical to lastUpdatedTimestamp, and when they differ,
      it is only by seconds, so you can consider them to be duplicates.
* [STRING]    `fileExtension`
  - 
      File extension of the original file the broadcaster sent the FCC, like
      'pdf', 'docx' or 'rtf'. Even though these might not have been PDFs
      originally, the FCC converts them to PDFs after upload, so all the files
      available via the FCC and our project are PDFs.
* [STRING]    `fileFolderPath`
  - 
      Path to the folder in the FCC's API containing the original file, like
      'Political Files/2016/Federal/US Senate/Jane Smith'
* [STRING]    `fileId`
* [STRING]    `fileManagerId`
* [STRING]    `fileName`
  - 
      Name of the original file the broadcaster sent to the FCC, without the
      file extension, like 'Jane Smith for California Governor Invoice'. Often
      (but not necessarily) contains interesting keywords, like names of
      candidates ('Jane Smith') or locales ('California'). Other times, 
      a generic file name with no interesting keywords like 'Receipt
      1234'.
* [INTEGER]   `fileSize`
  - 
      Size in bytes of the original file the broadcaster sent the FCC, like
      '100000'.
* [STRING]    `fileStatus`
* [STRING]    `folderId`
* [STRING]    `historyStatus`
  - 
      Description of what happened to the file at this point in history. One of
      { 'purge', 'move', 'delete', 'new', 'restore', 'rename' }
* [TIMESTAMP] `lastUpdatedTimestamp`
  - 
      The last time the broadcaster sent an updated version of the file to the
      FCC. lastUpdatedTimestap is overwhelmingly identical to the
      createdTimestamp column, and when they differ, it is only by seconds, so
      you can consider them to be duplicates.
* [STRING]    `stationId`
  - 
      Unique identifier specifying the TV or radio broadcasting station who
      ran the ads described in this receipt.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
